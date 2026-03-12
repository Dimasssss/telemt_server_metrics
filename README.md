# Server Metrics 2026-03-12 23:20:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62528.6 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1950544
telemt_connections_bad_total 26075
telemt_handshake_timeouts_total 21200
telemt_upstream_connect_attempt_total 12408
telemt_upstream_connect_success_total 12337
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 617
telemt_me_reconnect_attempts_total 18047
telemt_me_reconnect_success_total 9191
telemt_me_reader_eof_total 9925
telemt_me_idle_close_by_peer_total 9924
telemt_me_route_drop_no_conn_total 759882
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1813819
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8556
telemt_desync_full_logged_total 2233
telemt_desync_suppressed_total 6323
telemt_desync_frames_bucket_total{bucket="1_2"} 2258
telemt_desync_frames_bucket_total{bucket="3_10"} 3077
telemt_desync_frames_bucket_total{bucket="gt_10"} 3221
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9597
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9178
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1813287
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 27235948304 (25.37 GB)
telemt_user_octets_to_client{user="hello"} 643424514016 (599.24 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92149.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806544
telemt_connections_bad_total 11734
telemt_handshake_timeouts_total 31480
telemt_upstream_connect_attempt_total 23334
telemt_upstream_connect_success_total 23305
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3420
telemt_me_reconnect_attempts_total 17147
telemt_me_reconnect_success_total 17051
telemt_me_reader_eof_total 18152
telemt_me_idle_close_by_peer_total 18152
telemt_me_route_drop_no_conn_total 260741
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729204
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3012
telemt_desync_full_logged_total 939
telemt_desync_suppressed_total 2073
telemt_desync_frames_bucket_total{bucket="1_2"} 1196
telemt_desync_frames_bucket_total{bucket="3_10"} 988
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17223
telemt_me_writer_restored_same_endpoint_total 17042
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 731084
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 12109039368 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 282966461787 (263.53 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92148.8 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679589
telemt_connections_bad_total 8095
telemt_handshake_timeouts_total 113342
telemt_upstream_connect_attempt_total 21411
telemt_upstream_connect_success_total 21405
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1226
telemt_me_reconnect_attempts_total 17693
telemt_me_reconnect_success_total 16442
telemt_me_reader_eof_total 17388
telemt_me_idle_close_by_peer_total 17387
telemt_me_route_drop_no_conn_total 550473
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312396
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4974
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2383
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16602
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16401
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 1312002
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 19791772532 (18.43 GB)
telemt_user_octets_to_client{user="hello"} 484546511073 (451.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92149.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037850
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 71536
telemt_upstream_connect_attempt_total 32620
telemt_upstream_connect_success_total 30361
telemt_upstream_connect_fail_total 2122
telemt_upstream_connect_attempts_per_request{bucket="1"} 32346
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2121
telemt_me_keepalive_timeout_total 11247
telemt_me_reconnect_attempts_total 27725
telemt_me_reconnect_success_total 19888
telemt_me_reader_eof_total 21540
telemt_me_idle_close_by_peer_total 21533
telemt_me_route_drop_no_conn_total 368392
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 898551
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20250
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 19866
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 903771
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 14271409025 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 360525114326 (335.77 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92149.0 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1156731
telemt_connections_bad_total 12542
telemt_handshake_timeouts_total 9257
telemt_upstream_connect_attempt_total 28069
telemt_upstream_connect_success_total 27720
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 28069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 1455
telemt_me_reconnect_attempts_total 34147
telemt_me_reconnect_success_total 23107
telemt_me_reader_eof_total 24306
telemt_me_idle_close_by_peer_total 24306
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 431981
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1066071
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4019
telemt_desync_full_logged_total 1402
telemt_desync_suppressed_total 2617
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 1336
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 23720
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23062
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 1065929
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 13515680288 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 376166861964 (350.33 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 87
```