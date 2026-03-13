# Server Metrics 2026-03-13 13:13:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 112469.7 (31h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3386230
telemt_connections_bad_total 37364
telemt_handshake_timeouts_total 58454
telemt_upstream_connect_attempt_total 22080
telemt_upstream_connect_success_total 21957
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2109
telemt_me_reconnect_attempts_total 26458
telemt_me_reconnect_success_total 16374
telemt_me_reader_eof_total 17602
telemt_me_idle_close_by_peer_total 17601
telemt_me_route_drop_no_conn_total 1255402
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3104679
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12960
telemt_desync_full_logged_total 3382
telemt_desync_suppressed_total 9578
telemt_desync_frames_bucket_total{bucket="1_2"} 3286
telemt_desync_frames_bucket_total{bucket="3_10"} 4905
telemt_desync_frames_bucket_total{bucket="gt_10"} 4769
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16919
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16361
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3104572
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 42855862692 (39.91 GB)
telemt_user_octets_to_client{user="hello"} 997551991420 (929.04 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12133.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166261
telemt_connections_bad_total 9462
telemt_handshake_timeouts_total 4048
telemt_upstream_connect_attempt_total 2956
telemt_upstream_connect_success_total 2881
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 2956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 3450
telemt_me_reconnect_success_total 2221
telemt_me_reader_eof_total 2337
telemt_me_idle_close_by_peer_total 2337
telemt_me_route_drop_no_conn_total 60134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148768
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 582
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2276
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2214
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 148793
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 1499662744 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 40567551920 (37.78 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 142090.3 (39h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2551769
telemt_connections_bad_total 26712
telemt_handshake_timeouts_total 168813
telemt_upstream_connect_attempt_total 32238
telemt_upstream_connect_success_total 32228
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3193
telemt_me_reconnect_attempts_total 27370
telemt_me_reconnect_success_total 24824
telemt_me_reader_eof_total 26317
telemt_me_idle_close_by_peer_total 26316
telemt_me_route_drop_no_conn_total 855539
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077100
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7122
telemt_desync_full_logged_total 2319
telemt_desync_suppressed_total 4803
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 2601
telemt_desync_frames_bucket_total{bucket="gt_10"} 3390
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 25112
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24783
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 2076523
telemt_user_connections_current{user="hello"} 1142
telemt_user_octets_from_client{user="hello"} 34809388288 (32.42 GB)
telemt_user_octets_to_client{user="hello"} 747195800373 (695.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 142090.9 (39h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1627007
telemt_connections_bad_total 17881
telemt_handshake_timeouts_total 114644
telemt_upstream_connect_attempt_total 45589
telemt_upstream_connect_success_total 43269
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45315
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11830
telemt_me_reconnect_attempts_total 39318
telemt_me_reconnect_success_total 30352
telemt_me_reader_eof_total 32636
telemt_me_idle_close_by_peer_total 32629
telemt_me_route_drop_no_conn_total 579285
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1358939
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2728
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1842
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 872
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 30856
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30328
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1363660
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 20656274237 (19.24 GB)
telemt_user_octets_to_client{user="hello"} 531545480398 (495.04 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11526.4 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178738
telemt_connections_bad_total 3839
telemt_handshake_timeouts_total 1595
telemt_upstream_connect_attempt_total 2312
telemt_upstream_connect_success_total 2236
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 2312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 9701
telemt_me_reconnect_success_total 1627
telemt_me_reader_eof_total 1880
telemt_me_idle_close_by_peer_total 1880
telemt_me_route_drop_no_conn_total 68753
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167037
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1875
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1623
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 167021
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 1839391056 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 52665803408 (49.05 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 129
```