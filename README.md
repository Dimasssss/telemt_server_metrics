# Server Metrics 2026-03-14 16:34:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 11781.7 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469275
telemt_connections_bad_total 22326
telemt_handshake_timeouts_total 6108
telemt_upstream_connect_attempt_total 2496
telemt_upstream_connect_success_total 2484
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 2630
telemt_me_reconnect_success_total 1835
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_route_drop_no_conn_total 182489
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420189
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1445
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 540
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1889
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1826
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 420183
telemt_user_connections_current{user="hello"} 1774
telemt_user_octets_from_client{user="hello"} 7636641684 (7.11 GB)
telemt_user_octets_to_client{user="hello"} 127405796812 (118.66 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 11787.0 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192659
telemt_connections_bad_total 19722
telemt_handshake_timeouts_total 6065
telemt_upstream_connect_attempt_total 2578
telemt_upstream_connect_success_total 2549
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 2670
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1956
telemt_me_idle_close_by_peer_total 1956
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 58986
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153822
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 587
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1962
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1874
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 153775
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 2335784304 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 62074248024 (57.81 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 11649.7 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387792
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 84527
telemt_upstream_connect_attempt_total 2388
telemt_upstream_connect_success_total 2380
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 5665
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_route_drop_no_conn_total 99394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265571
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 586
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1893
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 265449
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 3967130604 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 99875777972 (93.02 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 11504.2 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207408
telemt_connections_bad_total 43399
telemt_handshake_timeouts_total 33946
telemt_upstream_connect_attempt_total 2939
telemt_upstream_connect_success_total 2938
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 2345
telemt_me_reconnect_success_total 2329
telemt_me_reader_eof_total 2382
telemt_me_idle_close_by_peer_total 2382
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 46608
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127354
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2349
telemt_me_writer_restored_same_endpoint_total 2322
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 127319
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 2145256512 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 41424239260 (38.58 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 11799.6 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184482
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2558
telemt_upstream_connect_attempt_total 2623
telemt_upstream_connect_success_total 2566
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 2623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 2590
telemt_me_reconnect_success_total 1925
telemt_me_reader_eof_total 2017
telemt_me_idle_close_by_peer_total 2017
telemt_me_route_drop_no_conn_total 61599
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170055
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 479
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1988
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1907
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 170070
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 2596185192 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 67022236600 (62.42 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 113
```