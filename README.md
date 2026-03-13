# Server Metrics 2026-03-13 13:58:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 115220.7 (32h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3499949
telemt_connections_bad_total 37389
telemt_handshake_timeouts_total 59810
telemt_upstream_connect_attempt_total 22537
telemt_upstream_connect_success_total 22413
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2131
telemt_me_reconnect_attempts_total 26785
telemt_me_reconnect_success_total 16701
telemt_me_reader_eof_total 17954
telemt_me_idle_close_by_peer_total 17953
telemt_me_route_drop_no_conn_total 1298761
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3212984
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13298
telemt_desync_full_logged_total 3477
telemt_desync_suppressed_total 9821
telemt_desync_frames_bucket_total{bucket="1_2"} 3386
telemt_desync_frames_bucket_total{bucket="3_10"} 5031
telemt_desync_frames_bucket_total{bucket="gt_10"} 4881
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17249
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16688
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 3212851
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 44319978712 (41.28 GB)
telemt_user_octets_to_client{user="hello"} 1021927191032 (951.74 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14884.5 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207289
telemt_connections_bad_total 11841
telemt_handshake_timeouts_total 5284
telemt_upstream_connect_attempt_total 3654
telemt_upstream_connect_success_total 3577
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 4014
telemt_me_reconnect_success_total 2782
telemt_me_reader_eof_total 2913
telemt_me_idle_close_by_peer_total 2913
telemt_me_route_drop_no_conn_total 75274
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184758
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2844
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2775
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 184783
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 1864691396 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 51849900264 (48.29 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 144841.1 (40h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2625583
telemt_connections_bad_total 26859
telemt_handshake_timeouts_total 175578
telemt_upstream_connect_attempt_total 32698
telemt_upstream_connect_success_total 32688
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3207
telemt_me_reconnect_attempts_total 27701
telemt_me_reconnect_success_total 25155
telemt_me_reader_eof_total 26670
telemt_me_idle_close_by_peer_total 26669
telemt_me_route_drop_no_conn_total 882047
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2142474
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7516
telemt_desync_full_logged_total 2461
telemt_desync_suppressed_total 5055
telemt_desync_frames_bucket_total{bucket="1_2"} 1187
telemt_desync_frames_bucket_total{bucket="3_10"} 2735
telemt_desync_frames_bucket_total{bucket="gt_10"} 3594
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 25449
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25114
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 2141887
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 35768783196 (33.31 GB)
telemt_user_octets_to_client{user="hello"} 762547032813 (710.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 144841.5 (40h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1673470
telemt_connections_bad_total 18056
telemt_handshake_timeouts_total 119125
telemt_upstream_connect_attempt_total 46116
telemt_upstream_connect_success_total 43794
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 45842
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11840
telemt_me_reconnect_attempts_total 39714
telemt_me_reconnect_success_total 30747
telemt_me_reader_eof_total 33058
telemt_me_idle_close_by_peer_total 33051
telemt_me_route_drop_no_conn_total 597248
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400017
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2812
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 1900
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 31257
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30723
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1404734
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 21649347189 (20.16 GB)
telemt_user_octets_to_client{user="hello"} 543527937542 (506.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14277.3 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224278
telemt_connections_bad_total 3860
telemt_handshake_timeouts_total 2045
telemt_upstream_connect_attempt_total 2943
telemt_upstream_connect_success_total 2844
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 2943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 10180
telemt_me_reconnect_success_total 2104
telemt_me_reader_eof_total 2370
telemt_me_idle_close_by_peer_total 2370
telemt_me_route_drop_no_conn_total 87879
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209712
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 731
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2358
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2100
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 209694
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 2216570916 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 64341931904 (59.92 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 92
```