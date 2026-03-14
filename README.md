# Server Metrics 2026-03-14 17:14:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 14235.5 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575369
telemt_connections_bad_total 31329
telemt_handshake_timeouts_total 7880
telemt_upstream_connect_attempt_total 2883
telemt_upstream_connect_success_total 2870
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2908
telemt_me_reconnect_success_total 2109
telemt_me_reader_eof_total 2205
telemt_me_idle_close_by_peer_total 2205
telemt_me_route_drop_no_conn_total 220338
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509971
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1800
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1282
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2167
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2100
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 509906
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 9201274480 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 157911552476 (147.07 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 14240.9 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231077
telemt_connections_bad_total 22252
telemt_handshake_timeouts_total 7049
telemt_upstream_connect_attempt_total 2994
telemt_upstream_connect_success_total 2959
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2984
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 2292
telemt_me_idle_close_by_peer_total 2292
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 71663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187198
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2277
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2183
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 187139
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 2753709684 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 73786548536 (68.72 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 14103.7 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477504
telemt_connections_bad_total 1937
telemt_handshake_timeouts_total 98515
telemt_upstream_connect_attempt_total 2896
telemt_upstream_connect_success_total 2887
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 6041
telemt_me_reconnect_success_total 2141
telemt_me_reader_eof_total 2306
telemt_me_idle_close_by_peer_total 2306
telemt_me_route_drop_no_conn_total 118954
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323112
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 934
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 617
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2276
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2108
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 323018
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 4788071204 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 117746536152 (109.66 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 13958.0 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251263
telemt_connections_bad_total 53296
telemt_handshake_timeouts_total 37522
telemt_upstream_connect_attempt_total 3487
telemt_upstream_connect_success_total 3486
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3659
telemt_me_reconnect_success_total 2746
telemt_me_reader_eof_total 2853
telemt_me_idle_close_by_peer_total 2853
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 56916
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156938
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2801
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2739
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 156896
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 2418167800 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 50671578044 (47.19 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 14253.8 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223333
telemt_connections_bad_total 857
telemt_handshake_timeouts_total 2870
telemt_upstream_connect_attempt_total 3138
telemt_upstream_connect_success_total 3075
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 2998
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2450
telemt_me_idle_close_by_peer_total 2450
telemt_me_route_drop_no_conn_total 73149
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205709
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2401
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2315
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 205725
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 3285867384 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 79626267004 (74.16 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 93
```