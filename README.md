# Server Metrics 2026-03-10 16:42:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8118.1 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281973
telemt_connections_bad_total 1355
telemt_handshake_timeouts_total 1379
telemt_upstream_connect_attempt_total 1402
telemt_upstream_connect_success_total 1394
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 9096
telemt_me_reconnect_success_total 960
telemt_me_reader_eof_total 1168
telemt_me_idle_close_by_peer_total 1168
telemt_me_route_drop_no_conn_total 124649
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269876
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1103
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 425
telemt_me_writer_removed_unexpected_total 1204
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 954
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 269821
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 3545302832 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 78915200224 (73.50 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8174.8 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113991
telemt_connections_bad_total 1672
telemt_handshake_timeouts_total 8601
telemt_upstream_connect_attempt_total 1824
telemt_upstream_connect_success_total 1814
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1369
telemt_me_reconnect_success_total 1359
telemt_me_reader_eof_total 1395
telemt_me_idle_close_by_peer_total 1395
telemt_me_route_drop_no_conn_total 31651
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97664
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 510
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 97646
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 1169461372 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 26610125948 (24.78 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8174.6 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215147
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 23585
telemt_upstream_connect_attempt_total 2933
telemt_upstream_connect_success_total 2879
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 2933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 1384
telemt_me_reader_eof_total 1433
telemt_me_idle_close_by_peer_total 1433
telemt_me_route_drop_no_conn_total 67552
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171002
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 465
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 171980
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 2149614785 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 49409068733 (46.02 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8174.9 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133061
telemt_connections_bad_total 8211
telemt_handshake_timeouts_total 13062
telemt_upstream_connect_attempt_total 1991
telemt_upstream_connect_success_total 1991
telemt_upstream_connect_attempts_per_request{bucket="1"} 1991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 921
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1541
telemt_me_reconnect_success_total 1534
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 43841
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105974
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 327
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1540
telemt_me_writer_restored_same_endpoint_total 1523
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 105837
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 1706755124 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 27660712168 (25.76 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8174.9 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145919
telemt_connections_bad_total 520
telemt_handshake_timeouts_total 1176
telemt_upstream_connect_attempt_total 2482
telemt_upstream_connect_success_total 2476
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2021
telemt_me_reconnect_success_total 2010
telemt_me_reader_eof_total 2037
telemt_me_idle_close_by_peer_total 2037
telemt_me_route_drop_no_conn_total 54934
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 688
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2026
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 136079
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 2342858664 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 41504345964 (38.65 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 90
```