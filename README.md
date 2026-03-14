# Server Metrics 2026-03-14 22:57:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 2574.2 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42259
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 515
telemt_upstream_connect_success_total 513
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 348
telemt_me_idle_close_by_peer_total 348
telemt_me_route_drop_no_conn_total 12336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38981
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 38979
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 633615044 (604.26 MB)
telemt_user_octets_to_client{user="hello"} 13510601112 (12.58 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 2574.7 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18736
telemt_connections_bad_total 2820
telemt_handshake_timeouts_total 1400
telemt_upstream_connect_attempt_total 1077
telemt_upstream_connect_success_total 1067
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 613
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 575
telemt_me_idle_close_by_peer_total 575
telemt_me_route_drop_no_conn_total 3684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13645
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 13941
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 1163425107 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 3680680776 (3.43 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 2574.9 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27366
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 1469
telemt_upstream_connect_attempt_total 484
telemt_upstream_connect_success_total 479
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 325
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 5572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_restored_same_endpoint_total 306
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 24913
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 452287868 (431.34 MB)
telemt_user_octets_to_client{user="hello"} 6078790964 (5.66 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 2574.7 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18067
telemt_connections_bad_total 2189
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 753
telemt_upstream_connect_success_total 716
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 579
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 540
telemt_me_idle_close_by_peer_total 540
telemt_me_route_drop_no_conn_total 3463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14857
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 14857
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 109965944 (104.87 MB)
telemt_user_octets_to_client{user="hello"} 4352057924 (4.05 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 2575.4 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14778
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 432
telemt_upstream_connect_success_total 428
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 278
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 3254
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 283
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 13887
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 107550816 (102.57 MB)
telemt_user_octets_to_client{user="hello"} 7656983756 (7.13 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 35
```