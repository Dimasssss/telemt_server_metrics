# Server Metrics 2026-03-10 21:43:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26173.2 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706160
telemt_connections_bad_total 8155
telemt_handshake_timeouts_total 8175
telemt_upstream_connect_attempt_total 5654
telemt_upstream_connect_success_total 5645
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 352
telemt_me_reconnect_attempts_total 15912
telemt_me_reconnect_success_total 4254
telemt_me_reader_eof_total 4703
telemt_me_idle_close_by_peer_total 4703
telemt_me_route_drop_no_conn_total 294500
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667499
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3343
telemt_desync_full_logged_total 939
telemt_desync_suppressed_total 2404
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 1262
telemt_desync_frames_bucket_total{bucket="gt_10"} 1129
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4650
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4248
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 667304
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 9615880584 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 202192347516 (188.31 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26230.0 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309138
telemt_connections_bad_total 2273
telemt_handshake_timeouts_total 17439
telemt_upstream_connect_attempt_total 12056
telemt_upstream_connect_success_total 9194
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 12056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 5674
telemt_me_reconnect_success_total 4869
telemt_me_reader_eof_total 5106
telemt_me_idle_close_by_peer_total 5104
telemt_me_route_drop_no_conn_total 163300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259648
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1516
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4953
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4848
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 261921
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2615250174 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 61636736064 (57.40 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26229.8 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505582
telemt_connections_bad_total 2913
telemt_handshake_timeouts_total 33575
telemt_upstream_connect_attempt_total 7402
telemt_upstream_connect_success_total 7286
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 15886
telemt_me_reconnect_success_total 4838
telemt_me_reader_eof_total 5329
telemt_me_idle_close_by_peer_total 5329
telemt_me_route_drop_no_conn_total 175446
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1426
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 1029
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 490
telemt_desync_frames_bucket_total{bucket="gt_10"} 612
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 5261
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4827
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 441881
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 6512028789 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 143667755625 (133.80 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26230.1 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350065
telemt_connections_bad_total 25423
telemt_handshake_timeouts_total 30702
telemt_upstream_connect_attempt_total 7091
telemt_upstream_connect_success_total 7091
telemt_upstream_connect_attempts_per_request{bucket="1"} 7091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 6738
telemt_me_reconnect_success_total 5716
telemt_me_reader_eof_total 5994
telemt_me_idle_close_by_peer_total 5994
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 114119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281330
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5813
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5702
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 281008
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 3981967692 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 84839511444 (79.01 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26230.5 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368834
telemt_connections_bad_total 1139
telemt_handshake_timeouts_total 2345
telemt_upstream_connect_attempt_total 8040
telemt_upstream_connect_success_total 8007
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 10364
telemt_me_reconnect_success_total 6610
telemt_me_reader_eof_total 6927
telemt_me_idle_close_by_peer_total 6927
telemt_me_route_drop_no_conn_total 131068
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345663
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2067
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 766
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6823
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6610
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 345524
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 6343403368 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 123391264688 (114.92 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 49
```