# Server Metrics 2026-03-11 22:56:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4282.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41077
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 976
telemt_upstream_connect_success_total 976
telemt_upstream_connect_attempts_per_request{bucket="1"} 976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 735
telemt_me_reconnect_success_total 733
telemt_me_reader_eof_total 750
telemt_me_idle_close_by_peer_total 750
telemt_me_route_drop_no_conn_total 14751
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38399
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 743
telemt_me_writer_restored_same_endpoint_total 717
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 38385
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 242424652 (231.19 MB)
telemt_user_octets_to_client{user="hello"} 10491459460 (9.77 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4283.3 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15463
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 1228
telemt_upstream_connect_success_total 1228
telemt_upstream_connect_attempts_per_request{bucket="1"} 1228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 637
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 982
telemt_me_reconnect_success_total 975
telemt_me_reader_eof_total 1002
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 4087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14742
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 978
telemt_me_writer_restored_same_endpoint_total 966
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 14740
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 499935488 (476.78 MB)
telemt_user_octets_to_client{user="hello"} 7545188120 (7.03 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4283.1 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32010
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 3371
telemt_upstream_connect_attempt_total 1762
telemt_upstream_connect_success_total 1762
telemt_upstream_connect_attempts_per_request{bucket="1"} 1762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1196
telemt_me_reconnect_success_total 1157
telemt_me_reader_eof_total 1104
telemt_me_idle_close_by_peer_total 1104
telemt_me_route_drop_no_conn_total 6672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1076
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1116
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 24747
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 201126540 (191.81 MB)
telemt_user_octets_to_client{user="hello"} 12303797397 (11.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4283.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22915
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 1384
telemt_upstream_connect_success_total 1375
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 537
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 1124
telemt_me_reader_eof_total 1131
telemt_me_idle_close_by_peer_total 1131
telemt_me_route_drop_no_conn_total 6137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1127
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 22200
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 129451504 (123.45 MB)
telemt_user_octets_to_client{user="hello"} 9604161148 (8.94 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4283.3 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27552
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 1774
telemt_upstream_connect_success_total 1756
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1512
telemt_me_reconnect_success_total 1502
telemt_me_reader_eof_total 1478
telemt_me_idle_close_by_peer_total 1478
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 6326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25957
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 29
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 25953
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 180738188 (172.37 MB)
telemt_user_octets_to_client{user="hello"} 7014230408 (6.53 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 39
```