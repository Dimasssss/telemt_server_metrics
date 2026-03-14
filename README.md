# Server Metrics 2026-03-14 07:56:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 179893.3 (49h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5081504
telemt_connections_bad_total 40904
telemt_handshake_timeouts_total 115839
telemt_upstream_connect_attempt_total 37847
telemt_upstream_connect_success_total 37602
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 37847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 7369
telemt_me_reconnect_attempts_total 37547
telemt_me_reconnect_success_total 26337
telemt_me_reader_eof_total 28264
telemt_me_idle_close_by_peer_total 28263
telemt_me_route_drop_no_conn_total 1922428
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4659055
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17741
telemt_desync_full_logged_total 4825
telemt_desync_suppressed_total 12916
telemt_desync_frames_bucket_total{bucket="1_2"} 4417
telemt_desync_frames_bucket_total{bucket="3_10"} 6738
telemt_desync_frames_bucket_total{bucket="gt_10"} 6586
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 27069
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26324
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 4660514
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 71443647440 (66.54 GB)
telemt_user_octets_to_client{user="hello"} 1490803907053 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79557.7 (22h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869959
telemt_connections_bad_total 53909
telemt_handshake_timeouts_total 15973
telemt_upstream_connect_attempt_total 21382
telemt_upstream_connect_success_total 21105
telemt_upstream_connect_fail_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 21382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 277
telemt_me_keepalive_timeout_total 2148
telemt_me_reconnect_attempts_total 18578
telemt_me_reconnect_success_total 15109
telemt_me_reader_eof_total 16056
telemt_me_idle_close_by_peer_total 16055
telemt_me_route_drop_no_conn_total 287657
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699514
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2096
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1443
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 921
telemt_desync_frames_bucket_total{bucket="gt_10"} 735
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15435
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15101
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 701423
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 7340697713 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 242427110052 (225.78 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 209514.1 (58h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3633478
telemt_connections_bad_total 42671
telemt_handshake_timeouts_total 238649
telemt_upstream_connect_attempt_total 47345
telemt_upstream_connect_success_total 47324
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10722
telemt_me_reconnect_attempts_total 41582
telemt_me_reconnect_success_total 36601
telemt_me_reader_eof_total 38858
telemt_me_idle_close_by_peer_total 38857
telemt_me_route_drop_no_conn_total 1244492
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3032293
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9979
telemt_desync_full_logged_total 3362
telemt_desync_suppressed_total 6617
telemt_desync_frames_bucket_total{bucket="1_2"} 1756
telemt_desync_frames_bucket_total{bucket="3_10"} 3612
telemt_desync_frames_bucket_total{bucket="gt_10"} 4611
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 37108
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36560
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 3031431
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 51018734912 (47.51 GB)
telemt_user_octets_to_client{user="hello"} 1085006180873 (1010.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 209516.4 (58h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2418065
telemt_connections_bad_total 23316
telemt_handshake_timeouts_total 292621
telemt_upstream_connect_attempt_total 65256
telemt_upstream_connect_success_total 62763
telemt_upstream_connect_fail_total 2356
telemt_upstream_connect_attempts_per_request{bucket="1"} 64982
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2355
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20544
telemt_me_reconnect_attempts_total 54413
telemt_me_reconnect_success_total 45331
telemt_me_reader_eof_total 48574
telemt_me_idle_close_by_peer_total 48567
telemt_me_route_drop_no_conn_total 812560
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1902945
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3930
telemt_desync_full_logged_total 1280
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1081
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 185
telemt_me_writer_removed_unexpected_total 46004
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45307
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1909052
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 28626328627 (26.66 GB)
telemt_user_octets_to_client{user="hello"} 696796390558 (648.94 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78949.8 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845162
telemt_connections_bad_total 8439
telemt_handshake_timeouts_total 9983
telemt_upstream_connect_attempt_total 20097
telemt_upstream_connect_success_total 19560
telemt_upstream_connect_fail_total 537
telemt_upstream_connect_attempts_per_request{bucket="1"} 20097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 537
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 64813
telemt_me_reconnect_success_total 15632
telemt_me_reader_eof_total 17541
telemt_me_idle_close_by_peer_total 17540
telemt_me_route_drop_no_conn_total 324952
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789638
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1974
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1346
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 749
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17303
telemt_me_refill_failed_total 1532
telemt_me_writer_restored_same_endpoint_total 15627
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1671
telemt_user_connections_total{user="hello"} 789496
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 14056407356 (13.09 GB)
telemt_user_octets_to_client{user="hello"} 265429005924 (247.20 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 86
```