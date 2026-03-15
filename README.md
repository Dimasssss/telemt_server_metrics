# Server Metrics 2026-03-15 08:43:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 37712.5 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768279
telemt_connections_bad_total 30409
telemt_handshake_timeouts_total 5534
telemt_upstream_connect_attempt_total 7707
telemt_upstream_connect_success_total 7675
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5834
telemt_me_reconnect_success_total 5803
telemt_me_reader_eof_total 6139
telemt_me_idle_close_by_peer_total 6139
telemt_me_route_drop_no_conn_total 249142
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653386
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1389
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5881
telemt_me_writer_restored_same_endpoint_total 5792
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 653384
telemt_user_connections_current{user="hello"} 1785
telemt_user_octets_from_client{user="hello"} 8795077936 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 245146644104 (228.31 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 37713.3 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303837
telemt_connections_bad_total 18461
telemt_handshake_timeouts_total 12509
telemt_upstream_connect_attempt_total 10117
telemt_upstream_connect_success_total 10067
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7919
telemt_me_reconnect_success_total 7871
telemt_me_reader_eof_total 8337
telemt_me_idle_close_by_peer_total 8337
telemt_me_route_drop_no_conn_total 76639
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239959
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7930
telemt_me_writer_restored_same_endpoint_total 7863
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 240236
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 3463413619 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 90230553424 (84.03 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 37713.3 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525884
telemt_connections_bad_total 16328
telemt_handshake_timeouts_total 46967
telemt_upstream_connect_attempt_total 8376
telemt_upstream_connect_success_total 8339
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6498
telemt_me_reconnect_success_total 6457
telemt_me_reader_eof_total 6838
telemt_me_idle_close_by_peer_total 6838
telemt_me_route_drop_no_conn_total 146106
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6536
telemt_me_writer_restored_same_endpoint_total 6438
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 422172
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 6214390624 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 175565040700 (163.51 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 37713.2 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329440
telemt_connections_bad_total 49394
telemt_handshake_timeouts_total 22126
telemt_upstream_connect_attempt_total 12043
telemt_upstream_connect_success_total 11771
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 12043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22539
telemt_me_reconnect_success_total 9896
telemt_me_reader_eof_total 10596
telemt_me_idle_close_by_peer_total 10596
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 87429
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245488
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10373
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9866
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 245491
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 2184983580 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 80779649600 (75.23 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 37714.4 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293272
telemt_connections_bad_total 3670
telemt_handshake_timeouts_total 3185
telemt_upstream_connect_attempt_total 8318
telemt_upstream_connect_success_total 8284
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6445
telemt_me_reconnect_success_total 6416
telemt_me_reader_eof_total 6843
telemt_me_idle_close_by_peer_total 6843
telemt_me_route_drop_no_conn_total 82153
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 995
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 667
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6480
telemt_me_writer_restored_same_endpoint_total 6408
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 253954
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 2874394204 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 98343305924 (91.59 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 119
```