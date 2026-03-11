# Server Metrics 2026-03-11 01:06:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 38371.1 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803051
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9096
telemt_upstream_connect_attempt_total 8348
telemt_upstream_connect_success_total 8339
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 18023
telemt_me_reconnect_success_total 6357
telemt_me_reader_eof_total 6965
telemt_me_idle_close_by_peer_total 6965
telemt_me_route_drop_no_conn_total 329070
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 760591
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3586
telemt_desync_full_logged_total 1006
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1332
telemt_desync_frames_bucket_total{bucket="gt_10"} 1204
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6775
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6351
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 760358
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 10525789356 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 230898917256 (215.04 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38427.7 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345833
telemt_connections_bad_total 2393
telemt_handshake_timeouts_total 17683
telemt_upstream_connect_attempt_total 15519
telemt_upstream_connect_success_total 12637
telemt_upstream_connect_fail_total 2882
telemt_upstream_connect_attempts_per_request{bucket="1"} 15519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2882
telemt_me_keepalive_timeout_total 1712
telemt_me_reconnect_attempts_total 8553
telemt_me_reconnect_success_total 7738
telemt_me_reader_eof_total 8169
telemt_me_idle_close_by_peer_total 8167
telemt_me_route_drop_no_conn_total 173564
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295118
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1775
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7842
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7717
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 297387
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2852359554 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 70690904308 (65.84 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 38427.6 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575042
telemt_connections_bad_total 4106
telemt_handshake_timeouts_total 34184
telemt_upstream_connect_attempt_total 10521
telemt_upstream_connect_success_total 10376
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 10521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 18414
telemt_me_reconnect_success_total 7352
telemt_me_reader_eof_total 8013
telemt_me_idle_close_by_peer_total 8013
telemt_me_route_drop_no_conn_total 197048
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508199
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7797
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7341
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 509115
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 6899200973 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 155380055053 (144.71 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 38428.1 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423289
telemt_connections_bad_total 36516
telemt_handshake_timeouts_total 40065
telemt_upstream_connect_attempt_total 11007
telemt_upstream_connect_success_total 11007
telemt_upstream_connect_attempts_per_request{bucket="1"} 11007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 10090
telemt_me_reconnect_success_total 9056
telemt_me_reader_eof_total 9576
telemt_me_idle_close_by_peer_total 9576
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 129512
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333669
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9173
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9040
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 333345
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 4223248124 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 91228687304 (84.96 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38427.8 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447646
telemt_connections_bad_total 4949
telemt_handshake_timeouts_total 2900
telemt_upstream_connect_attempt_total 11571
telemt_upstream_connect_success_total 11522
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 507
telemt_me_reconnect_attempts_total 13304
telemt_me_reconnect_success_total 9537
telemt_me_reader_eof_total 10031
telemt_me_idle_close_by_peer_total 10031
telemt_me_route_drop_no_conn_total 148491
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411290
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2276
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 839
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9776
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9537
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 411008
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 8378215032 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 147351345484 (137.23 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 38
```