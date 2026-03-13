# Server Metrics 2026-03-13 03:05:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75984.6 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2118269
telemt_connections_bad_total 27999
telemt_handshake_timeouts_total 22769
telemt_upstream_connect_attempt_total 15069
telemt_upstream_connect_success_total 14985
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1289
telemt_me_reconnect_attempts_total 20047
telemt_me_reconnect_success_total 11185
telemt_me_reader_eof_total 12082
telemt_me_idle_close_by_peer_total 12081
telemt_me_route_drop_no_conn_total 814290
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1949802
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8751
telemt_desync_full_logged_total 2276
telemt_desync_suppressed_total 6475
telemt_desync_frames_bucket_total{bucket="1_2"} 2305
telemt_desync_frames_bucket_total{bucket="3_10"} 3156
telemt_desync_frames_bucket_total{bucket="gt_10"} 3290
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11617
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11172
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 1949257
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 28394574200 (26.44 GB)
telemt_user_octets_to_client{user="hello"} 676044099852 (629.62 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105605.0 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862776
telemt_connections_bad_total 11830
telemt_handshake_timeouts_total 34948
telemt_upstream_connect_attempt_total 26939
telemt_upstream_connect_success_total 26910
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3458
telemt_me_reconnect_attempts_total 20104
telemt_me_reconnect_success_total 19994
telemt_me_reader_eof_total 21309
telemt_me_idle_close_by_peer_total 21309
telemt_me_route_drop_no_conn_total 277056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780596
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3102
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2127
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20189
telemt_me_writer_restored_same_endpoint_total 19985
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 782498
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 12450392588 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 297499574399 (277.07 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105604.9 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1788508
telemt_connections_bad_total 9330
telemt_handshake_timeouts_total 119854
telemt_upstream_connect_attempt_total 24639
telemt_upstream_connect_success_total 24629
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1615
telemt_me_reconnect_attempts_total 20270
telemt_me_reconnect_success_total 19005
telemt_me_reader_eof_total 20134
telemt_me_idle_close_by_peer_total 20133
telemt_me_route_drop_no_conn_total 582047
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1409301
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5034
telemt_desync_full_logged_total 1541
telemt_desync_suppressed_total 3493
telemt_desync_frames_bucket_total{bucket="1_2"} 805
telemt_desync_frames_bucket_total{bucket="3_10"} 1824
telemt_desync_frames_bucket_total{bucket="gt_10"} 2405
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19184
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18964
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1408895
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 20324080320 (18.93 GB)
telemt_user_octets_to_client{user="hello"} 506082540873 (471.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105605.3 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115740
telemt_connections_bad_total 13141
telemt_handshake_timeouts_total 73972
telemt_upstream_connect_attempt_total 36864
telemt_upstream_connect_success_total 34587
telemt_upstream_connect_fail_total 2140
telemt_upstream_connect_attempts_per_request{bucket="1"} 36590
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2139
telemt_me_keepalive_timeout_total 11366
telemt_me_reconnect_attempts_total 32376
telemt_me_reconnect_success_total 23451
telemt_me_reader_eof_total 25324
telemt_me_idle_close_by_peer_total 25317
telemt_me_route_drop_no_conn_total 395327
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956947
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 23882
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23427
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 962117
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 14634141061 (13.63 GB)
telemt_user_octets_to_client{user="hello"} 377193632586 (351.29 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 105605.0 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1234542
telemt_connections_bad_total 12634
telemt_handshake_timeouts_total 9588
telemt_upstream_connect_attempt_total 33310
telemt_upstream_connect_success_total 32903
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 33310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 1901
telemt_me_reconnect_attempts_total 41363
telemt_me_reconnect_success_total 27633
telemt_me_reader_eof_total 29082
telemt_me_idle_close_by_peer_total 29082
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 460753
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1142138
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4243
telemt_desync_full_logged_total 1510
telemt_desync_suppressed_total 2733
telemt_desync_frames_bucket_total{bucket="1_2"} 1280
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1568
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 28379
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27584
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 1141990
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 14128820712 (13.16 GB)
telemt_user_octets_to_client{user="hello"} 394912950816 (367.79 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 42
```