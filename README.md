# Server Metrics 2026-03-14 03:46:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 164851.0 (45h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4725225
telemt_connections_bad_total 39890
telemt_handshake_timeouts_total 109191
telemt_upstream_connect_attempt_total 34865
telemt_upstream_connect_success_total 34635
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6737
telemt_me_reconnect_attempts_total 34217
telemt_me_reconnect_success_total 24075
telemt_me_reader_eof_total 25814
telemt_me_idle_close_by_peer_total 25813
telemt_me_route_drop_no_conn_total 1793420
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4333741
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16794
telemt_desync_full_logged_total 4532
telemt_desync_suppressed_total 12262
telemt_desync_frames_bucket_total{bucket="1_2"} 4195
telemt_desync_frames_bucket_total{bucket="3_10"} 6406
telemt_desync_frames_bucket_total{bucket="gt_10"} 6193
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 24734
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24062
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 4335317
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 63511759612 (59.15 GB)
telemt_user_octets_to_client{user="hello"} 1367118241973 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64514.6 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716386
telemt_connections_bad_total 52058
telemt_handshake_timeouts_total 13295
telemt_upstream_connect_attempt_total 17907
telemt_upstream_connect_success_total 17650
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2096
telemt_me_reconnect_attempts_total 15855
telemt_me_reconnect_success_total 12405
telemt_me_reader_eof_total 13172
telemt_me_idle_close_by_peer_total 13171
telemt_me_route_drop_no_conn_total 239945
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574156
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 12683
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12397
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 576111
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 6133691465 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 191576042332 (178.42 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 194471.2 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3406659
telemt_connections_bad_total 35714
telemt_handshake_timeouts_total 223942
telemt_upstream_connect_attempt_total 43920
telemt_upstream_connect_success_total 43899
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10435
telemt_me_reconnect_attempts_total 38873
telemt_me_reconnect_success_total 33906
telemt_me_reader_eof_total 36014
telemt_me_idle_close_by_peer_total 36013
telemt_me_route_drop_no_conn_total 1165985
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2837992
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9391
telemt_desync_full_logged_total 3141
telemt_desync_suppressed_total 6250
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 3395
telemt_desync_frames_bucket_total{bucket="gt_10"} 4378
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 34379
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33865
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 2837213
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 45437134548 (42.32 GB)
telemt_user_octets_to_client{user="hello"} 1016634285005 (946.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 194473.9 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2282464
telemt_connections_bad_total 23011
telemt_handshake_timeouts_total 252693
telemt_upstream_connect_attempt_total 60936
telemt_upstream_connect_success_total 58467
telemt_upstream_connect_fail_total 2332
telemt_upstream_connect_attempts_per_request{bucket="1"} 60662
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2331
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20445
telemt_me_reconnect_attempts_total 50800
telemt_me_reconnect_success_total 41765
telemt_me_reader_eof_total 44789
telemt_me_idle_close_by_peer_total 44782
telemt_me_route_drop_no_conn_total 776598
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1814579
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3844
telemt_desync_full_logged_total 1235
telemt_desync_suppressed_total 2609
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1596
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 42402
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41741
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 1820519
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 27681356867 (25.78 GB)
telemt_user_octets_to_client{user="hello"} 671291643158 (625.19 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63907.4 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715726
telemt_connections_bad_total 7954
telemt_handshake_timeouts_total 8707
telemt_upstream_connect_attempt_total 16597
telemt_upstream_connect_success_total 16153
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 16597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 1524
telemt_me_reconnect_attempts_total 50357
telemt_me_reconnect_success_total 12977
telemt_me_reader_eof_total 14456
telemt_me_idle_close_by_peer_total 14455
telemt_me_route_drop_no_conn_total 272760
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667404
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14254
telemt_me_refill_failed_total 1164
telemt_me_writer_restored_same_endpoint_total 12972
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1277
telemt_user_connections_total{user="hello"} 667278
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 12171068552 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 216251059128 (201.40 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 46
```