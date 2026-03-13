# Server Metrics 2026-03-13 22:29:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 145834.6 (40h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4530087
telemt_connections_bad_total 38370
telemt_handshake_timeouts_total 107067
telemt_upstream_connect_attempt_total 30411
telemt_upstream_connect_success_total 30203
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6640
telemt_me_reconnect_attempts_total 30734
telemt_me_reconnect_success_total 20613
telemt_me_reader_eof_total 22118
telemt_me_idle_close_by_peer_total 22117
telemt_me_route_drop_no_conn_total 1710268
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4150434
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16538
telemt_desync_full_logged_total 4447
telemt_desync_suppressed_total 12091
telemt_desync_frames_bucket_total{bucket="1_2"} 4117
telemt_desync_frames_bucket_total{bucket="3_10"} 6325
telemt_desync_frames_bucket_total{bucket="gt_10"} 6096
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 21228
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20600
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 4152565
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 61013566660 (56.82 GB)
telemt_user_octets_to_client{user="hello"} 1312082669201 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45498.3 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592688
telemt_connections_bad_total 42931
telemt_handshake_timeouts_total 12439
telemt_upstream_connect_attempt_total 12815
telemt_upstream_connect_success_total 12587
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 12814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1911
telemt_me_reconnect_attempts_total 11701
telemt_me_reconnect_success_total 8269
telemt_me_reader_eof_total 8764
telemt_me_idle_close_by_peer_total 8763
telemt_me_route_drop_no_conn_total 216274
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512801
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8497
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8261
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 514730
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 5581006921 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 167737290372 (156.22 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 175454.9 (48h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3291930
telemt_connections_bad_total 31802
telemt_handshake_timeouts_total 220090
telemt_upstream_connect_attempt_total 38869
telemt_upstream_connect_success_total 38848
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10290
telemt_me_reconnect_attempts_total 34759
telemt_me_reconnect_success_total 29807
telemt_me_reader_eof_total 31634
telemt_me_idle_close_by_peer_total 31633
telemt_me_route_drop_no_conn_total 1128187
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2733477
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8989
telemt_desync_full_logged_total 3025
telemt_desync_suppressed_total 5964
telemt_desync_frames_bucket_total{bucket="1_2"} 1511
telemt_desync_frames_bucket_total{bucket="3_10"} 3256
telemt_desync_frames_bucket_total{bucket="gt_10"} 4222
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 30248
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29766
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2732736
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 44615171900 (41.55 GB)
telemt_user_octets_to_client{user="hello"} 967055853797 (900.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 175457.7 (48h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2153005
telemt_connections_bad_total 22835
telemt_handshake_timeouts_total 219661
telemt_upstream_connect_attempt_total 54544
telemt_upstream_connect_success_total 52095
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54270
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20325
telemt_me_reconnect_attempts_total 45366
telemt_me_reconnect_success_total 36349
telemt_me_reader_eof_total 38996
telemt_me_idle_close_by_peer_total 38989
telemt_me_route_drop_no_conn_total 755051
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1756344
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3794
telemt_desync_full_logged_total 1215
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 36945
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36325
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1762226
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 27295046827 (25.42 GB)
telemt_user_octets_to_client{user="hello"} 658206147206 (613.00 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44890.9 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635727
telemt_connections_bad_total 6992
telemt_handshake_timeouts_total 6037
telemt_upstream_connect_attempt_total 10182
telemt_upstream_connect_success_total 9856
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 10182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 35981
telemt_me_reconnect_success_total 7610
telemt_me_reader_eof_total 8629
telemt_me_idle_close_by_peer_total 8628
telemt_me_route_drop_no_conn_total 241794
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594249
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8567
telemt_me_refill_failed_total 883
telemt_me_writer_restored_same_endpoint_total 7605
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 957
telemt_user_connections_total{user="hello"} 594157
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 8962395200 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 193055153556 (179.80 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 45
```