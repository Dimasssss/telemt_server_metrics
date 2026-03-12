# Server Metrics 2026-03-12 00:12:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8873.3 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78603
telemt_connections_bad_total 1321
telemt_handshake_timeouts_total 232
telemt_upstream_connect_attempt_total 2112
telemt_upstream_connect_success_total 2112
telemt_upstream_connect_attempts_per_request{bucket="1"} 2112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 1654
telemt_me_reconnect_success_total 1648
telemt_me_reader_eof_total 1725
telemt_me_idle_close_by_peer_total 1725
telemt_me_route_drop_no_conn_total 29136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73971
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1670
telemt_me_writer_restored_same_endpoint_total 1632
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 73922
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 553173244 (527.55 MB)
telemt_user_octets_to_client{user="hello"} 22707779692 (21.15 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8873.9 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27983
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 2668
telemt_upstream_connect_success_total 2665
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 2025
telemt_me_reconnect_success_total 2005
telemt_me_reader_eof_total 2103
telemt_me_idle_close_by_peer_total 2103
telemt_me_route_drop_no_conn_total 7310
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2018
telemt_me_writer_restored_same_endpoint_total 1996
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 26608
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 566912323 (540.65 MB)
telemt_user_octets_to_client{user="hello"} 10421473702 (9.71 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8873.8 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80233
telemt_connections_bad_total 553
telemt_handshake_timeouts_total 6201
telemt_upstream_connect_attempt_total 3055
telemt_upstream_connect_success_total 3053
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2271
telemt_me_reconnect_success_total 2225
telemt_me_reader_eof_total 2236
telemt_me_idle_close_by_peer_total 2236
telemt_me_route_drop_no_conn_total 12882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43460
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2159
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2184
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 43805
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 489758040 (467.07 MB)
telemt_user_octets_to_client{user="hello"} 20445565213 (19.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8874.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41518
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 610
telemt_upstream_connect_attempt_total 2639
telemt_upstream_connect_success_total 2625
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 2164
telemt_me_reconnect_success_total 2155
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2238
telemt_me_route_drop_no_conn_total 13876
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40241
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2168
telemt_me_writer_restored_same_endpoint_total 2134
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 40237
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 193264068 (184.31 MB)
telemt_user_octets_to_client{user="hello"} 11567524424 (10.77 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8873.8 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54071
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 510
telemt_upstream_connect_attempt_total 4009
telemt_upstream_connect_success_total 3974
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 4984
telemt_me_reconnect_success_total 3495
telemt_me_reader_eof_total 3569
telemt_me_idle_close_by_peer_total 3569
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 12988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50518
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 89
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3559
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3489
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 50500
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 254197616 (242.42 MB)
telemt_user_octets_to_client{user="hello"} 12912702924 (12.03 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```