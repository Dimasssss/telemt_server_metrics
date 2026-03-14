# Server Metrics 2026-03-14 16:23:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 11167.9 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441804
telemt_connections_bad_total 19439
telemt_handshake_timeouts_total 5392
telemt_upstream_connect_attempt_total 2446
telemt_upstream_connect_success_total 2434
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 2601
telemt_me_reconnect_success_total 1806
telemt_me_reader_eof_total 1880
telemt_me_idle_close_by_peer_total 1880
telemt_me_route_drop_no_conn_total 172571
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397282
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1319
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1858
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1797
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 397278
telemt_user_connections_current{user="hello"} 1747
telemt_user_octets_from_client{user="hello"} 6995236044 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 120602957780 (112.32 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 11173.3 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181327
telemt_connections_bad_total 17680
telemt_handshake_timeouts_total 5942
telemt_upstream_connect_attempt_total 2435
telemt_upstream_connect_success_total 2407
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 2560
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1845
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 56090
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145565
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 552
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1850
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1766
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 145506
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 1874691936 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 59595516756 (55.50 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 11036.1 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368111
telemt_connections_bad_total 1441
telemt_handshake_timeouts_total 83218
telemt_upstream_connect_attempt_total 2312
telemt_upstream_connect_success_total 2304
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 5589
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1834
telemt_me_idle_close_by_peer_total 1834
telemt_me_route_drop_no_conn_total 94230
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251378
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1816
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 251262
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 3725707044 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 94866339484 (88.35 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 10890.6 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196830
telemt_connections_bad_total 40226
telemt_handshake_timeouts_total 33562
telemt_upstream_connect_attempt_total 2738
telemt_upstream_connect_success_total 2737
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2153
telemt_me_reconnect_success_total 2138
telemt_me_reader_eof_total 2186
telemt_me_idle_close_by_peer_total 2186
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 44182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120539
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 241
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2152
telemt_me_writer_restored_same_endpoint_total 2132
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 120504
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 2020382168 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 39748189348 (37.02 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 11186.3 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174767
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 2415
telemt_upstream_connect_attempt_total 2533
telemt_upstream_connect_success_total 2478
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 2533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 2533
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1960
telemt_me_idle_close_by_peer_total 1960
telemt_me_route_drop_no_conn_total 58789
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161179
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1931
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1850
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 161194
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 2486023944 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 62916359156 (58.60 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 85
```