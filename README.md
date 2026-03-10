# Server Metrics 2026-03-10 17:02:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9342.6 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318452
telemt_connections_bad_total 1360
telemt_handshake_timeouts_total 1570
telemt_upstream_connect_attempt_total 1659
telemt_upstream_connect_success_total 1651
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 9261
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 1340
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 140092
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305669
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 995
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1370
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1117
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 305602
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 3981154416 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 89707549812 (83.55 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9399.2 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128431
telemt_connections_bad_total 1673
telemt_handshake_timeouts_total 9129
telemt_upstream_connect_attempt_total 2155
telemt_upstream_connect_success_total 2144
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 1637
telemt_me_reconnect_success_total 1625
telemt_me_reader_eof_total 1673
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 35965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111062
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1634
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 111044
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 1346429400 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 29814058708 (27.77 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9399.1 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245657
telemt_connections_bad_total 698
telemt_handshake_timeouts_total 28218
telemt_upstream_connect_attempt_total 3229
telemt_upstream_connect_success_total 3173
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 3229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1645
telemt_me_reconnect_success_total 1606
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 76788
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194906
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 573
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 416
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1633
telemt_me_writer_restored_same_endpoint_total 1595
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 195884
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 2674361945 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 57473056861 (53.53 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9399.5 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151707
telemt_connections_bad_total 9335
telemt_handshake_timeouts_total 14149
telemt_upstream_connect_attempt_total 2389
telemt_upstream_connect_success_total 2389
telemt_upstream_connect_attempts_per_request{bucket="1"} 2389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1104
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 1881
telemt_me_reconnect_success_total 1872
telemt_me_reader_eof_total 1939
telemt_me_idle_close_by_peer_total 1939
telemt_me_route_drop_no_conn_total 50288
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 381
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1883
telemt_me_writer_restored_same_endpoint_total 1861
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 121378
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 2146357328 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 31840102220 (29.65 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9399.2 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165165
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 1381
telemt_upstream_connect_attempt_total 2974
telemt_upstream_connect_success_total 2966
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 2447
telemt_me_reconnect_success_total 2432
telemt_me_reader_eof_total 2489
telemt_me_idle_close_by_peer_total 2489
telemt_me_route_drop_no_conn_total 61832
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154536
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 766
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 500
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2452
telemt_me_writer_restored_same_endpoint_total 2432
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 154476
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 2722501900 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 47286971884 (44.04 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 103
```