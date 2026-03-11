# Server Metrics 2026-03-11 01:52:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41114.0 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824621
telemt_connections_bad_total 9534
telemt_handshake_timeouts_total 11240
telemt_upstream_connect_attempt_total 8942
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 18485
telemt_me_reconnect_success_total 6818
telemt_me_reader_eof_total 7457
telemt_me_idle_close_by_peer_total 7457
telemt_me_route_drop_no_conn_total 335633
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779716
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3637
telemt_desync_full_logged_total 1023
telemt_desync_suppressed_total 2614
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7238
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6812
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 779456
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 10664319196 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 236172924808 (219.95 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41170.8 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353671
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 18009
telemt_upstream_connect_attempt_total 16265
telemt_upstream_connect_success_total 13379
telemt_upstream_connect_fail_total 2886
telemt_upstream_connect_attempts_per_request{bucket="1"} 16265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2886
telemt_me_keepalive_timeout_total 1727
telemt_me_reconnect_attempts_total 9166
telemt_me_reconnect_success_total 8349
telemt_me_reader_eof_total 8819
telemt_me_idle_close_by_peer_total 8817
telemt_me_route_drop_no_conn_total 175375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302447
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8458
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8328
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 304717
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2875831990 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 72028265936 (67.08 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41170.5 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588961
telemt_connections_bad_total 4521
telemt_handshake_timeouts_total 34342
telemt_upstream_connect_attempt_total 11259
telemt_upstream_connect_success_total 11105
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 11259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 19012
telemt_me_reconnect_success_total 7948
telemt_me_reader_eof_total 8635
telemt_me_idle_close_by_peer_total 8635
telemt_me_route_drop_no_conn_total 200749
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521407
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1524
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8402
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7937
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 522319
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 6945201929 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 159427112221 (148.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41171.0 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437631
telemt_connections_bad_total 39053
telemt_handshake_timeouts_total 42013
telemt_upstream_connect_attempt_total 11931
telemt_upstream_connect_success_total 11931
telemt_upstream_connect_attempts_per_request{bucket="1"} 11931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 426
telemt_me_reconnect_attempts_total 10885
telemt_me_reconnect_success_total 9850
telemt_me_reader_eof_total 10431
telemt_me_idle_close_by_peer_total 10431
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 132231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343052
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 737
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9971
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9832
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 342722
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 4267988532 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 92574951320 (86.22 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41170.6 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462003
telemt_connections_bad_total 5338
telemt_handshake_timeouts_total 2973
telemt_upstream_connect_attempt_total 12240
telemt_upstream_connect_success_total 12189
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 13842
telemt_me_reconnect_success_total 10071
telemt_me_reader_eof_total 10607
telemt_me_idle_close_by_peer_total 10607
telemt_me_route_drop_no_conn_total 151286
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2296
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10319
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10071
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 422486
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 8436892832 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 149972381120 (139.67 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```