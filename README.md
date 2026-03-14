# Server Metrics 2026-03-14 17:45:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 16076.7 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650769
telemt_connections_bad_total 36819
telemt_handshake_timeouts_total 8672
telemt_upstream_connect_attempt_total 3201
telemt_upstream_connect_success_total 3187
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3137
telemt_me_reconnect_success_total 2337
telemt_me_reader_eof_total 2439
telemt_me_idle_close_by_peer_total 2439
telemt_me_route_drop_no_conn_total 247227
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575768
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2000
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 787
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2397
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2328
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 575706
telemt_user_connections_current{user="hello"} 1771
telemt_user_octets_from_client{user="hello"} 10295781256 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 182632823380 (170.09 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 16082.0 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257202
telemt_connections_bad_total 22594
telemt_handshake_timeouts_total 8283
telemt_upstream_connect_attempt_total 3345
telemt_upstream_connect_success_total 3307
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 303
telemt_me_reconnect_attempts_total 3247
telemt_me_reconnect_success_total 2459
telemt_me_reader_eof_total 2566
telemt_me_idle_close_by_peer_total 2566
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 79934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209513
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2539
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2444
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 209454
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 3010120984 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 80054061008 (74.56 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 15945.0 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542986
telemt_connections_bad_total 1973
telemt_handshake_timeouts_total 109274
telemt_upstream_connect_attempt_total 3210
telemt_upstream_connect_success_total 3201
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 6269
telemt_me_reconnect_success_total 2367
telemt_me_reader_eof_total 2548
telemt_me_idle_close_by_peer_total 2548
telemt_me_route_drop_no_conn_total 131909
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363898
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1117
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 737
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2508
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2334
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 363795
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 5468616388 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 130973552044 (121.98 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 15799.5 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288288
telemt_connections_bad_total 62606
telemt_handshake_timeouts_total 40503
telemt_upstream_connect_attempt_total 3856
telemt_upstream_connect_success_total 3855
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3941
telemt_me_reconnect_success_total 3027
telemt_me_reader_eof_total 3155
telemt_me_idle_close_by_peer_total 3155
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 64593
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180935
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 353
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3085
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3020
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 180890
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 2788196972 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 57682653688 (53.72 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 16094.9 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250638
telemt_connections_bad_total 955
telemt_handshake_timeouts_total 3065
telemt_upstream_connect_attempt_total 3425
telemt_upstream_connect_success_total 3359
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3196
telemt_me_reconnect_success_total 2530
telemt_me_reader_eof_total 2659
telemt_me_idle_close_by_peer_total 2659
telemt_me_route_drop_no_conn_total 80636
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231149
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2601
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 231160
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 3505058444 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 90428326520 (84.22 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 107
```