# Server Metrics 2026-03-10 18:09:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13317.9 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443533
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 2592
telemt_upstream_connect_success_total 2583
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 11135
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 2135
telemt_me_idle_close_by_peer_total 2135
telemt_me_route_drop_no_conn_total 186447
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418427
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2100
telemt_desync_full_logged_total 576
telemt_desync_suppressed_total 1524
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2162
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1862
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 418348
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 5465719744 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 122192021980 (113.80 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13374.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170690
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 11242
telemt_upstream_connect_attempt_total 3026
telemt_upstream_connect_success_total 3011
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2330
telemt_me_reconnect_success_total 2315
telemt_me_reader_eof_total 2400
telemt_me_idle_close_by_peer_total 2400
telemt_me_route_drop_no_conn_total 50992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148881
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2331
telemt_me_writer_restored_same_endpoint_total 2294
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 148844
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 1872194932 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 39829530644 (37.09 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13374.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325957
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 31341
telemt_upstream_connect_attempt_total 4351
telemt_upstream_connect_success_total 4285
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3733
telemt_me_reconnect_success_total 2538
telemt_me_reader_eof_total 2657
telemt_me_idle_close_by_peer_total 2657
telemt_me_route_drop_no_conn_total 107040
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270184
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 873
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 621
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 300
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2612
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2527
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 271146
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 3705408745 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 85781474297 (79.89 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13374.9 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211453
telemt_connections_bad_total 13005
telemt_handshake_timeouts_total 19800
telemt_upstream_connect_attempt_total 3439
telemt_upstream_connect_success_total 3439
telemt_upstream_connect_attempts_per_request{bucket="1"} 3439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1605
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2756
telemt_me_reconnect_success_total 2740
telemt_me_reader_eof_total 2845
telemt_me_idle_close_by_peer_total 2845
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 69178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169953
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2764
telemt_me_writer_restored_same_endpoint_total 2728
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 169766
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 2685955140 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 47420567536 (44.16 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13374.5 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223839
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1681
telemt_upstream_connect_attempt_total 4000
telemt_upstream_connect_success_total 3988
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 3293
telemt_me_reconnect_success_total 3273
telemt_me_reader_eof_total 3358
telemt_me_idle_close_by_peer_total 3358
telemt_me_route_drop_no_conn_total 82487
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210648
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1138
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 737
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3305
telemt_me_writer_restored_same_endpoint_total 3273
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 210583
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 4642998372 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 63907418584 (59.52 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 94
```