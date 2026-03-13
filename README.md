# Server Metrics 2026-03-13 09:02:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97417.2 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755415
telemt_connections_bad_total 36379
telemt_handshake_timeouts_total 37436
telemt_upstream_connect_attempt_total 19123
telemt_upstream_connect_success_total 19018
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 19123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1371
telemt_me_reconnect_attempts_total 24225
telemt_me_reconnect_success_total 14165
telemt_me_reader_eof_total 15271
telemt_me_idle_close_by_peer_total 15270
telemt_me_route_drop_no_conn_total 1022660
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2518167
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11220
telemt_desync_full_logged_total 2898
telemt_desync_suppressed_total 8322
telemt_desync_frames_bucket_total{bucket="1_2"} 2883
telemt_desync_frames_bucket_total{bucket="3_10"} 4197
telemt_desync_frames_bucket_total{bucket="gt_10"} 4140
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14675
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14152
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 2517735
telemt_user_connections_current{user="hello"} 1848
telemt_user_octets_from_client{user="hello"} 35343364684 (32.92 GB)
telemt_user_octets_to_client{user="hello"} 828171754868 (771.30 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 127037.8 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127445
telemt_connections_bad_total 14093
telemt_handshake_timeouts_total 100832
telemt_upstream_connect_attempt_total 31602
telemt_upstream_connect_success_total 31571
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23725
telemt_me_reconnect_success_total 23601
telemt_me_reader_eof_total 25158
telemt_me_idle_close_by_peer_total 25158
telemt_me_route_drop_no_conn_total 345066
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971217
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4315
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 3003
telemt_desync_frames_bucket_total{bucket="1_2"} 1576
telemt_desync_frames_bucket_total{bucket="3_10"} 1421
telemt_desync_frames_bucket_total{bucket="gt_10"} 1318
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 23833
telemt_me_writer_restored_same_endpoint_total 23592
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 973143
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 14864611636 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 358678911719 (334.05 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 127037.8 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2177326
telemt_connections_bad_total 24436
telemt_handshake_timeouts_total 145102
telemt_upstream_connect_attempt_total 29180
telemt_upstream_connect_success_total 29170
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1764
telemt_me_reconnect_attempts_total 23766
telemt_me_reconnect_success_total 22483
telemt_me_reader_eof_total 23812
telemt_me_idle_close_by_peer_total 23811
telemt_me_route_drop_no_conn_total 706554
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1737754
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5793
telemt_desync_full_logged_total 1841
telemt_desync_suppressed_total 3952
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 2114
telemt_desync_frames_bucket_total{bucket="gt_10"} 2732
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22705
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22442
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 1737192
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 30438325456 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 630323238665 (587.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 127038.2 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1381928
telemt_connections_bad_total 14224
telemt_handshake_timeouts_total 84821
telemt_upstream_connect_attempt_total 42141
telemt_upstream_connect_success_total 39837
telemt_upstream_connect_fail_total 2167
telemt_upstream_connect_attempts_per_request{bucket="1"} 41867
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2166
telemt_me_keepalive_timeout_total 11454
telemt_me_reconnect_attempts_total 36584
telemt_me_reconnect_success_total 27644
telemt_me_reader_eof_total 29768
telemt_me_idle_close_by_peer_total 29761
telemt_me_route_drop_no_conn_total 485296
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151027
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2197
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28119
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27620
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 1155790
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 17381230045 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 459230294086 (427.69 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 127037.7 (35h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532075
telemt_connections_bad_total 33085
telemt_handshake_timeouts_total 12608
telemt_upstream_connect_attempt_total 40446
telemt_upstream_connect_success_total 39958
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 40446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 2168
telemt_me_reconnect_attempts_total 47369
telemt_me_reconnect_success_total 33622
telemt_me_reader_eof_total 35236
telemt_me_idle_close_by_peer_total 35236
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 560537
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401449
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4902
telemt_desync_full_logged_total 1753
telemt_desync_suppressed_total 3149
telemt_desync_frames_bucket_total{bucket="1_2"} 1496
telemt_desync_frames_bucket_total{bucket="3_10"} 1583
telemt_desync_frames_bucket_total{bucket="gt_10"} 1823
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34420
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 33561
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1401252
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 18127765292 (16.88 GB)
telemt_user_octets_to_client{user="hello"} 486783129552 (453.35 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 122
```