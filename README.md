# Server Metrics 2026-03-10 19:00:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16375.7 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527544
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2919
telemt_upstream_connect_attempt_total 3292
telemt_upstream_connect_success_total 3283
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 12836
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2700
telemt_me_idle_close_by_peer_total 2700
telemt_me_route_drop_no_conn_total 220539
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497907
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2615
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1903
telemt_desync_frames_bucket_total{bucket="1_2"} 691
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 917
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2715
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2372
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 497817
telemt_user_connections_current{user="hello"} 1191
telemt_user_octets_from_client{user="hello"} 7402677900 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 144178255920 (134.28 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16432.5 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230301
telemt_connections_bad_total 1814
telemt_handshake_timeouts_total 16394
telemt_upstream_connect_attempt_total 8574
telemt_upstream_connect_success_total 5830
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1874
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 703
telemt_me_reconnect_attempts_total 3746
telemt_me_reconnect_success_total 2963
telemt_me_reader_eof_total 3087
telemt_me_idle_close_by_peer_total 3085
telemt_me_route_drop_no_conn_total 128146
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193999
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 773
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3015
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 2942
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 195956
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 2116626410 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 46773047610 (43.56 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16432.4 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382221
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 31906
telemt_upstream_connect_attempt_total 5145
telemt_upstream_connect_success_total 5064
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 5145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 6574
telemt_me_reconnect_success_total 3127
telemt_me_reader_eof_total 3342
telemt_me_idle_close_by_peer_total 3342
telemt_me_route_drop_no_conn_total 127952
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324627
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1039
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3291
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3116
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 325581
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 4501675825 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 103689303433 (96.57 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16432.7 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248568
telemt_connections_bad_total 16175
telemt_handshake_timeouts_total 22394
telemt_upstream_connect_attempt_total 4493
telemt_upstream_connect_success_total 4493
telemt_upstream_connect_attempts_per_request{bucket="1"} 4493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 4622
telemt_me_reconnect_success_total 3610
telemt_me_reader_eof_total 3765
telemt_me_idle_close_by_peer_total 3765
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 81938
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199535
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 542
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3678
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3597
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 199326
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 2959325104 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 57290864276 (53.36 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16432.4 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263304
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 1801
telemt_upstream_connect_attempt_total 4967
telemt_upstream_connect_success_total 4949
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 4079
telemt_me_reconnect_success_total 4047
telemt_me_reader_eof_total 4169
telemt_me_idle_close_by_peer_total 4169
telemt_me_route_drop_no_conn_total 97398
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248650
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1379
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4102
telemt_me_writer_restored_same_endpoint_total 4047
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 248582
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 5155920688 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 78455938252 (73.07 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 80
```