# Server Metrics 2026-03-12 04:43:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25093.0 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242706
telemt_connections_bad_total 1389
telemt_handshake_timeouts_total 3814
telemt_upstream_connect_attempt_total 5689
telemt_upstream_connect_success_total 5689
telemt_upstream_connect_attempts_per_request{bucket="1"} 5689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 4454
telemt_me_reconnect_success_total 4437
telemt_me_reader_eof_total 4689
telemt_me_idle_close_by_peer_total 4689
telemt_me_route_drop_no_conn_total 86737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231089
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4483
telemt_me_writer_restored_same_endpoint_total 4421
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 230830
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 2289771872 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 71623069464 (66.70 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25093.8 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81602
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 1596
telemt_upstream_connect_attempt_total 6922
telemt_upstream_connect_success_total 6918
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 5502
telemt_me_reconnect_success_total 5469
telemt_me_reader_eof_total 5809
telemt_me_idle_close_by_peer_total 5809
telemt_me_route_drop_no_conn_total 23731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 218
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5514
telemt_me_writer_restored_same_endpoint_total 5460
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 73886
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 1177323283 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 26344790238 (24.54 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25093.6 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363103
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 23346
telemt_upstream_connect_attempt_total 7237
telemt_upstream_connect_success_total 7235
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 5674
telemt_me_reconnect_success_total 5614
telemt_me_reader_eof_total 5862
telemt_me_idle_close_by_peer_total 5862
telemt_me_route_drop_no_conn_total 45044
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137738
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5584
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5573
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 138054
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 1359440052 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 42595861145 (39.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25094.1 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120334
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 7673
telemt_upstream_connect_attempt_total 7451
telemt_upstream_connect_success_total 7418
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 6179
telemt_me_reconnect_success_total 6157
telemt_me_reader_eof_total 6532
telemt_me_idle_close_by_peer_total 6532
telemt_me_route_drop_no_conn_total 40363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109407
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6196
telemt_me_writer_restored_same_endpoint_total 6136
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 109389
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 860685876 (820.81 MB)
telemt_user_octets_to_client{user="hello"} 31617465196 (29.45 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25093.9 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140585
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 820
telemt_upstream_connect_attempt_total 9308
telemt_upstream_connect_success_total 9208
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 9308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 9439
telemt_me_reconnect_success_total 7936
telemt_me_reader_eof_total 8241
telemt_me_idle_close_by_peer_total 8241
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 39191
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134451
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 505
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 8048
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7919
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 134430
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 919116668 (876.54 MB)
telemt_user_octets_to_client{user="hello"} 29526870684 (27.50 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 58
```