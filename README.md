# Server Metrics 2026-03-11 06:47:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58794.7 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164533
telemt_connections_bad_total 13235
telemt_handshake_timeouts_total 38721
telemt_upstream_connect_attempt_total 12393
telemt_upstream_connect_success_total 12384
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 21073
telemt_me_reconnect_success_total 9390
telemt_me_reader_eof_total 10208
telemt_me_idle_close_by_peer_total 10208
telemt_me_route_drop_no_conn_total 428052
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048683
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5031
telemt_desync_full_logged_total 1406
telemt_desync_suppressed_total 3625
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 1887
telemt_desync_frames_bucket_total{bucket="gt_10"} 1792
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9845
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9384
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 1048346
telemt_user_connections_current{user="hello"} 1209
telemt_user_octets_from_client{user="hello"} 13917406196 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 307524837724 (286.40 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58851.5 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449145
telemt_connections_bad_total 5143
telemt_handshake_timeouts_total 21902
telemt_upstream_connect_attempt_total 21117
telemt_upstream_connect_success_total 18204
telemt_upstream_connect_fail_total 2913
telemt_upstream_connect_attempts_per_request{bucket="1"} 21117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2913
telemt_me_keepalive_timeout_total 2029
telemt_me_reconnect_attempts_total 13121
telemt_me_reconnect_success_total 12296
telemt_me_reader_eof_total 13002
telemt_me_idle_close_by_peer_total 13000
telemt_me_route_drop_no_conn_total 202726
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384272
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1954
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1361
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12440
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12274
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 386542
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 3845040586 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 96939126496 (90.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58851.4 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 764428
telemt_connections_bad_total 6624
telemt_handshake_timeouts_total 41440
telemt_upstream_connect_attempt_total 15785
telemt_upstream_connect_success_total 15582
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 704
telemt_me_reconnect_attempts_total 22624
telemt_me_reconnect_success_total 11551
telemt_me_reader_eof_total 12446
telemt_me_idle_close_by_peer_total 12446
telemt_me_route_drop_no_conn_total 258306
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683670
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1955
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 703
telemt_desync_frames_bucket_total{bucket="gt_10"} 791
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12044
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11540
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 684500
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 8077016305 (7.52 GB)
telemt_user_octets_to_client{user="hello"} 202419737445 (188.52 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58851.9 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582431
telemt_connections_bad_total 55179
telemt_handshake_timeouts_total 59101
telemt_upstream_connect_attempt_total 16721
telemt_upstream_connect_success_total 16721
telemt_upstream_connect_attempts_per_request{bucket="1"} 16721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 14811
telemt_me_reconnect_success_total 13764
telemt_me_reader_eof_total 14615
telemt_me_idle_close_by_peer_total 14615
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 175742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450618
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 959
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 565
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13924
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13742
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 450157
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 5398160948 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 123347456652 (114.88 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58851.4 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607538
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4301
telemt_upstream_connect_attempt_total 16662
telemt_upstream_connect_success_total 16593
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7933
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 676
telemt_me_reconnect_attempts_total 17305
telemt_me_reconnect_success_total 13519
telemt_me_reader_eof_total 14287
telemt_me_idle_close_by_peer_total 14287
telemt_me_route_drop_no_conn_total 200065
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553255
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2598
telemt_desync_full_logged_total 996
telemt_desync_suppressed_total 1602
telemt_desync_frames_bucket_total{bucket="1_2"} 929
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 13812
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13519
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 552987
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 9601576107 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 201470913778 (187.63 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 67
```