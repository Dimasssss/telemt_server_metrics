# Server Metrics 2026-03-10 22:08:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27699.8 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722840
telemt_connections_bad_total 8313
telemt_handshake_timeouts_total 8270
telemt_upstream_connect_attempt_total 5960
telemt_upstream_connect_success_total 5951
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 16153
telemt_me_reconnect_success_total 4494
telemt_me_reader_eof_total 4963
telemt_me_idle_close_by_peer_total 4963
telemt_me_route_drop_no_conn_total 301316
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683617
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3397
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 2443
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 1144
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4894
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4488
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 683422
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 9912188360 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 206786239044 (192.58 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27756.5 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314806
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 17526
telemt_upstream_connect_attempt_total 12444
telemt_upstream_connect_success_total 9581
telemt_upstream_connect_fail_total 2863
telemt_upstream_connect_attempts_per_request{bucket="1"} 12444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2863
telemt_me_keepalive_timeout_total 1373
telemt_me_reconnect_attempts_total 6017
telemt_me_reconnect_success_total 5211
telemt_me_reader_eof_total 5469
telemt_me_idle_close_by_peer_total 5467
telemt_me_route_drop_no_conn_total 165216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265031
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1586
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 1147
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 537
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5296
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5190
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 267304
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 2642850662 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 62763378696 (58.45 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27756.3 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518086
telemt_connections_bad_total 3070
telemt_handshake_timeouts_total 33637
telemt_upstream_connect_attempt_total 7729
telemt_upstream_connect_success_total 7613
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 16170
telemt_me_reconnect_success_total 5118
telemt_me_reader_eof_total 5631
telemt_me_idle_close_by_peer_total 5631
telemt_me_route_drop_no_conn_total 180139
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453129
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1449
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5542
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5107
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 454062
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 6574268009 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 146507927785 (136.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27756.6 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360516
telemt_connections_bad_total 26810
telemt_handshake_timeouts_total 31846
telemt_upstream_connect_attempt_total 7680
telemt_upstream_connect_success_total 7680
telemt_upstream_connect_attempts_per_request{bucket="1"} 7680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 7281
telemt_me_reconnect_success_total 6257
telemt_me_reader_eof_total 6570
telemt_me_idle_close_by_peer_total 6570
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 116466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289059
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6356
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6243
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 288737
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 4021906904 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 85844124880 (79.95 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27756.5 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380626
telemt_connections_bad_total 2093
telemt_handshake_timeouts_total 2469
telemt_upstream_connect_attempt_total 8619
telemt_upstream_connect_success_total 8585
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 10888
telemt_me_reconnect_success_total 7132
telemt_me_reader_eof_total 7455
telemt_me_idle_close_by_peer_total 7455
telemt_me_route_drop_no_conn_total 133908
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355315
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2106
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 779
telemt_desync_frames_bucket_total{bucket="3_10"} 898
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7352
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7132
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 355159
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 6399844392 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 135114621920 (125.84 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 44
```