# Server Metrics 2026-03-13 17:58:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 129616.4 (36h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4137286
telemt_connections_bad_total 37530
telemt_handshake_timeouts_total 101748
telemt_upstream_connect_attempt_total 27388
telemt_upstream_connect_success_total 27209
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5753
telemt_me_reconnect_attempts_total 28523
telemt_me_reconnect_success_total 18417
telemt_me_reader_eof_total 19784
telemt_me_idle_close_by_peer_total 19783
telemt_me_route_drop_no_conn_total 1541046
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3779318
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14770
telemt_desync_full_logged_total 3933
telemt_desync_suppressed_total 10837
telemt_desync_frames_bucket_total{bucket="1_2"} 3659
telemt_desync_frames_bucket_total{bucket="3_10"} 5607
telemt_desync_frames_bucket_total{bucket="gt_10"} 5504
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 18993
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18404
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 3781482
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 53175386384 (49.52 GB)
telemt_user_octets_to_client{user="hello"} 1173786315573 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29280.2 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437233
telemt_connections_bad_total 33430
telemt_handshake_timeouts_total 10511
telemt_upstream_connect_attempt_total 8348
telemt_upstream_connect_success_total 8171
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1602
telemt_me_reconnect_attempts_total 8654
telemt_me_reconnect_success_total 5256
telemt_me_reader_eof_total 5566
telemt_me_idle_close_by_peer_total 5565
telemt_me_route_drop_no_conn_total 164285
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380802
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 973
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 437
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5429
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5248
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 382138
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 3926115751 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 117132763992 (109.09 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 159236.9 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3026229
telemt_connections_bad_total 28753
telemt_handshake_timeouts_total 202211
telemt_upstream_connect_attempt_total 35503
telemt_upstream_connect_success_total 35493
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3489
telemt_me_reconnect_attempts_total 29806
telemt_me_reconnect_success_total 27252
telemt_me_reader_eof_total 28896
telemt_me_idle_close_by_peer_total 28895
telemt_me_route_drop_no_conn_total 1032799
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2502388
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8523
telemt_desync_full_logged_total 2827
telemt_desync_suppressed_total 5696
telemt_desync_frames_bucket_total{bucket="1_2"} 1375
telemt_desync_frames_bucket_total{bucket="3_10"} 3119
telemt_desync_frames_bucket_total{bucket="gt_10"} 4029
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 27570
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27211
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 2501723
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 41072707212 (38.25 GB)
telemt_user_octets_to_client{user="hello"} 873911893069 (813.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 159237.5 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1949310
telemt_connections_bad_total 18282
telemt_handshake_timeouts_total 180607
telemt_upstream_connect_attempt_total 49376
telemt_upstream_connect_success_total 47035
telemt_upstream_connect_fail_total 2204
telemt_upstream_connect_attempts_per_request{bucket="1"} 49102
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11972
telemt_me_reconnect_attempts_total 42255
telemt_me_reconnect_success_total 33271
telemt_me_reader_eof_total 35725
telemt_me_idle_close_by_peer_total 35718
telemt_me_route_drop_no_conn_total 692374
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1607846
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3183
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 880
telemt_desync_frames_bucket_total{bucket="3_10"} 1309
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 33819
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33247
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 1612542
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 24827442833 (23.12 GB)
telemt_user_octets_to_client{user="hello"} 609076036326 (567.25 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28673.2 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468830
telemt_connections_bad_total 4634
telemt_handshake_timeouts_total 4882
telemt_upstream_connect_attempt_total 6501
telemt_upstream_connect_success_total 6292
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 6501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 19054
telemt_me_reconnect_success_total 4846
telemt_me_reader_eof_total 5384
telemt_me_idle_close_by_peer_total 5384
telemt_me_route_drop_no_conn_total 179269
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438537
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1320
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 899
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5328
telemt_me_refill_failed_total 442
telemt_me_writer_restored_same_endpoint_total 4842
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 438509
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 4955229564 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 136453381072 (127.08 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 84
```