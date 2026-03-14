# Server Metrics 2026-03-14 15:16:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 7142.4 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281139
telemt_connections_bad_total 7641
telemt_handshake_timeouts_total 3563
telemt_upstream_connect_attempt_total 1429
telemt_upstream_connect_success_total 1422
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1809
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1058
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 111307
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258407
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 574
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1062
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1017
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 258399
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 4385910172 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 78428257540 (73.04 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 7147.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113596
telemt_connections_bad_total 9309
telemt_handshake_timeouts_total 4507
telemt_upstream_connect_attempt_total 1559
telemt_upstream_connect_success_total 1541
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 1176
telemt_me_reconnect_success_total 1142
telemt_me_reader_eof_total 1158
telemt_me_idle_close_by_peer_total 1158
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 35910
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91924
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 357
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_restored_same_endpoint_total 1131
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 91885
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 1279315176 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 38273715300 (35.65 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 7010.6 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222631
telemt_connections_bad_total 827
telemt_handshake_timeouts_total 47902
telemt_upstream_connect_attempt_total 1581
telemt_upstream_connect_success_total 1576
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3704
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1252
telemt_me_idle_close_by_peer_total 1252
telemt_me_route_drop_no_conn_total 60900
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162583
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 249
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1262
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1155
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 162509
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 2449576956 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 56674183800 (52.78 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 6865.1 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113498
telemt_connections_bad_total 26016
telemt_handshake_timeouts_total 15600
telemt_upstream_connect_attempt_total 1836
telemt_upstream_connect_success_total 1835
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1461
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1463
telemt_me_idle_close_by_peer_total 1463
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 26510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 70490
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1338667336 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 20711030328 (19.29 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 7160.4 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113053
telemt_connections_bad_total 318
telemt_handshake_timeouts_total 1767
telemt_upstream_connect_attempt_total 1635
telemt_upstream_connect_success_total 1599
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1868
telemt_me_reconnect_success_total 1210
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 39076
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1259
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 104328
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 1594989388 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 38400146936 (35.76 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 105
```