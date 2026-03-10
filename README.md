# Server Metrics 2026-03-10 16:32:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7505.3 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264350
telemt_connections_bad_total 1353
telemt_handshake_timeouts_total 1267
telemt_upstream_connect_attempt_total 1361
telemt_upstream_connect_success_total 1353
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 9055
telemt_me_reconnect_success_total 919
telemt_me_reader_eof_total 1127
telemt_me_idle_close_by_peer_total 1127
telemt_me_route_drop_no_conn_total 117456
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 968
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 702
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_me_writer_removed_unexpected_total 1163
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 252712
telemt_user_connections_current{user="hello"} 1230
telemt_user_octets_from_client{user="hello"} 3323433048 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 74134815056 (69.04 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7562.1 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106789
telemt_connections_bad_total 1670
telemt_handshake_timeouts_total 8207
telemt_upstream_connect_attempt_total 1723
telemt_upstream_connect_success_total 1713
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1294
telemt_me_reconnect_success_total 1284
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 29179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91080
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 91066
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 1066535052 (1017.13 MB)
telemt_user_octets_to_client{user="hello"} 25047873476 (23.33 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7561.9 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193743
telemt_connections_bad_total 682
telemt_handshake_timeouts_total 18099
telemt_upstream_connect_attempt_total 2829
telemt_upstream_connect_success_total 2779
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1340
telemt_me_reconnect_success_total 1309
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1358
telemt_me_route_drop_no_conn_total 62929
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159718
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 160696
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 2057850845 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 46665976641 (43.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7562.4 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123923
telemt_connections_bad_total 7576
telemt_handshake_timeouts_total 12359
telemt_upstream_connect_attempt_total 1884
telemt_upstream_connect_success_total 1884
telemt_upstream_connect_attempts_per_request{bucket="1"} 1884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 865
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 1459
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 40530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98523
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 303
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 98394
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 1541109168 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 25227379656 (23.49 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7562.1 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135746
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 885
telemt_upstream_connect_attempt_total 2273
telemt_upstream_connect_success_total 2267
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1837
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1849
telemt_me_idle_close_by_peer_total 1849
telemt_me_route_drop_no_conn_total 51106
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126781
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 659
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1837
telemt_me_writer_restored_same_endpoint_total 1826
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 126731
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 2154858144 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 39031080632 (36.35 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 96
```