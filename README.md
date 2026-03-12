# Server Metrics 2026-03-12 22:19:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58857.6 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1911811
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20959
telemt_upstream_connect_attempt_total 11616
telemt_upstream_connect_success_total 11549
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 11616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 599
telemt_me_reconnect_attempts_total 17431
telemt_me_reconnect_success_total 8576
telemt_me_reader_eof_total 9267
telemt_me_idle_close_by_peer_total 9266
telemt_me_route_drop_no_conn_total 747090
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1779079
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8482
telemt_desync_full_logged_total 2208
telemt_desync_suppressed_total 6274
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3055
telemt_desync_frames_bucket_total{bucket="gt_10"} 3192
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8973
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8563
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 1778558
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 26911104540 (25.06 GB)
telemt_user_octets_to_client{user="hello"} 629943467540 (586.68 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88478.2 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793312
telemt_connections_bad_total 11703
telemt_handshake_timeouts_total 31263
telemt_upstream_connect_attempt_total 22379
telemt_upstream_connect_success_total 22350
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3410
telemt_me_reconnect_attempts_total 16364
telemt_me_reconnect_success_total 16269
telemt_me_reader_eof_total 17315
telemt_me_idle_close_by_peer_total 17315
telemt_me_route_drop_no_conn_total 256907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716483
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16434
telemt_me_writer_restored_same_endpoint_total 16260
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 718363
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 12061120868 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 278753877615 (259.61 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88478.0 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1648179
telemt_connections_bad_total 7822
telemt_handshake_timeouts_total 113250
telemt_upstream_connect_attempt_total 20658
telemt_upstream_connect_success_total 20652
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 17112
telemt_me_reconnect_success_total 15863
telemt_me_reader_eof_total 16766
telemt_me_idle_close_by_peer_total 16765
telemt_me_route_drop_no_conn_total 542375
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1281989
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 16013
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15822
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 1281595
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 19697521552 (18.34 GB)
telemt_user_octets_to_client{user="hello"} 473893856409 (441.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88478.4 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015963
telemt_connections_bad_total 12998
telemt_handshake_timeouts_total 71364
telemt_upstream_connect_attempt_total 22625
telemt_upstream_connect_success_total 22532
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 22625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1687
telemt_me_reconnect_attempts_total 25835
telemt_me_reconnect_success_total 18105
telemt_me_reader_eof_total 19345
telemt_me_idle_close_by_peer_total 19345
telemt_me_route_drop_no_conn_total 363492
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 884914
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18491
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18084
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 884263
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 14184551580 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 353632339640 (329.35 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88478.3 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1136085
telemt_connections_bad_total 12534
telemt_handshake_timeouts_total 9195
telemt_upstream_connect_attempt_total 27162
telemt_upstream_connect_success_total 26824
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 27162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 1442
telemt_me_reconnect_attempts_total 33423
telemt_me_reconnect_success_total 22384
telemt_me_reader_eof_total 23538
telemt_me_idle_close_by_peer_total 23538
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 425427
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045755
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3914
telemt_desync_full_logged_total 1363
telemt_desync_suppressed_total 2551
telemt_desync_frames_bucket_total{bucket="1_2"} 1150
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 22987
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22340
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 1045616
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 12838020088 (11.96 GB)
telemt_user_octets_to_client{user="hello"} 370657064392 (345.20 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 47
```