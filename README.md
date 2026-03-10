# Server Metrics 2026-03-10 20:26:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21589.7 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639851
telemt_connections_bad_total 8008
telemt_handshake_timeouts_total 7206
telemt_upstream_connect_attempt_total 4530
telemt_upstream_connect_success_total 4521
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 339
telemt_me_reconnect_attempts_total 15029
telemt_me_reconnect_success_total 3378
telemt_me_reader_eof_total 3765
telemt_me_idle_close_by_peer_total 3765
telemt_me_route_drop_no_conn_total 267939
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 603503
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3136
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 2287
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1183
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3761
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3372
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 603324
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 8663401476 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 179524257792 (167.19 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21646.6 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282806
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16887
telemt_upstream_connect_attempt_total 10224
telemt_upstream_connect_success_total 7378
telemt_upstream_connect_fail_total 2846
telemt_upstream_connect_attempts_per_request{bucket="1"} 10224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2846
telemt_me_keepalive_timeout_total 735
telemt_me_reconnect_attempts_total 4769
telemt_me_reconnect_success_total 3977
telemt_me_reader_eof_total 4156
telemt_me_idle_close_by_peer_total 4154
telemt_me_route_drop_no_conn_total 155126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236829
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1292
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4052
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3956
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 238429
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 2432397142 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 56778223818 (52.88 GB)
telemt_user_msgs_from_client{user="hello"} 5762
telemt_user_msgs_to_client{user="hello"} 6647
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21646.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456707
telemt_connections_bad_total 2241
telemt_handshake_timeouts_total 32506
telemt_upstream_connect_attempt_total 6506
telemt_upstream_connect_success_total 6410
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 6506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 11193
telemt_me_reconnect_success_total 4219
telemt_me_reader_eof_total 4559
telemt_me_idle_close_by_peer_total 4559
telemt_me_route_drop_no_conn_total 157815
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396249
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1332
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 572
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4511
telemt_me_refill_failed_total 216
telemt_me_writer_restored_same_endpoint_total 4208
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 397193
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 5721465721 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 123774188793 (115.27 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21646.7 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308650
telemt_connections_bad_total 21252
telemt_handshake_timeouts_total 26670
telemt_upstream_connect_attempt_total 5898
telemt_upstream_connect_success_total 5898
telemt_upstream_connect_attempts_per_request{bucket="1"} 5898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 5793
telemt_me_reconnect_success_total 4776
telemt_me_reader_eof_total 5001
telemt_me_idle_close_by_peer_total 5001
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 100282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248824
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4855
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4763
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 248522
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 3778287384 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 77833303668 (72.49 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21646.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324545
telemt_connections_bad_total 987
telemt_handshake_timeouts_total 2056
telemt_upstream_connect_attempt_total 6868
telemt_upstream_connect_success_total 6841
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 8101
telemt_me_reconnect_success_total 5694
telemt_me_reader_eof_total 5914
telemt_me_idle_close_by_peer_total 5914
telemt_me_route_drop_no_conn_total 118137
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305460
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1779
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1118
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 748
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5852
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 5694
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 305368
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 5955948444 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 102129860884 (95.12 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 54
```