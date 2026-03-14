# Server Metrics 2026-03-14 14:46:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 5304.0 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212711
telemt_connections_bad_total 5049
telemt_handshake_timeouts_total 3073
telemt_upstream_connect_attempt_total 1051
telemt_upstream_connect_success_total 1045
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1523
telemt_me_reconnect_success_total 743
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_route_drop_no_conn_total 82587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195472
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 777
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 734
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 195465
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 3431743000 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 54446518976 (50.71 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 5309.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84243
telemt_connections_bad_total 6841
telemt_handshake_timeouts_total 3205
telemt_upstream_connect_attempt_total 1091
telemt_upstream_connect_success_total 1085
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 799
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 789
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 26424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68223
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 68182
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 925345784 (882.48 MB)
telemt_user_octets_to_client{user="hello"} 31266798112 (29.12 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 5172.2 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153480
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 25874
telemt_upstream_connect_attempt_total 1160
telemt_upstream_connect_success_total 1156
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 866
telemt_me_reconnect_success_total 857
telemt_me_reader_eof_total 840
telemt_me_idle_close_by_peer_total 840
telemt_me_route_drop_no_conn_total 43918
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119559
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 850
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 119497
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 1774096992 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 35871765332 (33.41 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 5026.7 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81717
telemt_connections_bad_total 21545
telemt_handshake_timeouts_total 11545
telemt_upstream_connect_attempt_total 1346
telemt_upstream_connect_success_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 1346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1059
telemt_me_reconnect_success_total 1052
telemt_me_reader_eof_total 1063
telemt_me_idle_close_by_peer_total 1063
telemt_me_route_drop_no_conn_total 18567
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47720
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
telemt_me_writer_removed_unexpected_total 1052
telemt_me_writer_restored_same_endpoint_total 1051
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 47688
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 990552784 (944.66 MB)
telemt_user_octets_to_client{user="hello"} 13319914040 (12.41 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 5322.4 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84752
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 1225
telemt_upstream_connect_success_total 1201
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1557
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 934
telemt_me_idle_close_by_peer_total 934
telemt_me_route_drop_no_conn_total 29053
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77570
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 286
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 946
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 889
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 77570
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 1177725700 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 27607170596 (25.71 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 103
```