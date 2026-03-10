# Server Metrics 2026-03-10 16:21:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6892.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244993
telemt_connections_bad_total 1342
telemt_handshake_timeouts_total 1111
telemt_upstream_connect_attempt_total 1276
telemt_upstream_connect_success_total 1268
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 7639
telemt_me_reconnect_success_total 879
telemt_me_reader_eof_total 1044
telemt_me_idle_close_by_peer_total 1044
telemt_me_route_drop_no_conn_total 109656
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233963
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 882
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_me_writer_removed_unexpected_total 1080
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 873
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 233910
telemt_user_connections_current{user="hello"} 1399
telemt_user_octets_from_client{user="hello"} 2870481768 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 68745179640 (64.02 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6949.2 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98644
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 7948
telemt_upstream_connect_attempt_total 1577
telemt_upstream_connect_success_total 1567
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1191
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1208
telemt_me_idle_close_by_peer_total 1208
telemt_me_route_drop_no_conn_total 26488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83549
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 484
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1184
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 83535
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 1025257932 (977.76 MB)
telemt_user_octets_to_client{user="hello"} 23283017564 (21.68 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6948.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176095
telemt_connections_bad_total 507
telemt_handshake_timeouts_total 13710
telemt_upstream_connect_attempt_total 2674
telemt_upstream_connect_success_total 2627
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1231
telemt_me_reconnect_success_total 1203
telemt_me_reader_eof_total 1238
telemt_me_idle_close_by_peer_total 1238
telemt_me_route_drop_no_conn_total 58368
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147138
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 148118
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 1987890629 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 44180670905 (41.15 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6949.7 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114869
telemt_connections_bad_total 6949
telemt_handshake_timeouts_total 11486
telemt_upstream_connect_attempt_total 1740
telemt_upstream_connect_success_total 1740
telemt_upstream_connect_attempts_per_request{bucket="1"} 1740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 794
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1366
telemt_me_reconnect_success_total 1359
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 37855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91426
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1363
telemt_me_writer_restored_same_endpoint_total 1348
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 91300
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 1435527640 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 22545204632 (21.00 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6949.1 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125243
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 854
telemt_upstream_connect_attempt_total 2001
telemt_upstream_connect_success_total 1995
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1610
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1622
telemt_me_idle_close_by_peer_total 1622
telemt_me_route_drop_no_conn_total 47179
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117034
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 625
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1610
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 116984
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 2030095656 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 35598020752 (33.15 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 92
```