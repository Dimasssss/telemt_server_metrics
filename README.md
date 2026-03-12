# Server Metrics 2026-03-12 07:21:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4963.4 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146762
telemt_connections_bad_total 1180
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 1059
telemt_upstream_connect_success_total 1051
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 766
telemt_me_reconnect_success_total 763
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 48857
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 761
telemt_me_writer_restored_same_endpoint_total 750
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 141088
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 2457326088 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 43326587220 (40.35 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34584.1 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164093
telemt_connections_bad_total 2170
telemt_handshake_timeouts_total 6350
telemt_upstream_connect_attempt_total 8982
telemt_upstream_connect_success_total 8977
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 7088
telemt_me_reconnect_success_total 7049
telemt_me_reader_eof_total 7498
telemt_me_idle_close_by_peer_total 7498
telemt_me_route_drop_no_conn_total 46688
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141541
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7106
telemt_me_writer_restored_same_endpoint_total 7040
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 141773
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 2241032047 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 58416148350 (54.40 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34583.9 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517128
telemt_connections_bad_total 2433
telemt_handshake_timeouts_total 38593
telemt_upstream_connect_attempt_total 9254
telemt_upstream_connect_success_total 9252
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 7218
telemt_me_reconnect_success_total 7151
telemt_me_reader_eof_total 7502
telemt_me_idle_close_by_peer_total 7502
telemt_me_route_drop_no_conn_total 91044
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268042
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1187
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 818
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7137
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7110
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 268334
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 2850412524 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 96974566973 (90.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34584.2 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232937
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 14665
telemt_upstream_connect_attempt_total 9744
telemt_upstream_connect_success_total 9704
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 7991
telemt_me_reconnect_success_total 7963
telemt_me_reader_eof_total 8458
telemt_me_idle_close_by_peer_total 8458
telemt_me_route_drop_no_conn_total 76185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191053
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8011
telemt_me_writer_restored_same_endpoint_total 7942
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 190920
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 2194413968 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 61200416356 (57.00 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34584.0 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248890
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 1870
telemt_upstream_connect_attempt_total 11699
telemt_upstream_connect_success_total 11558
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 11699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 11316
telemt_me_reconnect_success_total 9804
telemt_me_reader_eof_total 10215
telemt_me_idle_close_by_peer_total 10215
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 77308
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234063
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 943
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 629
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 9943
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9784
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 234017
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 2249659372 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 55608002672 (51.79 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 97
```