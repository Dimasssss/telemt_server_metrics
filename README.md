# Server Metrics 2026-03-11 22:05:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1222.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16026
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 239
telemt_upstream_connect_success_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 129
telemt_me_reader_eof_total 111
telemt_me_idle_close_by_peer_total 111
telemt_me_route_drop_no_conn_total 4641
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13957
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 131
telemt_me_writer_restored_same_endpoint_total 113
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 13955
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 78748708 (75.10 MB)
telemt_user_octets_to_client{user="hello"} 4538741484 (4.23 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 1223.6 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5447
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 306
telemt_upstream_connect_success_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 143
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 192
telemt_me_reconnect_success_total 189
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 1297
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5083
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_restored_same_endpoint_total 180
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 5083
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 46856076 (44.69 MB)
telemt_user_octets_to_client{user="hello"} 1003261920 (956.79 MB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 1223.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12275
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 1183
telemt_upstream_connect_attempt_total 911
telemt_upstream_connect_success_total 911
telemt_upstream_connect_attempts_per_request{bucket="1"} 911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 475
telemt_me_reconnect_success_total 440
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 2231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10257
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 352
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 10611
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 75391004 (71.90 MB)
telemt_user_octets_to_client{user="hello"} 2133133061 (1.99 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 1223.7 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7951
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 328
telemt_upstream_connect_success_total 324
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 212
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 179
telemt_me_idle_close_by_peer_total 179
telemt_me_route_drop_no_conn_total 1611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_restored_same_endpoint_total 188
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 7610
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 57694032 (55.02 MB)
telemt_user_octets_to_client{user="hello"} 3093789968 (2.88 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1223.5 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8812
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 324
telemt_upstream_connect_success_total 319
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 207
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 164
telemt_me_idle_close_by_peer_total 164
telemt_me_route_drop_no_conn_total 1795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 186
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 8177
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 93320148 (89.00 MB)
telemt_user_octets_to_client{user="hello"} 2715469624 (2.53 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 42
```