# Server Metrics 2026-03-12 20:52:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53647.7 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1826048
telemt_connections_bad_total 20726
telemt_handshake_timeouts_total 20065
telemt_upstream_connect_attempt_total 10440
telemt_upstream_connect_success_total 10379
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 16520
telemt_me_reconnect_success_total 7670
telemt_me_reader_eof_total 8295
telemt_me_idle_close_by_peer_total 8294
telemt_me_route_drop_no_conn_total 717952
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1704531
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8324
telemt_desync_full_logged_total 2151
telemt_desync_suppressed_total 6173
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 3004
telemt_desync_frames_bucket_total{bucket="gt_10"} 3138
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8057
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7657
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 1704014
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 26206143612 (24.41 GB)
telemt_user_octets_to_client{user="hello"} 597700126888 (556.65 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83268.3 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766825
telemt_connections_bad_total 11393
telemt_handshake_timeouts_total 30480
telemt_upstream_connect_attempt_total 21065
telemt_upstream_connect_success_total 21036
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3388
telemt_me_reconnect_attempts_total 15310
telemt_me_reconnect_success_total 15219
telemt_me_reader_eof_total 16185
telemt_me_idle_close_by_peer_total 16185
telemt_me_route_drop_no_conn_total 247373
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2945
telemt_desync_full_logged_total 903
telemt_desync_suppressed_total 2042
telemt_desync_frames_bucket_total{bucket="1_2"} 1146
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15374
telemt_me_writer_restored_same_endpoint_total 15210
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 693586
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 11824724844 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 266256091135 (247.97 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83268.2 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1584522
telemt_connections_bad_total 7545
telemt_handshake_timeouts_total 108779
telemt_upstream_connect_attempt_total 19537
telemt_upstream_connect_success_total 19531
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1208
telemt_me_reconnect_attempts_total 16250
telemt_me_reconnect_success_total 15003
telemt_me_reader_eof_total 15838
telemt_me_idle_close_by_peer_total 15837
telemt_me_route_drop_no_conn_total 523409
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1224122
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4848
telemt_desync_full_logged_total 1490
telemt_desync_suppressed_total 3358
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1752
telemt_desync_frames_bucket_total{bucket="gt_10"} 2326
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15144
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14962
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1223729
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 19228862700 (17.91 GB)
telemt_user_octets_to_client{user="hello"} 456705739349 (425.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83268.8 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974057
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70806
telemt_upstream_connect_attempt_total 21260
telemt_upstream_connect_success_total 21174
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 21260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1673
telemt_me_reconnect_attempts_total 24737
telemt_me_reconnect_success_total 17010
telemt_me_reader_eof_total 18172
telemt_me_idle_close_by_peer_total 18172
telemt_me_route_drop_no_conn_total 347751
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1815
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1213
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17387
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16989
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 845831
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 13248602712 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 345095507412 (321.40 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83268.4 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1092719
telemt_connections_bad_total 12502
telemt_handshake_timeouts_total 9007
telemt_upstream_connect_attempt_total 25795
telemt_upstream_connect_success_total 25480
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 25795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 32337
telemt_me_reconnect_success_total 21299
telemt_me_reader_eof_total 22384
telemt_me_idle_close_by_peer_total 22384
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 408750
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003371
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3783
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 2463
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 1251
telemt_desync_frames_bucket_total{bucket="gt_10"} 1439
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 21886
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21255
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 1003234
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 12460287780 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 353558623052 (329.28 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 52
```