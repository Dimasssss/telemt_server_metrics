# Server Metrics 2026-03-12 05:39:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28460.6 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314655
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 5630
telemt_upstream_connect_attempt_total 6331
telemt_upstream_connect_success_total 6331
telemt_upstream_connect_attempts_per_request{bucket="1"} 6331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4924
telemt_me_reconnect_success_total 4906
telemt_me_reader_eof_total 5192
telemt_me_idle_close_by_peer_total 5192
telemt_me_route_drop_no_conn_total 111887
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299476
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 778
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4958
telemt_me_writer_restored_same_endpoint_total 4890
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 299186
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 2901438228 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 92127972932 (85.80 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28461.4 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101982
telemt_connections_bad_total 728
telemt_handshake_timeouts_total 2274
telemt_upstream_connect_attempt_total 7684
telemt_upstream_connect_success_total 7679
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 6092
telemt_me_reconnect_success_total 6055
telemt_me_reader_eof_total 6441
telemt_me_idle_close_by_peer_total 6441
telemt_me_route_drop_no_conn_total 30369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6107
telemt_me_writer_restored_same_endpoint_total 6046
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 92667
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 1458207987 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 38377687210 (35.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28461.3 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410793
telemt_connections_bad_total 2082
telemt_handshake_timeouts_total 28558
telemt_upstream_connect_attempt_total 7970
telemt_upstream_connect_success_total 7968
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 6235
telemt_me_reconnect_success_total 6173
telemt_me_reader_eof_total 6461
telemt_me_idle_close_by_peer_total 6461
telemt_me_route_drop_no_conn_total 57182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174046
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 679
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6149
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6132
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 174361
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 1827908240 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 53365335557 (49.70 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28461.7 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146819
telemt_connections_bad_total 1690
telemt_handshake_timeouts_total 10175
telemt_upstream_connect_attempt_total 8289
telemt_upstream_connect_success_total 8254
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 6842
telemt_me_reconnect_success_total 6819
telemt_me_reader_eof_total 7239
telemt_me_idle_close_by_peer_total 7239
telemt_me_route_drop_no_conn_total 49648
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 193
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6860
telemt_me_writer_restored_same_endpoint_total 6798
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 132686
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1276146156 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 39158949868 (36.47 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28461.5 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169259
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1057
telemt_upstream_connect_attempt_total 10238
telemt_upstream_connect_success_total 10126
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 10238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 10186
telemt_me_reconnect_success_total 8679
telemt_me_reader_eof_total 9036
telemt_me_idle_close_by_peer_total 9036
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 48759
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 604
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 8799
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8660
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 161782
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1434704196 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 36281728940 (33.79 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 77
```