# Server Metrics 2026-03-12 03:11:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19582.1 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166257
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 3320
telemt_upstream_connect_attempt_total 4492
telemt_upstream_connect_success_total 4492
telemt_upstream_connect_attempts_per_request{bucket="1"} 4492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3517
telemt_me_reconnect_success_total 3502
telemt_me_reader_eof_total 3699
telemt_me_idle_close_by_peer_total 3699
telemt_me_route_drop_no_conn_total 60230
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156828
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3541
telemt_me_writer_restored_same_endpoint_total 3486
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 156647
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 1186761968 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 49541830696 (46.14 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19582.8 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55446
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 931
telemt_upstream_connect_attempt_total 5586
telemt_upstream_connect_success_total 5583
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4426
telemt_me_reconnect_success_total 4398
telemt_me_reader_eof_total 4664
telemt_me_idle_close_by_peer_total 4664
telemt_me_route_drop_no_conn_total 15287
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 90
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4431
telemt_me_writer_restored_same_endpoint_total 4389
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 51968
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 785748171 (749.35 MB)
telemt_user_octets_to_client{user="hello"} 18598705726 (17.32 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19582.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297152
telemt_connections_bad_total 1495
telemt_handshake_timeouts_total 17101
telemt_upstream_connect_attempt_total 5931
telemt_upstream_connect_success_total 5929
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4630
telemt_me_reconnect_success_total 4576
telemt_me_reader_eof_total 4750
telemt_me_idle_close_by_peer_total 4750
telemt_me_route_drop_no_conn_total 29529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95917
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4536
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4535
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 96249
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 801636348 (764.50 MB)
telemt_user_octets_to_client{user="hello"} 29645521685 (27.61 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19583.1 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87404
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 4116
telemt_upstream_connect_attempt_total 5863
telemt_upstream_connect_success_total 5835
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 4858
telemt_me_reconnect_success_total 4840
telemt_me_reader_eof_total 5125
telemt_me_idle_close_by_peer_total 5125
telemt_me_route_drop_no_conn_total 29716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81980
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4871
telemt_me_writer_restored_same_endpoint_total 4819
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 81969
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 535042032 (510.26 MB)
telemt_user_octets_to_client{user="hello"} 19628657280 (18.28 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19582.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105386
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 681
telemt_upstream_connect_attempt_total 7246
telemt_upstream_connect_success_total 7172
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 7664
telemt_me_reconnect_success_total 6166
telemt_me_reader_eof_total 6408
telemt_me_idle_close_by_peer_total 6408
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 26939
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100452
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 339
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6258
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6150
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 100429
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 610319848 (582.05 MB)
telemt_user_octets_to_client{user="hello"} 21968668440 (20.46 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 47
```