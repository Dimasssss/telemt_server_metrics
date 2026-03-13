# Server Metrics 2026-03-13 17:02:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 126250.6 (35h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4015884
telemt_connections_bad_total 37515
telemt_handshake_timeouts_total 100067
telemt_upstream_connect_attempt_total 26883
telemt_upstream_connect_success_total 26706
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 26883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 5582
telemt_me_reconnect_attempts_total 28151
telemt_me_reconnect_success_total 18047
telemt_me_reader_eof_total 19388
telemt_me_idle_close_by_peer_total 19387
telemt_me_route_drop_no_conn_total 1490668
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3666521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14368
telemt_desync_full_logged_total 3796
telemt_desync_suppressed_total 10572
telemt_desync_frames_bucket_total{bucket="1_2"} 3584
telemt_desync_frames_bucket_total{bucket="3_10"} 5442
telemt_desync_frames_bucket_total{bucket="gt_10"} 5342
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18612
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18034
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 3668691
telemt_user_connections_current{user="hello"} 1834
telemt_user_octets_from_client{user="hello"} 51654489444 (48.11 GB)
telemt_user_octets_to_client{user="hello"} 1143533252485 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25914.1 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386893
telemt_connections_bad_total 28325
telemt_handshake_timeouts_total 10218
telemt_upstream_connect_attempt_total 7608
telemt_upstream_connect_success_total 7438
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 7608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 1565
telemt_me_reconnect_attempts_total 8093
telemt_me_reconnect_success_total 4700
telemt_me_reader_eof_total 4975
telemt_me_idle_close_by_peer_total 4974
telemt_me_route_drop_no_conn_total 141743
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337296
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1204
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 895
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4861
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4692
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 338636
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 3353637003 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 98417501576 (91.66 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 155871.0 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2939127
telemt_connections_bad_total 28320
telemt_handshake_timeouts_total 197016
telemt_upstream_connect_attempt_total 34834
telemt_upstream_connect_success_total 34824
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3376
telemt_me_reconnect_attempts_total 29272
telemt_me_reconnect_success_total 26718
telemt_me_reader_eof_total 28334
telemt_me_idle_close_by_peer_total 28333
telemt_me_route_drop_no_conn_total 999630
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2423587
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8444
telemt_desync_full_logged_total 2792
telemt_desync_suppressed_total 5652
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 3090
telemt_desync_frames_bucket_total{bucket="gt_10"} 3995
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27030
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26677
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 2422948
telemt_user_connections_current{user="hello"} 1168
telemt_user_octets_from_client{user="hello"} 39423309188 (36.72 GB)
telemt_user_octets_to_client{user="hello"} 846349146321 (788.22 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 155871.5 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1894125
telemt_connections_bad_total 18224
telemt_handshake_timeouts_total 172560
telemt_upstream_connect_attempt_total 48682
telemt_upstream_connect_success_total 46345
telemt_upstream_connect_fail_total 2200
telemt_upstream_connect_attempts_per_request{bucket="1"} 48408
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11924
telemt_me_reconnect_attempts_total 41696
telemt_me_reconnect_success_total 32715
telemt_me_reader_eof_total 35137
telemt_me_idle_close_by_peer_total 35130
telemt_me_route_drop_no_conn_total 673050
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1562032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3111
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 2102
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33255
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32691
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1566728
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 24225654461 (22.56 GB)
telemt_user_octets_to_client{user="hello"} 595125611358 (554.25 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25307.0 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413660
telemt_connections_bad_total 4343
telemt_handshake_timeouts_total 4071
telemt_upstream_connect_attempt_total 5714
telemt_upstream_connect_success_total 5536
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 5713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 15941
telemt_me_reconnect_success_total 4231
telemt_me_reader_eof_total 4688
telemt_me_idle_close_by_peer_total 4688
telemt_me_route_drop_no_conn_total 160047
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386486
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1246
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 852
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4628
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4227
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 386461
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 4442414368 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 122150836544 (113.76 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 118
```