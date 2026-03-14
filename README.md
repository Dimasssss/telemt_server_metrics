# Server Metrics 2026-03-14 03:35:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 164237.4 (45h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4716017
telemt_connections_bad_total 39884
telemt_handshake_timeouts_total 109096
telemt_upstream_connect_attempt_total 34734
telemt_upstream_connect_success_total 34504
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6736
telemt_me_reconnect_attempts_total 34129
telemt_me_reconnect_success_total 23987
telemt_me_reader_eof_total 25723
telemt_me_idle_close_by_peer_total 25722
telemt_me_route_drop_no_conn_total 1790564
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4325704
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16777
telemt_desync_full_logged_total 4525
telemt_desync_suppressed_total 12252
telemt_desync_frames_bucket_total{bucket="1_2"} 4193
telemt_desync_frames_bucket_total{bucket="3_10"} 6397
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 24646
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23974
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 4327282
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 63294648016 (58.95 GB)
telemt_user_octets_to_client{user="hello"} 1365269201517 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63901.0 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713739
telemt_connections_bad_total 51817
telemt_handshake_timeouts_total 13274
telemt_upstream_connect_attempt_total 17722
telemt_upstream_connect_success_total 17465
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2093
telemt_me_reconnect_attempts_total 15715
telemt_me_reconnect_success_total 12266
telemt_me_reader_eof_total 13022
telemt_me_idle_close_by_peer_total 13021
telemt_me_route_drop_no_conn_total 238805
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571820
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1705
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 749
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12541
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12258
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 573776
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 6119380753 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 190658510616 (177.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 193857.8 (53h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3402487
telemt_connections_bad_total 35708
telemt_handshake_timeouts_total 223865
telemt_upstream_connect_attempt_total 43791
telemt_upstream_connect_success_total 43770
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10432
telemt_me_reconnect_attempts_total 38771
telemt_me_reconnect_success_total 33805
telemt_me_reader_eof_total 35913
telemt_me_idle_close_by_peer_total 35912
telemt_me_route_drop_no_conn_total 1164535
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2833999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9369
telemt_desync_full_logged_total 3133
telemt_desync_suppressed_total 6236
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 3386
telemt_desync_frames_bucket_total{bucket="gt_10"} 4369
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 34278
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33764
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 2833220
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 45373786100 (42.26 GB)
telemt_user_octets_to_client{user="hello"} 1012279563957 (942.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 193860.4 (53h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2278700
telemt_connections_bad_total 23006
telemt_handshake_timeouts_total 251478
telemt_upstream_connect_attempt_total 60779
telemt_upstream_connect_success_total 58310
telemt_upstream_connect_fail_total 2332
telemt_upstream_connect_attempts_per_request{bucket="1"} 60505
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2331
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20444
telemt_me_reconnect_attempts_total 50668
telemt_me_reconnect_success_total 41633
telemt_me_reader_eof_total 44657
telemt_me_idle_close_by_peer_total 44650
telemt_me_route_drop_no_conn_total 775947
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1812394
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3832
telemt_desync_full_logged_total 1232
telemt_desync_suppressed_total 2600
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1216
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 42270
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41609
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 1818331
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 27665354775 (25.77 GB)
telemt_user_octets_to_client{user="hello"} 670189086494 (624.16 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63293.6 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712890
telemt_connections_bad_total 7954
telemt_handshake_timeouts_total 8693
telemt_upstream_connect_attempt_total 16478
telemt_upstream_connect_success_total 16034
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 16478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 50238
telemt_me_reconnect_success_total 12858
telemt_me_reader_eof_total 14337
telemt_me_idle_close_by_peer_total 14336
telemt_me_route_drop_no_conn_total 271407
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664609
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_me_writer_removed_unexpected_total 14135
telemt_me_refill_failed_total 1164
telemt_me_writer_restored_same_endpoint_total 12853
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1277
telemt_user_connections_total{user="hello"} 664487
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 12131563456 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 215669935488 (200.86 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 36
```