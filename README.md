# Server Metrics 2026-03-10 16:11:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6279.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226796
telemt_connections_bad_total 1060
telemt_handshake_timeouts_total 1060
telemt_upstream_connect_attempt_total 1188
telemt_upstream_connect_success_total 1182
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 6254
telemt_me_reconnect_success_total 838
telemt_me_reader_eof_total 963
telemt_me_idle_close_by_peer_total 963
telemt_me_route_drop_no_conn_total 101873
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216432
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_me_writer_removed_unexpected_total 996
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 216377
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 2668493120 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 64129214644 (59.72 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6336.1 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90542
telemt_connections_bad_total 1659
telemt_handshake_timeouts_total 7576
telemt_upstream_connect_attempt_total 1422
telemt_upstream_connect_success_total 1414
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 1066
telemt_me_reader_eof_total 1075
telemt_me_idle_close_by_peer_total 1075
telemt_me_route_drop_no_conn_total 24016
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76151
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 459
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1068
telemt_me_writer_restored_same_endpoint_total 1045
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 76137
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 928875820 (885.85 MB)
telemt_user_octets_to_client{user="hello"} 21147206528 (19.69 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6335.9 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162249
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 12885
telemt_upstream_connect_attempt_total 2483
telemt_upstream_connect_success_total 2438
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 1088
telemt_me_idle_close_by_peer_total 1088
telemt_me_route_drop_no_conn_total 53047
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134352
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1074
telemt_me_writer_restored_same_endpoint_total 1044
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 135336
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 1720007861 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 40505502933 (37.72 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6336.4 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105929
telemt_connections_bad_total 6321
telemt_handshake_timeouts_total 10921
telemt_upstream_connect_attempt_total 1588
telemt_upstream_connect_success_total 1588
telemt_upstream_connect_attempts_per_request{bucket="1"} 1588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1246
telemt_me_reconnect_success_total 1240
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 35393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84068
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 267
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1241
telemt_me_writer_restored_same_endpoint_total 1229
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 83964
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 1359603808 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 19963232940 (18.59 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6336.0 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115941
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 825
telemt_upstream_connect_attempt_total 1759
telemt_upstream_connect_success_total 1753
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 1395
telemt_me_reader_eof_total 1416
telemt_me_idle_close_by_peer_total 1416
telemt_me_route_drop_no_conn_total 43505
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108042
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 586
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 392
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1402
telemt_me_writer_restored_same_endpoint_total 1395
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 107993
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 1812216516 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 31726678312 (29.55 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 116
```