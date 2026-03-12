# Server Metrics 2026-03-12 22:55:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60999.0 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1934158
telemt_connections_bad_total 26065
telemt_handshake_timeouts_total 21121
telemt_upstream_connect_attempt_total 12044
telemt_upstream_connect_success_total 11976
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 607
telemt_me_reconnect_attempts_total 17772
telemt_me_reconnect_success_total 8916
telemt_me_reader_eof_total 9627
telemt_me_idle_close_by_peer_total 9626
telemt_me_route_drop_no_conn_total 755119
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1799144
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8521
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 6299
telemt_desync_frames_bucket_total{bucket="1_2"} 2243
telemt_desync_frames_bucket_total{bucket="3_10"} 3065
telemt_desync_frames_bucket_total{bucket="gt_10"} 3213
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9318
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8903
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1798615
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 27070577560 (25.21 GB)
telemt_user_octets_to_client{user="hello"} 640371903480 (596.39 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90619.3 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800736
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31392
telemt_upstream_connect_attempt_total 22927
telemt_upstream_connect_success_total 22898
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3416
telemt_me_reconnect_attempts_total 16826
telemt_me_reconnect_success_total 16731
telemt_me_reader_eof_total 17806
telemt_me_idle_close_by_peer_total 17806
telemt_me_route_drop_no_conn_total 258967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16900
telemt_me_writer_restored_same_endpoint_total 16722
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 725514
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 12087795620 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 279742906907 (260.53 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90619.2 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1666705
telemt_connections_bad_total 8040
telemt_handshake_timeouts_total 113303
telemt_upstream_connect_attempt_total 21068
telemt_upstream_connect_success_total 21062
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1223
telemt_me_reconnect_attempts_total 17436
telemt_me_reconnect_success_total 16185
telemt_me_reader_eof_total 17111
telemt_me_idle_close_by_peer_total 17110
telemt_me_route_drop_no_conn_total 547026
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299888
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
telemt_me_writer_removed_unexpected_total 16341
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16144
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 1299494
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 19760022956 (18.40 GB)
telemt_user_octets_to_client{user="hello"} 481594741261 (448.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90619.6 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026456
telemt_connections_bad_total 13005
telemt_handshake_timeouts_total 71480
telemt_upstream_connect_attempt_total 23233
telemt_upstream_connect_success_total 23139
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 23233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 26356
telemt_me_reconnect_success_total 18624
telemt_me_reader_eof_total 19895
telemt_me_idle_close_by_peer_total 19895
telemt_me_route_drop_no_conn_total 367621
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895159
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
telemt_me_writer_removed_unexpected_total 19013
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18603
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 894505
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 14242188004 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 358178871364 (333.58 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90619.4 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148199
telemt_connections_bad_total 12537
telemt_handshake_timeouts_total 9229
telemt_upstream_connect_attempt_total 27685
telemt_upstream_connect_success_total 27340
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 27685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 1449
telemt_me_reconnect_attempts_total 33853
telemt_me_reconnect_success_total 22813
telemt_me_reader_eof_total 23991
telemt_me_idle_close_by_peer_total 23991
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 428782
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1057690
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3987
telemt_desync_full_logged_total 1386
telemt_desync_suppressed_total 2601
telemt_desync_frames_bucket_total{bucket="1_2"} 1161
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 1506
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 23423
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22769
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 1057549
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 13490451232 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 374341111104 (348.63 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 36
```