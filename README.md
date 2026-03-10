# Server Metrics 2026-03-10 16:57:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9036.0 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309217
telemt_connections_bad_total 1355
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 1536
telemt_upstream_connect_success_total 1528
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 9185
telemt_me_reconnect_success_total 1048
telemt_me_reader_eof_total 1264
telemt_me_idle_close_by_peer_total 1264
telemt_me_route_drop_no_conn_total 136028
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1330
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 503
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1294
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1042
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 296580
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 3906153168 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 86629761524 (80.68 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9092.8 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124684
telemt_connections_bad_total 1673
telemt_handshake_timeouts_total 8894
telemt_upstream_connect_attempt_total 2022
telemt_upstream_connect_success_total 2011
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 1518
telemt_me_reconnect_success_total 1507
telemt_me_reader_eof_total 1554
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 34932
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107665
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 554
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1514
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 107647
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 1312204612 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 28782916564 (26.81 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9092.7 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238002
telemt_connections_bad_total 695
telemt_handshake_timeouts_total 28181
telemt_upstream_connect_attempt_total 3099
telemt_upstream_connect_success_total 3045
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1540
telemt_me_reconnect_success_total 1506
telemt_me_reader_eof_total 1565
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 74496
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188792
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1532
telemt_me_writer_restored_same_endpoint_total 1495
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 189768
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 2595582969 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 55312970225 (51.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9093.1 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146665
telemt_connections_bad_total 9055
telemt_handshake_timeouts_total 13791
telemt_upstream_connect_attempt_total 2300
telemt_upstream_connect_success_total 2299
telemt_upstream_connect_attempts_per_request{bucket="1"} 2299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1060
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1837
telemt_me_idle_close_by_peer_total 1837
telemt_me_route_drop_no_conn_total 48727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117331
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 367
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1799
telemt_me_writer_restored_same_endpoint_total 1778
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 117189
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 2120664596 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 30298686388 (28.22 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9092.8 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159999
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 1357
telemt_upstream_connect_attempt_total 2904
telemt_upstream_connect_success_total 2896
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2385
telemt_me_reconnect_success_total 2370
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2401
telemt_me_route_drop_no_conn_total 59879
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149561
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 736
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2390
telemt_me_writer_restored_same_endpoint_total 2370
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 149501
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 2679945840 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 45787794016 (42.64 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 101
```