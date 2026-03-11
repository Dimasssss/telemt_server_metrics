# Server Metrics 2026-03-11 10:10:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71016.5 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1547721
telemt_connections_bad_total 24384
telemt_handshake_timeouts_total 40944
telemt_upstream_connect_attempt_total 14643
telemt_upstream_connect_success_total 14634
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 788
telemt_me_reconnect_attempts_total 22755
telemt_me_reconnect_success_total 11067
telemt_me_reader_eof_total 11985
telemt_me_idle_close_by_peer_total 11985
telemt_me_route_drop_no_conn_total 569862
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1403707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6963
telemt_desync_full_logged_total 1930
telemt_desync_suppressed_total 5033
telemt_desync_frames_bucket_total{bucket="1_2"} 1836
telemt_desync_frames_bucket_total{bucket="3_10"} 2633
telemt_desync_frames_bucket_total{bucket="gt_10"} 2494
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11542
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11061
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 1402287
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 18326976800 (17.07 GB)
telemt_user_octets_to_client{user="hello"} 400534360992 (373.03 GB)
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71073.3 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592289
telemt_connections_bad_total 10180
telemt_handshake_timeouts_total 34583
telemt_upstream_connect_attempt_total 23698
telemt_upstream_connect_success_total 20769
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 15122
telemt_me_reconnect_success_total 14281
telemt_me_reader_eof_total 15126
telemt_me_idle_close_by_peer_total 15124
telemt_me_route_drop_no_conn_total 244063
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502009
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2263
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1566
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 697
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14451
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14259
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 504245
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 4926188614 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 140025753732 (130.41 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71073.2 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1027850
telemt_connections_bad_total 7698
telemt_handshake_timeouts_total 99905
telemt_upstream_connect_attempt_total 19222
telemt_upstream_connect_success_total 18986
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 19222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 792
telemt_me_reconnect_attempts_total 26732
telemt_me_reconnect_success_total 14363
telemt_me_reader_eof_total 15403
telemt_me_idle_close_by_peer_total 15403
telemt_me_route_drop_no_conn_total 338891
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 880681
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2511
telemt_desync_full_logged_total 741
telemt_desync_suppressed_total 1770
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 921
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14935
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 14352
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 881493
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 10444191057 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 270099443629 (251.55 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71073.7 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749361
telemt_connections_bad_total 66909
telemt_handshake_timeouts_total 71912
telemt_upstream_connect_attempt_total 19496
telemt_upstream_connect_success_total 19496
telemt_upstream_connect_attempts_per_request{bucket="1"} 19496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 729
telemt_me_reconnect_attempts_total 17020
telemt_me_reconnect_success_total 15965
telemt_me_reader_eof_total 16936
telemt_me_idle_close_by_peer_total 16935
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 235027
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588225
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1269
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16151
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15941
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 587597
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 6768973168 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 169456741604 (157.82 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71073.4 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797513
telemt_connections_bad_total 6083
telemt_handshake_timeouts_total 7718
telemt_upstream_connect_attempt_total 19115
telemt_upstream_connect_success_total 19038
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 801
telemt_me_reconnect_attempts_total 19184
telemt_me_reconnect_success_total 15390
telemt_me_reader_eof_total 16272
telemt_me_idle_close_by_peer_total 16272
telemt_me_route_drop_no_conn_total 275578
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724065
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3012
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 1875
telemt_desync_frames_bucket_total{bucket="1_2"} 1056
telemt_desync_frames_bucket_total{bucket="3_10"} 1219
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15703
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15390
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 723744
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 11222021163 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 265379221902 (247.15 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 118
```