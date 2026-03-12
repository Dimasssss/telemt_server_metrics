# Server Metrics 2026-03-12 06:40:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2514.3 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72085
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 785
telemt_upstream_connect_attempt_total 532
telemt_upstream_connect_success_total 529
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 373
telemt_me_reconnect_success_total 372
telemt_me_reader_eof_total 353
telemt_me_idle_close_by_peer_total 353
telemt_me_route_drop_no_conn_total 23251
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68571
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 366
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 68537
telemt_user_connections_current{user="hello"} 1193
telemt_user_octets_from_client{user="hello"} 1569481968 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 20488470168 (19.08 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32134.7 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134287
telemt_connections_bad_total 1781
telemt_handshake_timeouts_total 5248
telemt_upstream_connect_attempt_total 8459
telemt_upstream_connect_success_total 8454
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 6694
telemt_me_reconnect_success_total 6657
telemt_me_reader_eof_total 7080
telemt_me_idle_close_by_peer_total 7080
telemt_me_route_drop_no_conn_total 39894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119925
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6713
telemt_me_writer_restored_same_endpoint_total 6648
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 120114
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 1796176151 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 52611662746 (49.00 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32134.6 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471004
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 34733
telemt_upstream_connect_attempt_total 8740
telemt_upstream_connect_success_total 8738
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 6833
telemt_me_reconnect_success_total 6768
telemt_me_reader_eof_total 7091
telemt_me_idle_close_by_peer_total 7091
telemt_me_route_drop_no_conn_total 75396
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226810
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 985
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 671
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6750
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 227111
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 2406392480 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 77605202201 (72.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32134.9 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205029
telemt_connections_bad_total 1737
telemt_handshake_timeouts_total 13022
telemt_upstream_connect_attempt_total 9212
telemt_upstream_connect_success_total 9173
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 246
telemt_me_reconnect_attempts_total 7589
telemt_me_reconnect_success_total 7561
telemt_me_reader_eof_total 8029
telemt_me_idle_close_by_peer_total 8029
telemt_me_route_drop_no_conn_total 64119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165266
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 272
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7605
telemt_me_writer_restored_same_endpoint_total 7540
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 165130
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 1879547408 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 51775510208 (48.22 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32134.9 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215148
telemt_connections_bad_total 310
telemt_handshake_timeouts_total 1286
telemt_upstream_connect_attempt_total 10957
telemt_upstream_connect_success_total 10832
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 10957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 10720
telemt_me_reconnect_success_total 9210
telemt_me_reader_eof_total 9599
telemt_me_idle_close_by_peer_total 9599
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 65877
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204407
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 811
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9341
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9191
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 204361
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 1795181596 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 47060301940 (43.83 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 122
```