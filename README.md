# Server Metrics 2026-03-13 10:27:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102557.4 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2971415
telemt_connections_bad_total 36442
telemt_handshake_timeouts_total 53949
telemt_upstream_connect_attempt_total 20159
telemt_upstream_connect_success_total 20050
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1445
telemt_me_reconnect_attempts_total 25036
telemt_me_reconnect_success_total 14967
telemt_me_reader_eof_total 16118
telemt_me_idle_close_by_peer_total 16117
telemt_me_route_drop_no_conn_total 1096621
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2710076
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11837
telemt_desync_full_logged_total 3051
telemt_desync_suppressed_total 8786
telemt_desync_frames_bucket_total{bucket="1_2"} 3026
telemt_desync_frames_bucket_total{bucket="3_10"} 4447
telemt_desync_frames_bucket_total{bucket="gt_10"} 4364
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15489
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14954
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2710016
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 37246359664 (34.69 GB)
telemt_user_octets_to_client{user="hello"} 879310010136 (818.92 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2221.1 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19465
telemt_connections_bad_total 1809
telemt_handshake_timeouts_total 342
telemt_upstream_connect_attempt_total 547
telemt_upstream_connect_success_total 479
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 387
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 6315
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16860
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_restored_same_endpoint_total 314
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 16861
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 242488804 (231.26 MB)
telemt_user_octets_to_client{user="hello"} 3433277356 (3.20 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 132178.0 (36h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2302564
telemt_connections_bad_total 25093
telemt_handshake_timeouts_total 156968
telemt_upstream_connect_attempt_total 30158
telemt_upstream_connect_success_total 30148
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1879
telemt_me_reconnect_attempts_total 24523
telemt_me_reconnect_success_total 23233
telemt_me_reader_eof_total 24613
telemt_me_idle_close_by_peer_total 24612
telemt_me_route_drop_no_conn_total 754134
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1847772
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6070
telemt_desync_full_logged_total 1941
telemt_desync_suppressed_total 4129
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 2209
telemt_desync_frames_bucket_total{bucket="gt_10"} 2872
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 23467
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23192
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1847213
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 31865992388 (29.68 GB)
telemt_user_octets_to_client{user="hello"} 665909668165 (620.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 132178.2 (36h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1454364
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 90309
telemt_upstream_connect_attempt_total 43160
telemt_upstream_connect_success_total 40850
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 42886
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_timeout_total 11507
telemt_me_reconnect_attempts_total 37381
telemt_me_reconnect_success_total 28430
telemt_me_reader_eof_total 30605
telemt_me_idle_close_by_peer_total 30598
telemt_me_route_drop_no_conn_total 514760
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1216656
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 28916
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28406
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1221394
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 18486659537 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 485272964902 (451.95 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1614.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12364
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 434
telemt_upstream_connect_success_total 429
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 318
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 3398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11591
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 11591
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 153397184 (146.29 MB)
telemt_user_octets_to_client{user="hello"} 6186964252 (5.76 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 110
```