# Server Metrics 2026-03-12 01:54:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14991.6 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122990
telemt_connections_bad_total 1350
telemt_handshake_timeouts_total 1454
telemt_upstream_connect_attempt_total 3483
telemt_upstream_connect_success_total 3483
telemt_upstream_connect_attempts_per_request{bucket="1"} 3483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2723
telemt_me_reconnect_success_total 2712
telemt_me_reader_eof_total 2860
telemt_me_idle_close_by_peer_total 2860
telemt_me_route_drop_no_conn_total 44491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116256
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2745
telemt_me_writer_restored_same_endpoint_total 2696
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 116122
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 829525228 (791.10 MB)
telemt_user_octets_to_client{user="hello"} 34003051712 (31.67 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14992.2 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42077
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 464
telemt_upstream_connect_attempt_total 4386
telemt_upstream_connect_success_total 4382
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3442
telemt_me_reconnect_success_total 3416
telemt_me_reader_eof_total 3618
telemt_me_idle_close_by_peer_total 3618
telemt_me_route_drop_no_conn_total 11581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3442
telemt_me_writer_restored_same_endpoint_total 3407
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 39446
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 679286127 (647.82 MB)
telemt_user_octets_to_client{user="hello"} 13656224486 (12.72 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 14992.0 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167899
telemt_connections_bad_total 1119
telemt_handshake_timeouts_total 12867
telemt_upstream_connect_attempt_total 4704
telemt_upstream_connect_success_total 4702
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 3618
telemt_me_reconnect_success_total 3567
telemt_me_reader_eof_total 3675
telemt_me_idle_close_by_peer_total 3675
telemt_me_route_drop_no_conn_total 22683
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3515
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3526
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 71231
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 652608360 (622.38 MB)
telemt_user_octets_to_client{user="hello"} 25002664961 (23.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 14992.3 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63971
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 1437
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4505
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 3743
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 3943
telemt_me_idle_close_by_peer_total 3943
telemt_me_route_drop_no_conn_total 22489
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61547
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3754
telemt_me_writer_restored_same_endpoint_total 3710
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 61538
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 346595040 (330.54 MB)
telemt_user_octets_to_client{user="hello"} 14102265108 (13.13 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14992.1 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82392
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 601
telemt_upstream_connect_attempt_total 5799
telemt_upstream_connect_success_total 5744
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 6452
telemt_me_reconnect_success_total 4958
telemt_me_reader_eof_total 5140
telemt_me_idle_close_by_peer_total 5140
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 20446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78105
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 244
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5041
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4946
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 78085
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 359624712 (342.96 MB)
telemt_user_octets_to_client{user="hello"} 16239776428 (15.12 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```