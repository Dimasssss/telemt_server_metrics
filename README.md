# Server Metrics 2026-03-12 21:08:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54566.6 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1844955
telemt_connections_bad_total 22351
telemt_handshake_timeouts_total 20261
telemt_upstream_connect_attempt_total 10620
telemt_upstream_connect_success_total 10559
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 16657
telemt_me_reconnect_success_total 7805
telemt_me_reader_eof_total 8443
telemt_me_idle_close_by_peer_total 8442
telemt_me_route_drop_no_conn_total 724499
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8360
telemt_desync_full_logged_total 2160
telemt_desync_suppressed_total 6200
telemt_desync_frames_bucket_total{bucket="1_2"} 2194
telemt_desync_frames_bucket_total{bucket="3_10"} 3018
telemt_desync_frames_bucket_total{bucket="gt_10"} 3148
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8194
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7792
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 1720048
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 26335296844 (24.53 GB)
telemt_user_octets_to_client{user="hello"} 605567130248 (563.98 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84187.3 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772011
telemt_connections_bad_total 11584
telemt_handshake_timeouts_total 30578
telemt_upstream_connect_attempt_total 21288
telemt_upstream_connect_success_total 21259
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3392
telemt_me_reconnect_attempts_total 15490
telemt_me_reconnect_success_total 15398
telemt_me_reader_eof_total 16377
telemt_me_idle_close_by_peer_total 16377
telemt_me_route_drop_no_conn_total 249506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696446
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2965
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 2052
telemt_desync_frames_bucket_total{bucket="1_2"} 1161
telemt_desync_frames_bucket_total{bucket="3_10"} 977
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15555
telemt_me_writer_restored_same_endpoint_total 15389
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 698324
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 11871944188 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 268830225495 (250.37 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84187.0 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596558
telemt_connections_bad_total 7549
telemt_handshake_timeouts_total 110190
telemt_upstream_connect_attempt_total 19734
telemt_upstream_connect_success_total 19728
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1210
telemt_me_reconnect_attempts_total 16404
telemt_me_reconnect_success_total 15157
telemt_me_reader_eof_total 16003
telemt_me_idle_close_by_peer_total 16002
telemt_me_route_drop_no_conn_total 527776
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1234523
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4863
telemt_desync_full_logged_total 1495
telemt_desync_suppressed_total 3368
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 1756
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15300
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15116
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1234130
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 19363254252 (18.03 GB)
telemt_user_octets_to_client{user="hello"} 459244189061 (427.70 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84187.5 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982249
telemt_connections_bad_total 12974
telemt_handshake_timeouts_total 70908
telemt_upstream_connect_attempt_total 21468
telemt_upstream_connect_success_total 21380
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1674
telemt_me_reconnect_attempts_total 24899
telemt_me_reconnect_success_total 17172
telemt_me_reader_eof_total 18342
telemt_me_idle_close_by_peer_total 18342
telemt_me_route_drop_no_conn_total 351352
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854496
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1836
telemt_desync_full_logged_total 609
telemt_desync_suppressed_total 1227
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17551
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17151
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 853846
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 13389816084 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 346730850940 (322.92 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84187.4 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102035
telemt_connections_bad_total 12513
telemt_handshake_timeouts_total 9024
telemt_upstream_connect_attempt_total 26049
telemt_upstream_connect_success_total 25728
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 26049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 32542
telemt_me_reconnect_success_total 21504
telemt_me_reader_eof_total 22593
telemt_me_idle_close_by_peer_total 22593
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 412904
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1012485
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3845
telemt_desync_full_logged_total 1337
telemt_desync_suppressed_total 2508
telemt_desync_frames_bucket_total{bucket="1_2"} 1121
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 22095
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21460
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 1012345
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 12526002888 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 357517303344 (332.96 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 58
```