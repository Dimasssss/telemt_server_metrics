# Server Metrics 2026-03-14 03:00:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 162090.7 (45h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4689926
telemt_connections_bad_total 39844
telemt_handshake_timeouts_total 108585
telemt_upstream_connect_attempt_total 34251
telemt_upstream_connect_success_total 34023
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 34251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 6729
telemt_me_reconnect_attempts_total 33745
telemt_me_reconnect_success_total 23604
telemt_me_reader_eof_total 25312
telemt_me_idle_close_by_peer_total 25311
telemt_me_route_drop_no_conn_total 1781844
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4301789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16769
telemt_desync_full_logged_total 4523
telemt_desync_suppressed_total 12246
telemt_desync_frames_bucket_total{bucket="1_2"} 4189
telemt_desync_frames_bucket_total{bucket="3_10"} 6396
telemt_desync_frames_bucket_total{bucket="gt_10"} 6184
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 24260
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23591
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 4303388
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 63071140424 (58.74 GB)
telemt_user_octets_to_client{user="hello"} 1359434233645 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61754.3 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703254
telemt_connections_bad_total 51007
telemt_handshake_timeouts_total 13169
telemt_upstream_connect_attempt_total 17229
telemt_upstream_connect_success_total 16976
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 17229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 2087
telemt_me_reconnect_attempts_total 15311
telemt_me_reconnect_success_total 11865
telemt_me_reader_eof_total 12592
telemt_me_idle_close_by_peer_total 12591
telemt_me_route_drop_no_conn_total 236046
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563516
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1691
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1222
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 739
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12132
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11857
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 565474
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 6024476573 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 182156998424 (169.65 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 191710.9 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3387666
telemt_connections_bad_total 35436
telemt_handshake_timeouts_total 223467
telemt_upstream_connect_attempt_total 43199
telemt_upstream_connect_success_total 43178
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10426
telemt_me_reconnect_attempts_total 38308
telemt_me_reconnect_success_total 33345
telemt_me_reader_eof_total 35410
telemt_me_idle_close_by_peer_total 35409
telemt_me_route_drop_no_conn_total 1160467
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2820170
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9358
telemt_desync_full_logged_total 3126
telemt_desync_suppressed_total 6232
telemt_desync_frames_bucket_total{bucket="1_2"} 1611
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4363
telemt_pool_swap_total 180
telemt_me_writer_removed_unexpected_total 33811
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33304
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2819394
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 45242875840 (42.14 GB)
telemt_user_octets_to_client{user="hello"} 1006358860133 (937.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 191713.5 (53h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2264949
telemt_connections_bad_total 22981
telemt_handshake_timeouts_total 248660
telemt_upstream_connect_attempt_total 60097
telemt_upstream_connect_success_total 57632
telemt_upstream_connect_fail_total 2328
telemt_upstream_connect_attempts_per_request{bucket="1"} 59823
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2327
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20430
telemt_me_reconnect_attempts_total 50120
telemt_me_reconnect_success_total 41086
telemt_me_reader_eof_total 44059
telemt_me_idle_close_by_peer_total 44052
telemt_me_route_drop_no_conn_total 773581
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1805227
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3811
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2584
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 41721
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41062
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 635
telemt_user_connections_total{user="hello"} 1811162
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 27626170771 (25.73 GB)
telemt_user_octets_to_client{user="hello"} 667899706458 (622.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61146.7 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703710
telemt_connections_bad_total 7951
telemt_handshake_timeouts_total 8671
telemt_upstream_connect_attempt_total 15790
telemt_upstream_connect_success_total 15365
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 15790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1512
telemt_me_reconnect_attempts_total 45637
telemt_me_reconnect_success_total 12321
telemt_me_reader_eof_total 13672
telemt_me_idle_close_by_peer_total 13671
telemt_me_route_drop_no_conn_total 267184
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13470
telemt_me_refill_failed_total 1037
telemt_me_writer_restored_same_endpoint_total 12316
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1149
telemt_user_connections_total{user="hello"} 655495
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 11979529444 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 213081431592 (198.45 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 24
```