# Server Metrics 2026-03-12 07:52:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6800.8 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201025
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 1382
telemt_upstream_connect_success_total 1373
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 605
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 1002
telemt_me_reconnect_success_total 997
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 67342
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 955
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 713
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 998
telemt_me_writer_restored_same_endpoint_total 984
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 194072
telemt_user_connections_current{user="hello"} 1143
telemt_user_octets_from_client{user="hello"} 3013807352 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 56864607204 (52.96 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36421.2 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182938
telemt_connections_bad_total 2542
telemt_handshake_timeouts_total 7001
telemt_upstream_connect_attempt_total 9446
telemt_upstream_connect_success_total 9440
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 588
telemt_me_reconnect_attempts_total 7464
telemt_me_reconnect_success_total 7424
telemt_me_reader_eof_total 7880
telemt_me_idle_close_by_peer_total 7880
telemt_me_route_drop_no_conn_total 52815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158630
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7483
telemt_me_writer_restored_same_endpoint_total 7415
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 158923
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 2380451915 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 63725217018 (59.35 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36421.0 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552205
telemt_connections_bad_total 2556
telemt_handshake_timeouts_total 41179
telemt_upstream_connect_attempt_total 9649
telemt_upstream_connect_success_total 9643
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 504
telemt_me_reconnect_attempts_total 7523
telemt_me_reconnect_success_total 7453
telemt_me_reader_eof_total 7817
telemt_me_idle_close_by_peer_total 7817
telemt_me_route_drop_no_conn_total 102908
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299785
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1356
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 938
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 714
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7445
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7412
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 300064
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 3222438728 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 107533321485 (100.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36421.4 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254083
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 15742
telemt_upstream_connect_attempt_total 10188
telemt_upstream_connect_success_total 10148
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 737
telemt_me_reconnect_attempts_total 8346
telemt_me_reconnect_success_total 8317
telemt_me_reader_eof_total 8825
telemt_me_idle_close_by_peer_total 8825
telemt_me_route_drop_no_conn_total 84064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 360
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8369
telemt_me_writer_restored_same_endpoint_total 8296
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 210472
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 2442742828 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 70666928632 (65.81 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36421.4 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278289
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 2241
telemt_upstream_connect_attempt_total 12232
telemt_upstream_connect_success_total 12086
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 12232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 547
telemt_me_reconnect_attempts_total 11757
telemt_me_reconnect_success_total 10245
telemt_me_reader_eof_total 10655
telemt_me_idle_close_by_peer_total 10655
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 86782
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261489
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1053
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 700
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10387
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10224
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 261439
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 2572429808 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 62670757472 (58.37 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 102
```