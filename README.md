# Server Metrics 2026-03-10 17:48:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12094.3 (3h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405719
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 1931
telemt_upstream_connect_attempt_total 2363
telemt_upstream_connect_success_total 2354
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 10952
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1950
telemt_me_idle_close_by_peer_total 1950
telemt_me_route_drop_no_conn_total 171855
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384090
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1916
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1976
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1679
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 384017
telemt_user_connections_current{user="hello"} 1453
telemt_user_octets_from_client{user="hello"} 5015843864 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 112323919024 (104.61 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12150.9 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156941
telemt_connections_bad_total 1698
telemt_handshake_timeouts_total 10189
telemt_upstream_connect_attempt_total 2755
telemt_upstream_connect_success_total 2742
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2105
telemt_me_reconnect_success_total 2093
telemt_me_reader_eof_total 2173
telemt_me_idle_close_by_peer_total 2173
telemt_me_route_drop_no_conn_total 45884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136898
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2104
telemt_me_writer_restored_same_endpoint_total 2072
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 136877
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 1744126700 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 36645029708 (34.13 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12150.8 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301551
telemt_connections_bad_total 874
telemt_handshake_timeouts_total 31125
telemt_upstream_connect_attempt_total 4064
telemt_upstream_connect_success_total 3998
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 3491
telemt_me_reconnect_success_total 2297
telemt_me_reader_eof_total 2415
telemt_me_idle_close_by_peer_total 2415
telemt_me_route_drop_no_conn_total 98168
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246589
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 777
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2370
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2286
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 247563
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 3397561309 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 73308076473 (68.27 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12151.3 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193346
telemt_connections_bad_total 11837
telemt_handshake_timeouts_total 18716
telemt_upstream_connect_attempt_total 3139
telemt_upstream_connect_success_total 3139
telemt_upstream_connect_attempts_per_request{bucket="1"} 3139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1458
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 2499
telemt_me_reconnect_success_total 2483
telemt_me_reader_eof_total 2568
telemt_me_idle_close_by_peer_total 2568
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 62103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154726
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 476
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2505
telemt_me_writer_restored_same_endpoint_total 2471
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 154557
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 2526526924 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 43552003936 (40.56 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12151.0 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205835
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1600
telemt_upstream_connect_attempt_total 3661
telemt_upstream_connect_success_total 3651
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 3000
telemt_me_reconnect_success_total 2981
telemt_me_reader_eof_total 3061
telemt_me_idle_close_by_peer_total 3061
telemt_me_route_drop_no_conn_total 75506
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193588
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1040
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 674
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3008
telemt_me_writer_restored_same_endpoint_total 2981
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 193523
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 4375452404 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 56752496600 (52.85 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 104
```