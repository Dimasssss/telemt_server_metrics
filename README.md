# Server Metrics 2026-03-10 16:16:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6585.7 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236034
telemt_connections_bad_total 1281
telemt_handshake_timeouts_total 1077
telemt_upstream_connect_attempt_total 1255
telemt_upstream_connect_success_total 1247
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 7618
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1023
telemt_me_route_drop_no_conn_total 105996
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225280
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_me_writer_removed_unexpected_total 1059
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 852
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 225227
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 2785988460 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 66589996220 (62.02 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 6642.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94512
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 7661
telemt_upstream_connect_attempt_total 1539
telemt_upstream_connect_success_total 1529
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1153
telemt_me_reconnect_success_total 1144
telemt_me_reader_eof_total 1170
telemt_me_idle_close_by_peer_total 1170
telemt_me_route_drop_no_conn_total 25301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_restored_same_endpoint_total 1123
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 79865
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 957032720 (912.70 MB)
telemt_user_octets_to_client{user="hello"} 22005219696 (20.49 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 6642.3 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169328
telemt_connections_bad_total 500
telemt_handshake_timeouts_total 13590
telemt_upstream_connect_attempt_total 2616
telemt_upstream_connect_success_total 2569
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 1145
telemt_me_reader_eof_total 1180
telemt_me_idle_close_by_peer_total 1180
telemt_me_route_drop_no_conn_total 55637
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140566
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 141546
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 1936702749 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 42238532309 (39.34 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 6642.8 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110095
telemt_connections_bad_total 6643
telemt_handshake_timeouts_total 11160
telemt_upstream_connect_attempt_total 1697
telemt_upstream_connect_success_total 1697
telemt_upstream_connect_attempts_per_request{bucket="1"} 1697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 776
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 1323
telemt_me_reconnect_success_total 1316
telemt_me_reader_eof_total 1350
telemt_me_idle_close_by_peer_total 1350
telemt_me_route_drop_no_conn_total 36657
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87521
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_restored_same_endpoint_total 1305
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 87402
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 1385598508 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 21483932952 (20.01 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6642.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120436
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 841
telemt_upstream_connect_attempt_total 1919
telemt_upstream_connect_success_total 1913
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1528
telemt_me_reconnect_success_total 1517
telemt_me_reader_eof_total 1539
telemt_me_idle_close_by_peer_total 1539
telemt_me_route_drop_no_conn_total 45455
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112424
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 610
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_restored_same_endpoint_total 1517
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 112375
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 1980256032 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 33844749780 (31.52 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 91
```