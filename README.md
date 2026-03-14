# Server Metrics 2026-03-14 20:49:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 27126.8 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024116
telemt_connections_bad_total 42340
telemt_handshake_timeouts_total 14627
telemt_upstream_connect_attempt_total 4956
telemt_upstream_connect_success_total 4933
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 4321
telemt_me_reconnect_success_total 3514
telemt_me_reader_eof_total 3708
telemt_me_idle_close_by_peer_total 3708
telemt_me_route_drop_no_conn_total 391231
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910219
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3095
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 2213
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 1142
telemt_desync_frames_bucket_total{bucket="gt_10"} 1223
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3597
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3505
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 910165
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 16261556324 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 308133026664 (286.97 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 27132.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402237
telemt_connections_bad_total 30353
telemt_handshake_timeouts_total 12344
telemt_upstream_connect_attempt_total 5844
telemt_upstream_connect_success_total 5784
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5163
telemt_me_reconnect_success_total 4366
telemt_me_reader_eof_total 4559
telemt_me_idle_close_by_peer_total 4559
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 118543
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336662
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1646
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4482
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4343
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 336600
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 4964832080 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 117647106688 (109.57 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 26994.9 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872529
telemt_connections_bad_total 3378
telemt_handshake_timeouts_total 213092
telemt_upstream_connect_attempt_total 5199
telemt_upstream_connect_success_total 5182
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 7732
telemt_me_reconnect_success_total 3820
telemt_me_reader_eof_total 4096
telemt_me_idle_close_by_peer_total 4096
telemt_me_route_drop_no_conn_total 196887
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559123
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2075
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1271
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3985
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3787
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 558951
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 8328127804 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 206261862812 (192.10 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 26849.5 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465272
telemt_connections_bad_total 99444
telemt_handshake_timeouts_total 54284
telemt_upstream_connect_attempt_total 6176
telemt_upstream_connect_success_total 6175
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 5742
telemt_me_reconnect_success_total 4820
telemt_me_reader_eof_total 5053
telemt_me_idle_close_by_peer_total 5053
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 107065
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303689
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 684
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4906
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4808
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 303604
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 4277382320 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 94341718508 (87.86 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 27144.9 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389793
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 3944
telemt_upstream_connect_attempt_total 5783
telemt_upstream_connect_success_total 5668
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 5783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 4945
telemt_me_reconnect_success_total 4269
telemt_me_reader_eof_total 4504
telemt_me_idle_close_by_peer_total 4504
telemt_me_route_drop_no_conn_total 123129
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 935
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4368
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 361559
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 5840828612 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 152277689880 (141.82 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 58
```