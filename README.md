# Server Metrics 2026-03-10 22:24:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28616.6 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732297
telemt_connections_bad_total 8890
telemt_handshake_timeouts_total 8319
telemt_upstream_connect_attempt_total 6147
telemt_upstream_connect_success_total 6138
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 16297
telemt_me_reconnect_success_total 4638
telemt_me_reader_eof_total 5119
telemt_me_idle_close_by_peer_total 5119
telemt_me_route_drop_no_conn_total 304928
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3436
telemt_desync_full_logged_total 960
telemt_desync_suppressed_total 2476
telemt_desync_frames_bucket_total{bucket="1_2"} 992
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 1161
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 5040
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4632
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 692139
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 9963480264 (9.28 GB)
telemt_user_octets_to_client{user="hello"} 209940821384 (195.52 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28673.4 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317766
telemt_connections_bad_total 2363
telemt_handshake_timeouts_total 17573
telemt_upstream_connect_attempt_total 12668
telemt_upstream_connect_success_total 9803
telemt_upstream_connect_fail_total 2865
telemt_upstream_connect_attempts_per_request{bucket="1"} 12668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2865
telemt_me_keepalive_timeout_total 1375
telemt_me_reconnect_attempts_total 6195
telemt_me_reconnect_success_total 5389
telemt_me_reader_eof_total 5656
telemt_me_idle_close_by_peer_total 5654
telemt_me_route_drop_no_conn_total 166257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267870
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1595
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5475
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5368
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 270143
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2658723786 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 63677303148 (59.30 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28673.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524552
telemt_connections_bad_total 3341
telemt_handshake_timeouts_total 33708
telemt_upstream_connect_attempt_total 7914
telemt_upstream_connect_success_total 7798
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 16312
telemt_me_reconnect_success_total 5257
telemt_me_reader_eof_total 5785
telemt_me_idle_close_by_peer_total 5785
telemt_me_route_drop_no_conn_total 181939
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459197
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1466
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 1053
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5685
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5246
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 460130
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 6607849733 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 147813930641 (137.66 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28673.7 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367013
telemt_connections_bad_total 27641
telemt_handshake_timeouts_total 32746
telemt_upstream_connect_attempt_total 7937
telemt_upstream_connect_success_total 7937
telemt_upstream_connect_attempts_per_request{bucket="1"} 7937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 7495
telemt_me_reconnect_success_total 6471
telemt_me_reader_eof_total 6796
telemt_me_idle_close_by_peer_total 6796
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 117992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293764
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6571
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6457
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 293442
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 4038249804 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 86539984828 (80.60 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28673.4 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387760
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 2550
telemt_upstream_connect_attempt_total 8902
telemt_upstream_connect_success_total 8867
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 11126
telemt_me_reconnect_success_total 7368
telemt_me_reader_eof_total 7722
telemt_me_idle_close_by_peer_total 7722
telemt_me_route_drop_no_conn_total 135934
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361356
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2125
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 1319
telemt_desync_frames_bucket_total{bucket="1_2"} 784
telemt_desync_frames_bucket_total{bucket="3_10"} 908
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 7588
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7368
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 361188
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 6419559472 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 137032751704 (127.62 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 50
```