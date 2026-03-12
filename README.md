# Server Metrics 2026-03-12 00:43:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10709.0 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90949
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 252
telemt_upstream_connect_attempt_total 2512
telemt_upstream_connect_success_total 2512
telemt_upstream_connect_attempts_per_request{bucket="1"} 2512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 1968
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2055
telemt_me_idle_close_by_peer_total 2055
telemt_me_route_drop_no_conn_total 33106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86119
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 198
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1986
telemt_me_writer_restored_same_endpoint_total 1945
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 86038
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 616254112 (587.71 MB)
telemt_user_octets_to_client{user="hello"} 26391653124 (24.58 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10709.6 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31673
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 382
telemt_upstream_connect_attempt_total 3189
telemt_upstream_connect_success_total 3186
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 2460
telemt_me_reconnect_success_total 2439
telemt_me_reader_eof_total 2566
telemt_me_idle_close_by_peer_total 2566
telemt_me_route_drop_no_conn_total 8584
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29914
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2456
telemt_me_writer_restored_same_endpoint_total 2430
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 30093
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 596603859 (568.97 MB)
telemt_user_octets_to_client{user="hello"} 10959835586 (10.21 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10709.3 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93272
telemt_connections_bad_total 722
telemt_handshake_timeouts_total 8104
telemt_upstream_connect_attempt_total 3531
telemt_upstream_connect_success_total 3529
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 2661
telemt_me_reconnect_success_total 2614
telemt_me_reader_eof_total 2651
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 15840
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52220
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2551
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2573
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 52564
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 562070904 (536.03 MB)
telemt_user_octets_to_client{user="hello"} 22097132641 (20.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10709.8 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49080
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 719
telemt_upstream_connect_attempt_total 3213
telemt_upstream_connect_success_total 3199
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 2652
telemt_me_reconnect_success_total 2642
telemt_me_reader_eof_total 2766
telemt_me_idle_close_by_peer_total 2766
telemt_me_route_drop_no_conn_total 16434
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2658
telemt_me_writer_restored_same_endpoint_total 2621
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 47543
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 242610952 (231.37 MB)
telemt_user_octets_to_client{user="hello"} 12176404224 (11.34 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10709.6 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62855
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 536
telemt_upstream_connect_attempt_total 4562
telemt_upstream_connect_success_total 4524
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 4562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 5447
telemt_me_reconnect_success_total 3956
telemt_me_reader_eof_total 4077
telemt_me_idle_close_by_peer_total 4077
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 15118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59017
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 143
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4024
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3950
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 58999
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 285340568 (272.12 MB)
telemt_user_octets_to_client{user="hello"} 14140940448 (13.17 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```