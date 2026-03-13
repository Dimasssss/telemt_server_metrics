# Server Metrics 2026-03-13 02:29:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73842.7 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2086618
telemt_connections_bad_total 27787
telemt_handshake_timeouts_total 22184
telemt_upstream_connect_attempt_total 14586
telemt_upstream_connect_success_total 14503
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1263
telemt_me_reconnect_attempts_total 19683
telemt_me_reconnect_success_total 10822
telemt_me_reader_eof_total 11693
telemt_me_idle_close_by_peer_total 11692
telemt_me_route_drop_no_conn_total 806006
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1927072
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8706
telemt_desync_full_logged_total 2268
telemt_desync_suppressed_total 6438
telemt_desync_frames_bucket_total{bucket="1_2"} 2297
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11252
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10809
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1926530
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 28092537012 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 670706010300 (624.64 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103463.2 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853368
telemt_connections_bad_total 11812
telemt_handshake_timeouts_total 32383
telemt_upstream_connect_attempt_total 26326
telemt_upstream_connect_success_total 26297
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3453
telemt_me_reconnect_attempts_total 19622
telemt_me_reconnect_success_total 19515
telemt_me_reader_eof_total 20783
telemt_me_idle_close_by_peer_total 20783
telemt_me_route_drop_no_conn_total 274535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 773972
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 19704
telemt_me_writer_restored_same_endpoint_total 19506
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 775875
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 12367062956 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 292488214867 (272.40 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103463.1 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1770126
telemt_connections_bad_total 9180
telemt_handshake_timeouts_total 118488
telemt_upstream_connect_attempt_total 24104
telemt_upstream_connect_success_total 24094
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1605
telemt_me_reconnect_attempts_total 19865
telemt_me_reconnect_success_total 18601
telemt_me_reader_eof_total 19695
telemt_me_idle_close_by_peer_total 19694
telemt_me_route_drop_no_conn_total 577480
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1393213
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5022
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3484
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 18776
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18560
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 1392808
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 20194493812 (18.81 GB)
telemt_user_octets_to_client{user="hello"} 502412437349 (467.91 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103463.4 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106105
telemt_connections_bad_total 13135
telemt_handshake_timeouts_total 73246
telemt_upstream_connect_attempt_total 36178
telemt_upstream_connect_success_total 33905
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 35904
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11362
telemt_me_reconnect_attempts_total 31823
telemt_me_reconnect_success_total 22899
telemt_me_reader_eof_total 24730
telemt_me_idle_close_by_peer_total 24723
telemt_me_route_drop_no_conn_total 392030
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948491
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23328
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22875
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 953665
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 14530497477 (13.53 GB)
telemt_user_octets_to_client{user="hello"} 374087749122 (348.40 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 103463.3 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1222238
telemt_connections_bad_total 12625
telemt_handshake_timeouts_total 9549
telemt_upstream_connect_attempt_total 32740
telemt_upstream_connect_success_total 32339
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 32740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 1891
telemt_me_reconnect_attempts_total 40928
telemt_me_reconnect_success_total 27198
telemt_me_reader_eof_total 28591
telemt_me_idle_close_by_peer_total 28591
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 457027
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130061
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4199
telemt_desync_full_logged_total 1491
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1259
telemt_desync_frames_bucket_total{bucket="3_10"} 1387
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27938
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27149
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 1129916
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 13968524660 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 390551333464 (363.73 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 35
```