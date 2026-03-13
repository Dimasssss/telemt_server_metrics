# Server Metrics 2026-03-13 04:36:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81494.5 (22h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2208739
telemt_connections_bad_total 30679
telemt_handshake_timeouts_total 23268
telemt_upstream_connect_attempt_total 16096
telemt_upstream_connect_success_total 16007
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 16096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 20811
telemt_me_reconnect_success_total 11946
telemt_me_reader_eof_total 12895
telemt_me_idle_close_by_peer_total 12894
telemt_me_route_drop_no_conn_total 842830
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8932
telemt_desync_full_logged_total 2319
telemt_desync_suppressed_total 6613
telemt_desync_frames_bucket_total{bucket="1_2"} 2352
telemt_desync_frames_bucket_total{bucket="3_10"} 3220
telemt_desync_frames_bucket_total{bucket="gt_10"} 3360
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12391
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11933
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2030645
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 29465929716 (27.44 GB)
telemt_user_octets_to_client{user="hello"} 701572641156 (653.39 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111115.1 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897266
telemt_connections_bad_total 11909
telemt_handshake_timeouts_total 39436
telemt_upstream_connect_attempt_total 28211
telemt_upstream_connect_success_total 28182
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 28211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3498
telemt_me_reconnect_attempts_total 21117
telemt_me_reconnect_success_total 21004
telemt_me_reader_eof_total 22388
telemt_me_idle_close_by_peer_total 22388
telemt_me_route_drop_no_conn_total 286320
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809271
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3227
telemt_desync_full_logged_total 1013
telemt_desync_suppressed_total 2214
telemt_desync_frames_bucket_total{bucket="1_2"} 1290
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21210
telemt_me_writer_restored_same_endpoint_total 20995
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 811176
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 12984830556 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 312929253739 (291.44 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111114.9 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1854454
telemt_connections_bad_total 16129
telemt_handshake_timeouts_total 122261
telemt_upstream_connect_attempt_total 25899
telemt_upstream_connect_success_total 25889
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1641
telemt_me_reconnect_attempts_total 21270
telemt_me_reconnect_success_total 20002
telemt_me_reader_eof_total 21184
telemt_me_idle_close_by_peer_total 21183
telemt_me_route_drop_no_conn_total 598958
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1463882
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20192
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19961
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1463475
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 25288976936 (23.55 GB)
telemt_user_octets_to_client{user="hello"} 520539383573 (484.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111115.4 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1147695
telemt_connections_bad_total 13195
telemt_handshake_timeouts_total 74826
telemt_upstream_connect_attempt_total 38284
telemt_upstream_connect_success_total 36001
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 38010
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11387
telemt_me_reconnect_attempts_total 33532
telemt_me_reconnect_success_total 24601
telemt_me_reader_eof_total 26551
telemt_me_idle_close_by_peer_total 26544
telemt_me_route_drop_no_conn_total 408096
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987300
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1952
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 25044
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24577
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 992477
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 15214816301 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 392078377234 (365.15 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 111115.1 (30h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1275687
telemt_connections_bad_total 12885
telemt_handshake_timeouts_total 10242
telemt_upstream_connect_attempt_total 35053
telemt_upstream_connect_success_total 34628
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 35053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1935
telemt_me_reconnect_attempts_total 42828
telemt_me_reconnect_success_total 29096
telemt_me_reader_eof_total 30595
telemt_me_idle_close_by_peer_total 30595
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 473193
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1180345
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4311
telemt_desync_full_logged_total 1548
telemt_desync_suppressed_total 2763
telemt_desync_frames_bucket_total{bucket="1_2"} 1306
telemt_desync_frames_bucket_total{bucket="3_10"} 1408
telemt_desync_frames_bucket_total{bucket="gt_10"} 1597
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29857
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29046
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1180200
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 14391222724 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 402846932732 (375.18 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 61
```