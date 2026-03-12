# Server Metrics 2026-03-12 21:38:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56401.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1879571
telemt_connections_bad_total 26052
telemt_handshake_timeouts_total 20599
telemt_upstream_connect_attempt_total 10983
telemt_upstream_connect_success_total 10921
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 592
telemt_me_reconnect_attempts_total 16933
telemt_me_reconnect_success_total 8080
telemt_me_reader_eof_total 8741
telemt_me_idle_close_by_peer_total 8740
telemt_me_route_drop_no_conn_total 735868
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1749352
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8427
telemt_desync_full_logged_total 2187
telemt_desync_suppressed_total 6240
telemt_desync_frames_bucket_total{bucket="1_2"} 2214
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 3181
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8474
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8067
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 1748832
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 26642468360 (24.81 GB)
telemt_user_octets_to_client{user="hello"} 617295648264 (574.90 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86022.5 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782301
telemt_connections_bad_total 11666
telemt_handshake_timeouts_total 31042
telemt_upstream_connect_attempt_total 21726
telemt_upstream_connect_success_total 21697
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3399
telemt_me_reconnect_attempts_total 15842
telemt_me_reconnect_success_total 15749
telemt_me_reader_eof_total 16751
telemt_me_idle_close_by_peer_total 16751
telemt_me_route_drop_no_conn_total 252895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705946
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2979
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 15909
telemt_me_writer_restored_same_endpoint_total 15740
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 707823
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 11981874988 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 271621340563 (252.97 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86022.3 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1620852
telemt_connections_bad_total 7733
telemt_handshake_timeouts_total 112380
telemt_upstream_connect_attempt_total 20128
telemt_upstream_connect_success_total 20122
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1213
telemt_me_reconnect_attempts_total 16711
telemt_me_reconnect_success_total 15463
telemt_me_reader_eof_total 16333
telemt_me_idle_close_by_peer_total 16332
telemt_me_route_drop_no_conn_total 535144
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1256127
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4933
telemt_desync_full_logged_total 1515
telemt_desync_suppressed_total 3418
telemt_desync_frames_bucket_total{bucket="1_2"} 786
telemt_desync_frames_bucket_total{bucket="3_10"} 1782
telemt_desync_frames_bucket_total{bucket="gt_10"} 2365
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15609
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15422
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1255733
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 19582348152 (18.24 GB)
telemt_user_octets_to_client{user="hello"} 466568573289 (434.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86022.8 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998022
telemt_connections_bad_total 12985
telemt_handshake_timeouts_total 71090
telemt_upstream_connect_attempt_total 21927
telemt_upstream_connect_success_total 21838
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 21927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25270
telemt_me_reconnect_success_total 17542
telemt_me_reader_eof_total 18736
telemt_me_idle_close_by_peer_total 18736
telemt_me_route_drop_no_conn_total 357475
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869019
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 17923
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17521
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 868368
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 13755464104 (12.81 GB)
telemt_user_octets_to_client{user="hello"} 349502426592 (325.50 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86022.6 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117617
telemt_connections_bad_total 12521
telemt_handshake_timeouts_total 9057
telemt_upstream_connect_attempt_total 26506
telemt_upstream_connect_success_total 26181
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 26506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1435
telemt_me_reconnect_attempts_total 32909
telemt_me_reconnect_success_total 21871
telemt_me_reader_eof_total 22990
telemt_me_idle_close_by_peer_total 22990
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 419181
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027717
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3877
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 2527
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 22465
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21827
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1027577
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 12731538516 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 362391239424 (337.50 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 50
```