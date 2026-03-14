# Server Metrics 2026-03-14 14:51:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 5610.5 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224526
telemt_connections_bad_total 5861
telemt_handshake_timeouts_total 3163
telemt_upstream_connect_attempt_total 1149
telemt_upstream_connect_success_total 1142
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 1576
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 87165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206012
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 424
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 827
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 206004
telemt_user_connections_current{user="hello"} 1756
telemt_user_octets_from_client{user="hello"} 3577775028 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 58277943356 (54.28 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 5615.9 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89167
telemt_connections_bad_total 7651
telemt_handshake_timeouts_total 3340
telemt_upstream_connect_attempt_total 1201
telemt_upstream_connect_success_total 1193
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 864
telemt_me_reconnect_success_total 844
telemt_me_reader_eof_total 853
telemt_me_idle_close_by_peer_total 853
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 28228
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72086
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 434
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 862
telemt_me_writer_restored_same_endpoint_total 833
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 72045
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 964083944 (919.42 MB)
telemt_user_octets_to_client{user="hello"} 32605318104 (30.37 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 5478.8 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164146
telemt_connections_bad_total 657
telemt_handshake_timeouts_total 29145
telemt_upstream_connect_attempt_total 1262
telemt_upstream_connect_success_total 1257
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 939
telemt_me_reconnect_success_total 930
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 46462
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126120
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 221
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 923
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 126048
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 1879447248 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 37972945440 (35.37 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 5333.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86792
telemt_connections_bad_total 22270
telemt_handshake_timeouts_total 11784
telemt_upstream_connect_attempt_total 1377
telemt_upstream_connect_success_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 1377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1090
telemt_me_reconnect_success_total 1083
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1094
telemt_me_route_drop_no_conn_total 19715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51212
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 51180
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 1078001636 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 14258219308 (13.28 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 5628.7 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89356
telemt_connections_bad_total 185
telemt_handshake_timeouts_total 1531
telemt_upstream_connect_attempt_total 1332
telemt_upstream_connect_success_total 1304
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1617
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 30497
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81841
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1006
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 81840
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 1236770704 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 28656696392 (26.69 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 97
```