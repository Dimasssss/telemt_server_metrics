# Server Metrics 2026-03-10 17:43:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11788.8 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395739
telemt_connections_bad_total 6541
telemt_handshake_timeouts_total 1894
telemt_upstream_connect_attempt_total 2294
telemt_upstream_connect_success_total 2285
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 10894
telemt_me_reconnect_success_total 1628
telemt_me_reader_eof_total 1878
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 168686
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375830
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1332
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1918
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1622
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 375760
telemt_user_connections_current{user="hello"} 1348
telemt_user_octets_from_client{user="hello"} 4910763236 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 109202643556 (101.70 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11845.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153916
telemt_connections_bad_total 1698
telemt_handshake_timeouts_total 10041
telemt_upstream_connect_attempt_total 2684
telemt_upstream_connect_success_total 2671
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 2034
telemt_me_reconnect_success_total 2023
telemt_me_reader_eof_total 2098
telemt_me_idle_close_by_peer_total 2098
telemt_me_route_drop_no_conn_total 44824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134189
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2034
telemt_me_writer_restored_same_endpoint_total 2002
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 134168
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1728707716 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 35881063628 (33.42 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11845.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295779
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 31079
telemt_upstream_connect_attempt_total 4007
telemt_upstream_connect_success_total 3941
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 3434
telemt_me_reconnect_success_total 2241
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2354
telemt_me_route_drop_no_conn_total 96165
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241054
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 736
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2314
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2230
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 242028
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 3319181785 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 71252842325 (66.36 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11845.9 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188829
telemt_connections_bad_total 11555
telemt_handshake_timeouts_total 18513
telemt_upstream_connect_attempt_total 3015
telemt_upstream_connect_success_total 3015
telemt_upstream_connect_attempts_per_request{bucket="1"} 3015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1397
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2375
telemt_me_reconnect_success_total 2358
telemt_me_reader_eof_total 2441
telemt_me_idle_close_by_peer_total 2441
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 60967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150862
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2378
telemt_me_writer_restored_same_endpoint_total 2346
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 150694
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 2430204984 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 42454909544 (39.54 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11845.8 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201541
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1597
telemt_upstream_connect_attempt_total 3563
telemt_upstream_connect_success_total 3553
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 2902
telemt_me_reconnect_success_total 2883
telemt_me_reader_eof_total 2963
telemt_me_idle_close_by_peer_total 2963
telemt_me_route_drop_no_conn_total 73950
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189366
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1022
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2910
telemt_me_writer_restored_same_endpoint_total 2883
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 189301
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 4247540452 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 55923905488 (52.08 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 85
```