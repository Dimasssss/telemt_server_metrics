# Server Metrics 2026-03-14 15:06:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 6529.0 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260271
telemt_connections_bad_total 7576
telemt_handshake_timeouts_total 3393
telemt_upstream_connect_attempt_total 1319
telemt_upstream_connect_success_total 1312
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1699
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 102161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238610
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 346
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 952
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 906
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 238602
telemt_user_connections_current{user="hello"} 1716
telemt_user_octets_from_client{user="hello"} 3951958804 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 69832574596 (65.04 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 6534.3 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104620
telemt_connections_bad_total 8781
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 1427
telemt_upstream_connect_success_total 1413
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 1044
telemt_me_reconnect_success_total 1015
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1029
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 32620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84051
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 353
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1042
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 84009
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 1161756168 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 35818437024 (33.36 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 6397.2 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200550
telemt_connections_bad_total 670
telemt_handshake_timeouts_total 42122
telemt_upstream_connect_attempt_total 1478
telemt_upstream_connect_success_total 1473
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2237
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1118
telemt_me_idle_close_by_peer_total 1118
telemt_me_route_drop_no_conn_total 55295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147558
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 235
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1128
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 1064
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 147484
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 2264583752 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 48326379228 (45.01 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 6251.6 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101233
telemt_connections_bad_total 24462
telemt_handshake_timeouts_total 13290
telemt_upstream_connect_attempt_total 1619
telemt_upstream_connect_success_total 1618
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1287
telemt_me_reconnect_success_total 1278
telemt_me_reader_eof_total 1288
telemt_me_idle_close_by_peer_total 1288
telemt_me_route_drop_no_conn_total 23719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62296
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1281
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 62261
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1244799364 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 18216572016 (16.97 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 6547.1 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103730
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 1714
telemt_upstream_connect_attempt_total 1518
telemt_upstream_connect_success_total 1482
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1751
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 1141
telemt_me_idle_close_by_peer_total 1141
telemt_me_route_drop_no_conn_total 35875
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 319
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1142
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1076
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 95459
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 1443100924 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 33361126388 (31.07 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 105
```