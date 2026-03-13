# Server Metrics 2026-03-13 06:13:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87311.4 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2351461
telemt_connections_bad_total 35906
telemt_handshake_timeouts_total 24808
telemt_upstream_connect_attempt_total 17125
telemt_upstream_connect_success_total 17030
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1319
telemt_me_reconnect_attempts_total 21573
telemt_me_reconnect_success_total 12704
telemt_me_reader_eof_total 13702
telemt_me_idle_close_by_peer_total 13701
telemt_me_route_drop_no_conn_total 893016
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2163587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9675
telemt_desync_full_logged_total 2493
telemt_desync_suppressed_total 7182
telemt_desync_frames_bucket_total{bucket="1_2"} 2508
telemt_desync_frames_bucket_total{bucket="3_10"} 3548
telemt_desync_frames_bucket_total{bucket="gt_10"} 3619
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13156
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12691
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2162978
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 31240939168 (29.10 GB)
telemt_user_octets_to_client{user="hello"} 738087347828 (687.40 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 116931.9 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950080
telemt_connections_bad_total 12475
telemt_handshake_timeouts_total 40982
telemt_upstream_connect_attempt_total 29472
telemt_upstream_connect_success_total 29441
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3573
telemt_me_reconnect_attempts_total 22119
telemt_me_reconnect_success_total 22000
telemt_me_reader_eof_total 23457
telemt_me_idle_close_by_peer_total 23457
telemt_me_route_drop_no_conn_total 302294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3494
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2394
telemt_desync_frames_bucket_total{bucket="1_2"} 1362
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1003
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22220
telemt_me_writer_restored_same_endpoint_total 21991
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 859843
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 13545534772 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 328332639971 (305.78 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 116931.8 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1963376
telemt_connections_bad_total 22773
telemt_handshake_timeouts_total 131048
telemt_upstream_connect_attempt_total 27079
telemt_upstream_connect_success_total 27069
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1682
telemt_me_reconnect_attempts_total 22190
telemt_me_reconnect_success_total 20918
telemt_me_reader_eof_total 22160
telemt_me_idle_close_by_peer_total 22159
telemt_me_route_drop_no_conn_total 628360
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1545525
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5343
telemt_desync_full_logged_total 1620
telemt_desync_suppressed_total 3723
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1941
telemt_desync_frames_bucket_total{bucket="gt_10"} 2519
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 21120
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20877
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1545022
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 26424728360 (24.61 GB)
telemt_user_octets_to_client{user="hello"} 549258002625 (511.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 116932.2 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1196379
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 77916
telemt_upstream_connect_attempt_total 39822
telemt_upstream_connect_success_total 37534
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39548
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11408
telemt_me_reconnect_attempts_total 34803
telemt_me_reconnect_success_total 25868
telemt_me_reader_eof_total 27879
telemt_me_idle_close_by_peer_total 27872
telemt_me_route_drop_no_conn_total 428868
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029315
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2034
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1372
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 787
telemt_desync_frames_bucket_total{bucket="gt_10"} 689
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 26324
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25844
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 1034237
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 15691740093 (14.61 GB)
telemt_user_octets_to_client{user="hello"} 413008012802 (384.64 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 116932.0 (32h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1349282
telemt_connections_bad_total 17497
telemt_handshake_timeouts_total 11070
telemt_upstream_connect_attempt_total 37050
telemt_upstream_connect_success_total 36603
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 37050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 2027
telemt_me_reconnect_attempts_total 44539
telemt_me_reconnect_success_total 30802
telemt_me_reader_eof_total 32332
telemt_me_idle_close_by_peer_total 32332
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 496719
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245679
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4461
telemt_desync_full_logged_total 1608
telemt_desync_suppressed_total 2853
telemt_desync_frames_bucket_total{bucket="1_2"} 1358
telemt_desync_frames_bucket_total{bucket="3_10"} 1448
telemt_desync_frames_bucket_total{bucket="gt_10"} 1655
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31571
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30748
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1245521
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 15004635872 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 426888247340 (397.57 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 97
```