# Server Metrics 2026-03-10 18:03:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13012.4 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433079
telemt_connections_bad_total 7976
telemt_handshake_timeouts_total 2012
telemt_upstream_connect_attempt_total 2547
telemt_upstream_connect_success_total 2538
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 11090
telemt_me_reconnect_success_total 1823
telemt_me_reader_eof_total 2091
telemt_me_idle_close_by_peer_total 2091
telemt_me_route_drop_no_conn_total 182781
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410178
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2117
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1817
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 410099
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 5390313864 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 119997369488 (111.76 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13069.1 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167581
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 11014
telemt_upstream_connect_attempt_total 2975
telemt_upstream_connect_success_total 2960
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2279
telemt_me_reconnect_success_total 2264
telemt_me_reader_eof_total 2349
telemt_me_idle_close_by_peer_total 2349
telemt_me_route_drop_no_conn_total 49691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146116
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 463
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2280
telemt_me_writer_restored_same_endpoint_total 2243
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 146105
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 1827817136 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 39170235724 (36.48 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13068.9 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319924
telemt_connections_bad_total 967
telemt_handshake_timeouts_total 31314
telemt_upstream_connect_attempt_total 4284
telemt_upstream_connect_success_total 4218
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3666
telemt_me_reconnect_success_total 2471
telemt_me_reader_eof_total 2590
telemt_me_idle_close_by_peer_total 2590
telemt_me_route_drop_no_conn_total 104900
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264315
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 842
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2545
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2460
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 265278
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 3575031657 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 82135680277 (76.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13069.4 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207014
telemt_connections_bad_total 12690
telemt_handshake_timeouts_total 19577
telemt_upstream_connect_attempt_total 3407
telemt_upstream_connect_success_total 3407
telemt_upstream_connect_attempts_per_request{bucket="1"} 3407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1590
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 2724
telemt_me_reconnect_success_total 2708
telemt_me_reader_eof_total 2812
telemt_me_idle_close_by_peer_total 2812
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 67363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166230
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 493
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2731
telemt_me_writer_restored_same_endpoint_total 2696
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 166043
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 2663359008 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 46627459172 (43.43 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13069.3 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219139
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 3934
telemt_upstream_connect_success_total 3922
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 3227
telemt_me_reconnect_success_total 3207
telemt_me_reader_eof_total 3292
telemt_me_idle_close_by_peer_total 3292
telemt_me_route_drop_no_conn_total 80453
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206284
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1118
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 726
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3239
telemt_me_writer_restored_same_endpoint_total 3207
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 206219
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 4542057292 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 61281800048 (57.07 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 101
```