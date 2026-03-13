# Server Metrics 2026-03-13 01:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70173.4 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2033647
telemt_connections_bad_total 26135
telemt_handshake_timeouts_total 21709
telemt_upstream_connect_attempt_total 13888
telemt_upstream_connect_success_total 13809
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1251
telemt_me_reconnect_attempts_total 19174
telemt_me_reconnect_success_total 10314
telemt_me_reader_eof_total 11150
telemt_me_idle_close_by_peer_total 11149
telemt_me_route_drop_no_conn_total 792833
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1892358
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8683
telemt_desync_full_logged_total 2260
telemt_desync_suppressed_total 6423
telemt_desync_frames_bucket_total{bucket="1_2"} 2289
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10735
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10301
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 1891815
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 27686402976 (25.78 GB)
telemt_user_octets_to_client{user="hello"} 660853903444 (615.47 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99793.9 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838263
telemt_connections_bad_total 11774
telemt_handshake_timeouts_total 31976
telemt_upstream_connect_attempt_total 25371
telemt_upstream_connect_success_total 25342
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3447
telemt_me_reconnect_attempts_total 18839
telemt_me_reconnect_success_total 18735
telemt_me_reader_eof_total 19951
telemt_me_idle_close_by_peer_total 19951
telemt_me_route_drop_no_conn_total 270393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18919
telemt_me_writer_restored_same_endpoint_total 18726
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 761499
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 12258762316 (11.42 GB)
telemt_user_octets_to_client{user="hello"} 286527126915 (266.85 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99793.8 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1741543
telemt_connections_bad_total 8965
telemt_handshake_timeouts_total 116052
telemt_upstream_connect_attempt_total 23293
telemt_upstream_connect_success_total 23283
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1589
telemt_me_reconnect_attempts_total 19227
telemt_me_reconnect_success_total 17964
telemt_me_reader_eof_total 19019
telemt_me_idle_close_by_peer_total 19018
telemt_me_route_drop_no_conn_total 570801
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1367640
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 18135
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17923
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 1367237
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 20082429256 (18.70 GB)
telemt_user_octets_to_client{user="hello"} 496834650485 (462.71 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99793.8 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091350
telemt_connections_bad_total 13094
telemt_handshake_timeouts_total 72462
telemt_upstream_connect_attempt_total 34701
telemt_upstream_connect_success_total 32434
telemt_upstream_connect_fail_total 2130
telemt_upstream_connect_attempts_per_request{bucket="1"} 34427
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2129
telemt_me_keepalive_timeout_total 11273
telemt_me_reconnect_attempts_total 29452
telemt_me_reconnect_success_total 21611
telemt_me_reader_eof_total 23380
telemt_me_idle_close_by_peer_total 23373
telemt_me_route_drop_no_conn_total 385707
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935442
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 21990
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21589
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 940630
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 14461658325 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 369583156370 (344.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 99794.1 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1202690
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9394
telemt_upstream_connect_attempt_total 30443
telemt_upstream_connect_success_total 30062
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 30443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 1850
telemt_me_reconnect_attempts_total 36143
telemt_me_reconnect_success_total 25096
telemt_me_reader_eof_total 26389
telemt_me_idle_close_by_peer_total 26389
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 451014
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1111111
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4160
telemt_desync_full_logged_total 1474
telemt_desync_suppressed_total 2686
telemt_desync_frames_bucket_total{bucket="1_2"} 1245
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1536
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25734
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 25050
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 1110967
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 13721111148 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 382495436328 (356.23 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 37
```