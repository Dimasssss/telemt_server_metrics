# Server Metrics 2026-03-14 15:11:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 6835.6 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270797
telemt_connections_bad_total 7641
telemt_handshake_timeouts_total 3493
telemt_upstream_connect_attempt_total 1392
telemt_upstream_connect_success_total 1385
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1772
telemt_me_reconnect_success_total 989
telemt_me_reader_eof_total 1021
telemt_me_idle_close_by_peer_total 1021
telemt_me_route_drop_no_conn_total 106652
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248560
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1025
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 980
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 248553
telemt_user_connections_current{user="hello"} 1715
telemt_user_octets_from_client{user="hello"} 4185685632 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 74297425248 (69.19 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 6840.9 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109137
telemt_connections_bad_total 9058
telemt_handshake_timeouts_total 4443
telemt_upstream_connect_attempt_total 1508
telemt_upstream_connect_success_total 1491
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 1125
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 34163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87903
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 470
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1121
telemt_me_writer_restored_same_endpoint_total 1081
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 87861
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 1218632580 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 37044760492 (34.50 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 6703.9 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211715
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 45027
telemt_upstream_connect_attempt_total 1536
telemt_upstream_connect_success_total 1531
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3659
telemt_me_reconnect_success_total 1143
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1207
telemt_me_route_drop_no_conn_total 58214
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155339
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1217
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 155263
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 2368793496 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 52862454304 (49.23 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 6558.3 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106949
telemt_connections_bad_total 25229
telemt_handshake_timeouts_total 14111
telemt_upstream_connect_attempt_total 1759
telemt_upstream_connect_success_total 1758
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 1384
telemt_me_reconnect_success_total 1375
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1386
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 25096
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66191
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1380
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 66156
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 1282465876 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 19274820864 (17.95 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 6853.8 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108530
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 1592
telemt_upstream_connect_success_total 1556
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 1592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 1825
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 37611
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99979
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1216
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1149
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 99981
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 1523315256 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 36073498892 (33.60 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 121
```