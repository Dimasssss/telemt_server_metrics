# Server Metrics 2026-03-13 16:42:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 125027.6 (34h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3957179
telemt_connections_bad_total 37509
telemt_handshake_timeouts_total 94432
telemt_upstream_connect_attempt_total 24224
telemt_upstream_connect_success_total 24086
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 24224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2263
telemt_me_reconnect_attempts_total 27981
telemt_me_reconnect_success_total 17886
telemt_me_reader_eof_total 19213
telemt_me_idle_close_by_peer_total 19212
telemt_me_route_drop_no_conn_total 1469094
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3618155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14297
telemt_desync_full_logged_total 3775
telemt_desync_suppressed_total 10522
telemt_desync_frames_bucket_total{bucket="1_2"} 3575
telemt_desync_frames_bucket_total{bucket="3_10"} 5410
telemt_desync_frames_bucket_total{bucket="gt_10"} 5312
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18447
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17873
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 3617960
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 51024847516 (47.52 GB)
telemt_user_octets_to_client{user="hello"} 1130471348340 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24691.6 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363984
telemt_connections_bad_total 25297
telemt_handshake_timeouts_total 10048
telemt_upstream_connect_attempt_total 5868
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 5868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 7843
telemt_me_reconnect_success_total 4490
telemt_me_reader_eof_total 4773
telemt_me_idle_close_by_peer_total 4772
telemt_me_route_drop_no_conn_total 131269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319627
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1134
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 839
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4656
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4483
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 319658
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 3175981988 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 91653832596 (85.36 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 154648.2 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2909034
telemt_connections_bad_total 28302
telemt_handshake_timeouts_total 195533
telemt_upstream_connect_attempt_total 34560
telemt_upstream_connect_success_total 34550
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3318
telemt_me_reconnect_attempts_total 29084
telemt_me_reconnect_success_total 26532
telemt_me_reader_eof_total 28128
telemt_me_idle_close_by_peer_total 28127
telemt_me_route_drop_no_conn_total 987119
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2395761
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8395
telemt_desync_full_logged_total 2774
telemt_desync_suppressed_total 5621
telemt_desync_frames_bucket_total{bucket="1_2"} 1353
telemt_desync_frames_bucket_total{bucket="3_10"} 3067
telemt_desync_frames_bucket_total{bucket="gt_10"} 3975
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26843
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26491
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 2395129
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 39111074584 (36.43 GB)
telemt_user_octets_to_client{user="hello"} 833182070493 (775.96 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 154648.8 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1874767
telemt_connections_bad_total 18167
telemt_handshake_timeouts_total 171486
telemt_upstream_connect_attempt_total 48406
telemt_upstream_connect_success_total 46070
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48132
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11914
telemt_me_reconnect_attempts_total 41509
telemt_me_reconnect_success_total 32535
telemt_me_reader_eof_total 34945
telemt_me_idle_close_by_peer_total 34938
telemt_me_route_drop_no_conn_total 665128
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544238
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3080
telemt_desync_full_logged_total 1000
telemt_desync_suppressed_total 2080
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 33071
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32511
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 1548936
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 23943941881 (22.30 GB)
telemt_user_octets_to_client{user="hello"} 588051082330 (547.67 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24084.1 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391507
telemt_connections_bad_total 4203
telemt_handshake_timeouts_total 3595
telemt_upstream_connect_attempt_total 5440
telemt_upstream_connect_success_total 5281
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 5440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 15752
telemt_me_reconnect_success_total 4055
telemt_me_reader_eof_total 4498
telemt_me_idle_close_by_peer_total 4498
telemt_me_route_drop_no_conn_total 152607
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365854
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1208
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4449
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4051
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 365830
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 4252846532 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 117170259716 (109.12 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 108
```