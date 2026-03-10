# Server Metrics 2026-03-10 22:13:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28005.2 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726110
telemt_connections_bad_total 8313
telemt_handshake_timeouts_total 8288
telemt_upstream_connect_attempt_total 6032
telemt_upstream_connect_success_total 6023
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 16186
telemt_me_reconnect_success_total 4527
telemt_me_reader_eof_total 4996
telemt_me_idle_close_by_peer_total 4996
telemt_me_route_drop_no_conn_total 302430
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686843
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3430
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2472
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1159
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4927
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4521
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 686648
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 9935877732 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 207821997028 (193.55 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28061.8 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315808
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 17546
telemt_upstream_connect_attempt_total 12535
telemt_upstream_connect_success_total 9670
telemt_upstream_connect_fail_total 2865
telemt_upstream_connect_attempts_per_request{bucket="1"} 12535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2865
telemt_me_keepalive_timeout_total 1375
telemt_me_reconnect_attempts_total 6062
telemt_me_reconnect_success_total 5256
telemt_me_reader_eof_total 5517
telemt_me_idle_close_by_peer_total 5515
telemt_me_route_drop_no_conn_total 165496
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266001
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1588
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 1147
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5341
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5235
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 268274
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2646144130 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 62901862924 (58.58 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28061.6 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520511
telemt_connections_bad_total 3119
telemt_handshake_timeouts_total 33669
telemt_upstream_connect_attempt_total 7827
telemt_upstream_connect_success_total 7711
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 16225
telemt_me_reconnect_success_total 5170
telemt_me_reader_eof_total 5693
telemt_me_idle_close_by_peer_total 5693
telemt_me_route_drop_no_conn_total 180696
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1452
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5597
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5159
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 456382
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 6583287797 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 147298779933 (137.18 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28062.1 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362706
telemt_connections_bad_total 27085
telemt_handshake_timeouts_total 32304
telemt_upstream_connect_attempt_total 7779
telemt_upstream_connect_success_total 7779
telemt_upstream_connect_attempts_per_request{bucket="1"} 7779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 7337
telemt_me_reconnect_success_total 6313
telemt_me_reader_eof_total 6633
telemt_me_idle_close_by_peer_total 6633
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 117012
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290500
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6413
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6299
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 290178
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 4028645108 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 85935521352 (80.03 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28061.7 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382956
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 2515
telemt_upstream_connect_attempt_total 8775
telemt_upstream_connect_success_total 8740
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 10999
telemt_me_reconnect_success_total 7242
telemt_me_reader_eof_total 7585
telemt_me_idle_close_by_peer_total 7585
telemt_me_route_drop_no_conn_total 134613
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357004
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2111
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 901
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 7462
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7242
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 356844
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 6405843260 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 135784761192 (126.46 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 41
```