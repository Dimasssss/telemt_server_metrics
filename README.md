# Server Metrics 2026-03-11 04:50:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51781.7 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002874
telemt_connections_bad_total 10308
telemt_handshake_timeouts_total 31009
telemt_upstream_connect_attempt_total 11122
telemt_upstream_connect_success_total 11113
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 20148
telemt_me_reconnect_success_total 8473
telemt_me_reader_eof_total 9231
telemt_me_idle_close_by_peer_total 9231
telemt_me_route_drop_no_conn_total 375192
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903564
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4098
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 2946
telemt_desync_frames_bucket_total{bucket="1_2"} 1155
telemt_desync_frames_bucket_total{bucket="3_10"} 1542
telemt_desync_frames_bucket_total{bucket="gt_10"} 1401
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8914
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8467
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 903279
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 11804131660 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 265604579376 (247.36 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51838.3 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393999
telemt_connections_bad_total 2572
telemt_handshake_timeouts_total 19091
telemt_upstream_connect_attempt_total 19447
telemt_upstream_connect_success_total 16546
telemt_upstream_connect_fail_total 2901
telemt_upstream_connect_attempts_per_request{bucket="1"} 19447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2901
telemt_me_keepalive_timeout_total 1779
telemt_me_reconnect_attempts_total 11810
telemt_me_reconnect_success_total 10991
telemt_me_reader_eof_total 11617
telemt_me_idle_close_by_peer_total 11615
telemt_me_route_drop_no_conn_total 187337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338555
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 575
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11121
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10970
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 340827
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 3255971862 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 81483246052 (75.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51838.1 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667929
telemt_connections_bad_total 5592
telemt_handshake_timeouts_total 36666
telemt_upstream_connect_attempt_total 14072
telemt_upstream_connect_success_total 13889
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 14072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 21277
telemt_me_reconnect_success_total 10206
telemt_me_reader_eof_total 11039
telemt_me_idle_close_by_peer_total 11039
telemt_me_route_drop_no_conn_total 224747
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595489
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1644
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10686
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10195
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 596357
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 7404740805 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 179317617777 (167.00 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51838.6 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509995
telemt_connections_bad_total 48776
telemt_handshake_timeouts_total 53575
telemt_upstream_connect_attempt_total 14977
telemt_upstream_connect_success_total 14977
telemt_upstream_connect_attempts_per_request{bucket="1"} 14977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 13413
telemt_me_reconnect_success_total 12371
telemt_me_reader_eof_total 13136
telemt_me_idle_close_by_peer_total 13136
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 151234
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393416
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 832
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 493
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12514
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12351
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 393074
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 4773314304 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 107954174836 (100.54 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51838.2 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532356
telemt_connections_bad_total 5829
telemt_handshake_timeouts_total 3440
telemt_upstream_connect_attempt_total 14987
telemt_upstream_connect_success_total 14925
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 557
telemt_me_reconnect_attempts_total 16059
telemt_me_reconnect_success_total 12278
telemt_me_reader_eof_total 12960
telemt_me_idle_close_by_peer_total 12960
telemt_me_route_drop_no_conn_total 172244
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485208
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2410
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12552
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12278
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 484826
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 8868973940 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 171959597208 (160.15 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 58
```