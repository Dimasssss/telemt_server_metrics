# Server Metrics 2026-03-10 17:12:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9954.6 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336721
telemt_connections_bad_total 1362
telemt_handshake_timeouts_total 1615
telemt_upstream_connect_attempt_total 1765
telemt_upstream_connect_success_total 1757
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 9357
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1437
telemt_me_idle_close_by_peer_total 1437
telemt_me_route_drop_no_conn_total 147246
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323518
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1464
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1467
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 323450
telemt_user_connections_current{user="hello"} 1574
telemt_user_octets_from_client{user="hello"} 4202977700 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 95610539764 (89.04 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10011.4 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135230
telemt_connections_bad_total 1673
telemt_handshake_timeouts_total 9377
telemt_upstream_connect_attempt_total 2322
telemt_upstream_connect_success_total 2311
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1803
telemt_me_idle_close_by_peer_total 1803
telemt_me_route_drop_no_conn_total 38069
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117196
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 571
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1758
telemt_me_writer_restored_same_endpoint_total 1729
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 117177
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 1528960768 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 31104133972 (28.97 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10011.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260300
telemt_connections_bad_total 794
telemt_handshake_timeouts_total 30313
telemt_upstream_connect_attempt_total 3384
telemt_upstream_connect_success_total 3325
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1757
telemt_me_reconnect_success_total 1717
telemt_me_reader_eof_total 1777
telemt_me_idle_close_by_peer_total 1777
telemt_me_route_drop_no_conn_total 82135
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206987
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1744
telemt_me_writer_restored_same_endpoint_total 1706
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 207963
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 3022891441 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 61080536481 (56.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10011.8 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161284
telemt_connections_bad_total 9889
telemt_handshake_timeouts_total 15437
telemt_upstream_connect_attempt_total 2499
telemt_upstream_connect_success_total 2499
telemt_upstream_connect_attempts_per_request{bucket="1"} 2499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1948
telemt_me_reconnect_success_total 1937
telemt_me_reader_eof_total 2010
telemt_me_idle_close_by_peer_total 2010
telemt_me_route_drop_no_conn_total 52833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128879
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 410
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_restored_same_endpoint_total 1926
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 128725
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 2202132868 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 34859243560 (32.47 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10011.5 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174623
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 1408
telemt_upstream_connect_attempt_total 3088
telemt_upstream_connect_success_total 3078
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 2518
telemt_me_reconnect_success_total 2502
telemt_me_reader_eof_total 2559
telemt_me_idle_close_by_peer_total 2559
telemt_me_route_drop_no_conn_total 65118
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163436
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 839
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2522
telemt_me_writer_restored_same_endpoint_total 2502
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 163376
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 3932104656 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 49635235704 (46.23 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 78
```