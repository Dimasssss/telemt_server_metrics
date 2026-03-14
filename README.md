# Server Metrics 2026-03-14 18:06:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 17301.2 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699686
telemt_connections_bad_total 38232
telemt_handshake_timeouts_total 9305
telemt_upstream_connect_attempt_total 3448
telemt_upstream_connect_success_total 3433
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3297
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2617
telemt_me_idle_close_by_peer_total 2617
telemt_me_route_drop_no_conn_total 267201
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620680
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2148
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1534
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2560
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2487
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 620613
telemt_user_connections_current{user="hello"} 1861
telemt_user_octets_from_client{user="hello"} 10855186760 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 198859432316 (185.20 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 17306.7 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274982
telemt_connections_bad_total 22644
telemt_handshake_timeouts_total 8747
telemt_upstream_connect_attempt_total 3609
telemt_upstream_connect_success_total 3565
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 3420
telemt_me_reconnect_success_total 2629
telemt_me_reader_eof_total 2754
telemt_me_idle_close_by_peer_total 2754
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 85376
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226163
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 890
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2712
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2614
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 226104
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 3176379168 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 84834501560 (79.01 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 17169.6 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581475
telemt_connections_bad_total 2022
telemt_handshake_timeouts_total 117363
telemt_upstream_connect_attempt_total 3413
telemt_upstream_connect_success_total 3401
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 6404
telemt_me_reconnect_success_total 2501
telemt_me_reader_eof_total 2690
telemt_me_idle_close_by_peer_total 2690
telemt_me_route_drop_no_conn_total 141473
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390944
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 424
telemt_desync_suppressed_total 791
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2646
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2468
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 390836
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 5769214388 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 139443999272 (129.87 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 17024.0 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313249
telemt_connections_bad_total 72342
telemt_handshake_timeouts_total 40978
telemt_upstream_connect_attempt_total 4087
telemt_upstream_connect_success_total 4086
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 4129
telemt_me_reconnect_success_total 3214
telemt_me_reader_eof_total 3354
telemt_me_idle_close_by_peer_total 3354
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 69729
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3272
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3207
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 195337
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 2945182408 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 61067947952 (56.87 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 17319.6 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267554
telemt_connections_bad_total 1105
telemt_handshake_timeouts_total 3229
telemt_upstream_connect_attempt_total 3656
telemt_upstream_connect_success_total 3581
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 3656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 2808
telemt_me_idle_close_by_peer_total 2808
telemt_me_route_drop_no_conn_total 85264
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 615
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2740
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2647
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 247038
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 3873134940 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 102731409416 (95.68 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 100
```