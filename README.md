# Server Metrics 2026-03-12 23:00:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61305.2 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1937035
telemt_connections_bad_total 26067
telemt_handshake_timeouts_total 21134
telemt_upstream_connect_attempt_total 12125
telemt_upstream_connect_success_total 12056
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 608
telemt_me_reconnect_attempts_total 17809
telemt_me_reconnect_success_total 8953
telemt_me_reader_eof_total 9664
telemt_me_idle_close_by_peer_total 9663
telemt_me_route_drop_no_conn_total 756099
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1801686
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8524
telemt_desync_full_logged_total 2223
telemt_desync_suppressed_total 6301
telemt_desync_frames_bucket_total{bucket="1_2"} 2246
telemt_desync_frames_bucket_total{bucket="3_10"} 3065
telemt_desync_frames_bucket_total{bucket="gt_10"} 3213
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9355
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8940
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1801157
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 27163639120 (25.30 GB)
telemt_user_octets_to_client{user="hello"} 640962032100 (596.94 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90925.5 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801834
telemt_connections_bad_total 11708
telemt_handshake_timeouts_total 31410
telemt_upstream_connect_attempt_total 22972
telemt_upstream_connect_success_total 22942
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3417
telemt_me_reconnect_attempts_total 16868
telemt_me_reconnect_success_total 16773
telemt_me_reader_eof_total 17849
telemt_me_idle_close_by_peer_total 17849
telemt_me_route_drop_no_conn_total 259122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724694
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3006
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 2071
telemt_desync_frames_bucket_total{bucket="1_2"} 1191
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16943
telemt_me_writer_restored_same_endpoint_total 16764
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 726574
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 12093470456 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 281051235127 (261.75 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90925.4 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1669269
telemt_connections_bad_total 8043
telemt_handshake_timeouts_total 113313
telemt_upstream_connect_attempt_total 21101
telemt_upstream_connect_success_total 21095
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1224
telemt_me_reconnect_attempts_total 17466
telemt_me_reconnect_success_total 16215
telemt_me_reader_eof_total 17143
telemt_me_idle_close_by_peer_total 17142
telemt_me_route_drop_no_conn_total 548067
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1302353
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4969
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16373
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16174
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 1301959
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 19766425580 (18.41 GB)
telemt_user_octets_to_client{user="hello"} 482809763069 (449.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90925.7 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028252
telemt_connections_bad_total 13009
telemt_handshake_timeouts_total 71489
telemt_upstream_connect_attempt_total 23304
telemt_upstream_connect_success_total 23210
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 23304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1696
telemt_me_reconnect_attempts_total 26427
telemt_me_reconnect_success_total 18695
telemt_me_reader_eof_total 19966
telemt_me_idle_close_by_peer_total 19966
telemt_me_route_drop_no_conn_total 368151
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896930
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19084
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18674
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 896276
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 14247262104 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 358840328148 (334.20 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90925.6 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150032
telemt_connections_bad_total 12541
telemt_handshake_timeouts_total 9236
telemt_upstream_connect_attempt_total 27727
telemt_upstream_connect_success_total 27382
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 27727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 1449
telemt_me_reconnect_attempts_total 33895
telemt_me_reconnect_success_total 22855
telemt_me_reader_eof_total 24033
telemt_me_idle_close_by_peer_total 24033
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 429242
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1059476
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3996
telemt_desync_full_logged_total 1391
telemt_desync_suppressed_total 2605
telemt_desync_frames_bucket_total{bucket="1_2"} 1164
telemt_desync_frames_bucket_total{bucket="3_10"} 1324
telemt_desync_frames_bucket_total{bucket="gt_10"} 1508
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 23465
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22811
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 1059334
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 13497422580 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 374757415476 (349.02 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 43
```