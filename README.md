# Server Metrics 2026-03-13 00:37:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67115.5 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2001954
telemt_connections_bad_total 26109
telemt_handshake_timeouts_total 21428
telemt_upstream_connect_attempt_total 13339
telemt_upstream_connect_success_total 13263
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1244
telemt_me_reconnect_attempts_total 18757
telemt_me_reconnect_success_total 9898
telemt_me_reader_eof_total 10707
telemt_me_idle_close_by_peer_total 10706
telemt_me_route_drop_no_conn_total 781778
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1862395
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8668
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 3256
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10314
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9885
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 1861853
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 27508505792 (25.62 GB)
telemt_user_octets_to_client{user="hello"} 655104932588 (610.11 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96736.1 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825072
telemt_connections_bad_total 11755
telemt_handshake_timeouts_total 31815
telemt_upstream_connect_attempt_total 24618
telemt_upstream_connect_success_total 24589
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3437
telemt_me_reconnect_attempts_total 18215
telemt_me_reconnect_success_total 18115
telemt_me_reader_eof_total 19287
telemt_me_idle_close_by_peer_total 19287
telemt_me_route_drop_no_conn_total 267356
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3051
telemt_desync_full_logged_total 956
telemt_desync_suppressed_total 2095
telemt_desync_frames_bucket_total{bucket="1_2"} 1232
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18291
telemt_me_writer_restored_same_endpoint_total 18106
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 748970
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 12196520864 (11.36 GB)
telemt_user_octets_to_client{user="hello"} 285377903483 (265.78 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96736.0 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1717139
telemt_connections_bad_total 8778
telemt_handshake_timeouts_total 113677
telemt_upstream_connect_attempt_total 22488
telemt_upstream_connect_success_total 22478
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1576
telemt_me_reconnect_attempts_total 18553
telemt_me_reconnect_success_total 17292
telemt_me_reader_eof_total 18314
telemt_me_idle_close_by_peer_total 18313
telemt_me_route_drop_no_conn_total 564230
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1348166
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4979
telemt_desync_full_logged_total 1528
telemt_desync_suppressed_total 3451
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1801
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17459
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17251
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 1347769
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 19956166876 (18.59 GB)
telemt_user_octets_to_client{user="hello"} 489936022725 (456.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96736.0 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074045
telemt_connections_bad_total 13050
telemt_handshake_timeouts_total 71925
telemt_upstream_connect_attempt_total 33807
telemt_upstream_connect_success_total 31544
telemt_upstream_connect_fail_total 2126
telemt_upstream_connect_attempts_per_request{bucket="1"} 33533
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2125
telemt_me_keepalive_timeout_total 11265
telemt_me_reconnect_attempts_total 28693
telemt_me_reconnect_success_total 20853
telemt_me_reader_eof_total 22574
telemt_me_idle_close_by_peer_total 22567
telemt_me_route_drop_no_conn_total 379879
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921975
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
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21226
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20831
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 927167
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 14399164425 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 367015106246 (341.81 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96736.2 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184872
telemt_connections_bad_total 12579
telemt_handshake_timeouts_total 9315
telemt_upstream_connect_attempt_total 29272
telemt_upstream_connect_success_total 28907
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 29272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 1829
telemt_me_reconnect_attempts_total 35118
telemt_me_reconnect_success_total 24074
telemt_me_reader_eof_total 25352
telemt_me_idle_close_by_peer_total 25352
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 444550
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1093733
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4108
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 2660
telemt_desync_frames_bucket_total{bucket="1_2"} 1213
telemt_desync_frames_bucket_total{bucket="3_10"} 1371
telemt_desync_frames_bucket_total{bucket="gt_10"} 1524
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24697
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24028
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 1093590
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 13644302356 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 380917074772 (354.76 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 54
```