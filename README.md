# Server Metrics 2026-03-10 18:14:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13623.2 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452533
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2100
telemt_upstream_connect_attempt_total 2652
telemt_upstream_connect_success_total 2643
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 280
telemt_me_reconnect_attempts_total 11170
telemt_me_reconnect_success_total 1903
telemt_me_reader_eof_total 2170
telemt_me_idle_close_by_peer_total 2170
telemt_me_route_drop_no_conn_total 190465
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426085
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2140
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1555
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2197
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 426006
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 5590413924 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 124205052140 (115.67 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13680.0 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173529
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 11415
telemt_upstream_connect_attempt_total 3141
telemt_upstream_connect_success_total 3126
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2402
telemt_me_reconnect_success_total 2384
telemt_me_reader_eof_total 2484
telemt_me_idle_close_by_peer_total 2484
telemt_me_route_drop_no_conn_total 51889
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151462
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 678
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2402
telemt_me_writer_restored_same_endpoint_total 2363
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 151425
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 1889599344 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 40755424072 (37.96 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13680.0 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332418
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 31532
telemt_upstream_connect_attempt_total 4485
telemt_upstream_connect_success_total 4415
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3817
telemt_me_reconnect_success_total 2620
telemt_me_reader_eof_total 2744
telemt_me_idle_close_by_peer_total 2744
telemt_me_route_drop_no_conn_total 109218
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276242
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 892
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2699
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2609
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 277203
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 3786688129 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 87777158241 (81.75 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13680.3 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215527
telemt_connections_bad_total 13319
telemt_handshake_timeouts_total 20029
telemt_upstream_connect_attempt_total 3538
telemt_upstream_connect_success_total 3538
telemt_upstream_connect_attempts_per_request{bucket="1"} 3538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2811
telemt_me_reconnect_success_total 2793
telemt_me_reader_eof_total 2905
telemt_me_idle_close_by_peer_total 2905
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 70446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173355
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2817
telemt_me_writer_restored_same_endpoint_total 2781
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 173168
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 2706334668 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 48185673680 (44.88 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13680.2 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227855
telemt_connections_bad_total 797
telemt_handshake_timeouts_total 1692
telemt_upstream_connect_attempt_total 4120
telemt_upstream_connect_success_total 4108
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 3368
telemt_me_reconnect_success_total 3346
telemt_me_reader_eof_total 3437
telemt_me_idle_close_by_peer_total 3437
telemt_me_route_drop_no_conn_total 83982
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214408
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1155
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 477
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3384
telemt_me_writer_restored_same_endpoint_total 3346
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 214343
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 4748170192 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 65955587024 (61.43 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 81
```