# Server Metrics 2026-03-10 20:52:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23118.5 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665692
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 7833
telemt_upstream_connect_attempt_total 4903
telemt_upstream_connect_success_total 4894
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 15314
telemt_me_reconnect_success_total 3661
telemt_me_reader_eof_total 4073
telemt_me_idle_close_by_peer_total 4073
telemt_me_route_drop_no_conn_total 278936
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628197
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3234
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 2352
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1221
telemt_desync_frames_bucket_total{bucket="gt_10"} 1104
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4049
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3655
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 628006
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 8952020048 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 189236809324 (176.24 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23175.3 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293366
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17147
telemt_upstream_connect_attempt_total 11243
telemt_upstream_connect_success_total 8384
telemt_upstream_connect_fail_total 2859
telemt_upstream_connect_attempts_per_request{bucket="1"} 11243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2859
telemt_me_keepalive_timeout_total 1336
telemt_me_reconnect_attempts_total 5041
telemt_me_reconnect_success_total 4239
telemt_me_reader_eof_total 4440
telemt_me_idle_close_by_peer_total 4438
telemt_me_route_drop_no_conn_total 158569
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245821
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1412
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 1033
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4319
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4218
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 248085
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 2540022142 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 58196899780 (54.20 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 23175.1 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475046
telemt_connections_bad_total 2533
telemt_handshake_timeouts_total 32896
telemt_upstream_connect_attempt_total 6752
telemt_upstream_connect_success_total 6652
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 6752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 14114
telemt_me_reconnect_success_total 4386
telemt_me_reader_eof_total 4813
telemt_me_idle_close_by_peer_total 4813
telemt_me_route_drop_no_conn_total 164587
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413556
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1364
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 986
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4765
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 4375
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 414496
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 6003387281 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 131455613169 (122.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 23175.7 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322985
telemt_connections_bad_total 22641
telemt_handshake_timeouts_total 27750
telemt_upstream_connect_attempt_total 6264
telemt_upstream_connect_success_total 6264
telemt_upstream_connect_attempts_per_request{bucket="1"} 6264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 6086
telemt_me_reconnect_success_total 5068
telemt_me_reader_eof_total 5317
telemt_me_idle_close_by_peer_total 5317
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 104759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260387
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5152
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5055
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 260074
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 3870410932 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 80758404380 (75.21 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23175.2 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341888
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 2133
telemt_upstream_connect_attempt_total 7256
telemt_upstream_connect_success_total 7227
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 9756
telemt_me_reconnect_success_total 6005
telemt_me_reader_eof_total 6286
telemt_me_idle_close_by_peer_total 6286
telemt_me_route_drop_no_conn_total 123602
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321310
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1864
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1165
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6207
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6005
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 321205
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 6084862676 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 108551707108 (101.10 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 59
```