# Server Metrics 2026-03-13 06:18:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87617.4 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2360351
telemt_connections_bad_total 35906
telemt_handshake_timeouts_total 24977
telemt_upstream_connect_attempt_total 17221
telemt_upstream_connect_success_total 17125
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1322
telemt_me_reconnect_attempts_total 21625
telemt_me_reconnect_success_total 12756
telemt_me_reader_eof_total 13763
telemt_me_idle_close_by_peer_total 13762
telemt_me_route_drop_no_conn_total 895871
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2172060
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9710
telemt_desync_full_logged_total 2506
telemt_desync_suppressed_total 7204
telemt_desync_frames_bucket_total{bucket="1_2"} 2516
telemt_desync_frames_bucket_total{bucket="3_10"} 3564
telemt_desync_frames_bucket_total{bucket="gt_10"} 3630
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 13210
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12743
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2171450
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 31389566296 (29.23 GB)
telemt_user_octets_to_client{user="hello"} 739858472068 (689.05 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 117237.9 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953236
telemt_connections_bad_total 12486
telemt_handshake_timeouts_total 41082
telemt_upstream_connect_attempt_total 29566
telemt_upstream_connect_success_total 29535
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3574
telemt_me_reconnect_attempts_total 22170
telemt_me_reconnect_success_total 22051
telemt_me_reader_eof_total 23517
telemt_me_idle_close_by_peer_total 23517
telemt_me_route_drop_no_conn_total 303418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860908
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3515
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 2412
telemt_desync_frames_bucket_total{bucket="1_2"} 1367
telemt_desync_frames_bucket_total{bucket="3_10"} 1138
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 22271
telemt_me_writer_restored_same_endpoint_total 22042
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 862817
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 13570005412 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 328946162339 (306.35 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 117237.8 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1968822
telemt_connections_bad_total 22773
telemt_handshake_timeouts_total 131828
telemt_upstream_connect_attempt_total 27168
telemt_upstream_connect_success_total 27158
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1682
telemt_me_reconnect_attempts_total 22235
telemt_me_reconnect_success_total 20963
telemt_me_reader_eof_total 22209
telemt_me_idle_close_by_peer_total 22208
telemt_me_route_drop_no_conn_total 629964
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1550070
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5353
telemt_desync_full_logged_total 1625
telemt_desync_suppressed_total 3728
telemt_desync_frames_bucket_total{bucket="1_2"} 885
telemt_desync_frames_bucket_total{bucket="3_10"} 1947
telemt_desync_frames_bucket_total{bucket="gt_10"} 2521
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 21165
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20922
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1549567
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 26462283712 (24.64 GB)
telemt_user_octets_to_client{user="hello"} 551317519909 (513.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 117238.1 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201615
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 78002
telemt_upstream_connect_attempt_total 39944
telemt_upstream_connect_success_total 37656
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39670
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11409
telemt_me_reconnect_attempts_total 34882
telemt_me_reconnect_success_total 25947
telemt_me_reader_eof_total 27975
telemt_me_idle_close_by_peer_total 27968
telemt_me_route_drop_no_conn_total 430123
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032313
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2051
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 26403
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25923
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 1037234
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 15726039773 (14.65 GB)
telemt_user_octets_to_client{user="hello"} 414090765986 (385.65 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 117238.0 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1353790
telemt_connections_bad_total 17966
telemt_handshake_timeouts_total 11101
telemt_upstream_connect_attempt_total 37181
telemt_upstream_connect_success_total 36730
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 37181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2028
telemt_me_reconnect_attempts_total 44623
telemt_me_reconnect_success_total 30886
telemt_me_reader_eof_total 32438
telemt_me_idle_close_by_peer_total 32438
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 498114
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1249571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4479
telemt_desync_full_logged_total 1611
telemt_desync_suppressed_total 2868
telemt_desync_frames_bucket_total{bucket="1_2"} 1360
telemt_desync_frames_bucket_total{bucket="3_10"} 1453
telemt_desync_frames_bucket_total{bucket="gt_10"} 1666
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31655
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30832
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1249413
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 15078360144 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 429316421704 (399.83 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 86
```