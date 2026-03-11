# Server Metrics 2026-03-11 23:47:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7343.7 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66104
telemt_connections_bad_total 1249
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 1797
telemt_upstream_connect_success_total 1796
telemt_upstream_connect_attempts_per_request{bucket="1"} 1796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1383
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1436
telemt_me_route_drop_no_conn_total 24680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61744
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1398
telemt_me_writer_restored_same_endpoint_total 1362
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 61702
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 420254412 (400.79 MB)
telemt_user_octets_to_client{user="hello"} 18635409268 (17.36 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7344.3 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23226
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 2089
telemt_upstream_connect_success_total 2089
telemt_upstream_connect_attempts_per_request{bucket="1"} 2089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 1658
telemt_me_reader_eof_total 1738
telemt_me_idle_close_by_peer_total 1738
telemt_me_route_drop_no_conn_total 6166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1665
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 22133
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 548664028 (523.25 MB)
telemt_user_octets_to_client{user="hello"} 9733569120 (9.07 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7344.0 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64082
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 4558
telemt_upstream_connect_attempt_total 2664
telemt_upstream_connect_success_total 2662
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1923
telemt_me_reconnect_success_total 1879
telemt_me_reader_eof_total 1871
telemt_me_idle_close_by_peer_total 1871
telemt_me_route_drop_no_conn_total 10645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36601
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1807
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1838
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 36946
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 470751616 (448.94 MB)
telemt_user_octets_to_client{user="hello"} 19214121073 (17.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7344.6 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34818
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 2222
telemt_upstream_connect_success_total 2210
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 1783
telemt_me_reader_eof_total 1847
telemt_me_idle_close_by_peer_total 1847
telemt_me_route_drop_no_conn_total 10905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33747
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1793
telemt_me_writer_restored_same_endpoint_total 1762
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 33743
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 177425608 (169.21 MB)
telemt_user_octets_to_client{user="hello"} 11075099076 (10.31 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7344.4 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45542
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 493
telemt_upstream_connect_attempt_total 3266
telemt_upstream_connect_success_total 3234
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 4288
telemt_me_reconnect_success_total 2801
telemt_me_reader_eof_total 2871
telemt_me_idle_close_by_peer_total 2871
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 10439
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42429
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 70
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2861
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2795
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 42425
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 237748764 (226.73 MB)
telemt_user_octets_to_client{user="hello"} 12091720280 (11.26 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 34
```