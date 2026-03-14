# Server Metrics 2026-03-14 16:18:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 10861.4 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428983
telemt_connections_bad_total 19071
telemt_handshake_timeouts_total 5109
telemt_upstream_connect_attempt_total 2359
telemt_upstream_connect_success_total 2349
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 2543
telemt_me_reconnect_success_total 1753
telemt_me_reader_eof_total 1814
telemt_me_idle_close_by_peer_total 1814
telemt_me_route_drop_no_conn_total 167853
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385715
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1246
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1805
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1744
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 385712
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 6639627288 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 117503004260 (109.43 GB)
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 10866.5 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176537
telemt_connections_bad_total 17013
telemt_handshake_timeouts_total 5892
telemt_upstream_connect_attempt_total 2309
telemt_upstream_connect_success_total 2284
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 2461
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1748
telemt_me_idle_close_by_peer_total 1748
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 54694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141596
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 550
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1751
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 141537
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 1835055072 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 58241759548 (54.24 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 10729.4 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357961
telemt_connections_bad_total 1441
telemt_handshake_timeouts_total 81711
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2204
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 5533
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1771
telemt_me_idle_close_by_peer_total 1771
telemt_me_route_drop_no_conn_total 91372
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244402
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 492
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1760
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 244290
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 3598567932 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 93169150788 (86.77 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 10583.9 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190859
telemt_connections_bad_total 38240
telemt_handshake_timeouts_total 33439
telemt_upstream_connect_attempt_total 2654
telemt_upstream_connect_success_total 2653
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2106
telemt_me_reconnect_success_total 2091
telemt_me_reader_eof_total 2140
telemt_me_idle_close_by_peer_total 2140
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 41989
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116767
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2105
telemt_me_writer_restored_same_endpoint_total 2086
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 116732
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 1970754116 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 38919249488 (36.25 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 10879.3 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169825
telemt_connections_bad_total 346
telemt_handshake_timeouts_total 2354
telemt_upstream_connect_attempt_total 2450
telemt_upstream_connect_success_total 2397
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 2450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 2467
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1889
telemt_me_idle_close_by_peer_total 1889
telemt_me_route_drop_no_conn_total 57218
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156572
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1866
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1785
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 156588
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 2433801548 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 60230265904 (56.09 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 108
```