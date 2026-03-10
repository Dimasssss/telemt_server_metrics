# Server Metrics 2026-03-10 21:17:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24647.1 (6h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687636
telemt_connections_bad_total 8152
telemt_handshake_timeouts_total 8061
telemt_upstream_connect_attempt_total 5405
telemt_upstream_connect_success_total 5396
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 15728
telemt_me_reconnect_success_total 4070
telemt_me_reader_eof_total 4509
telemt_me_idle_close_by_peer_total 4509
telemt_me_route_drop_no_conn_total 287089
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649477
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3293
telemt_desync_full_logged_total 911
telemt_desync_suppressed_total 2382
telemt_desync_frames_bucket_total{bucket="1_2"} 929
telemt_desync_frames_bucket_total{bucket="3_10"} 1241
telemt_desync_frames_bucket_total{bucket="gt_10"} 1123
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4464
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4064
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 649286
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 9232968144 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 197572589276 (184.00 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24703.7 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301575
telemt_connections_bad_total 1888
telemt_handshake_timeouts_total 17197
telemt_upstream_connect_attempt_total 11706
telemt_upstream_connect_success_total 8844
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 5411
telemt_me_reconnect_success_total 4608
telemt_me_reader_eof_total 4827
telemt_me_idle_close_by_peer_total 4825
telemt_me_route_drop_no_conn_total 161312
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252955
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 1064
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4689
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4587
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 255222
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 2590734930 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 60582088652 (56.42 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24703.6 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489716
telemt_connections_bad_total 2796
telemt_handshake_timeouts_total 33488
telemt_upstream_connect_attempt_total 7047
telemt_upstream_connect_success_total 6937
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 7047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 15623
telemt_me_reconnect_success_total 4578
telemt_me_reader_eof_total 5055
telemt_me_idle_close_by_peer_total 5055
telemt_me_route_drop_no_conn_total 170275
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427061
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1395
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4999
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4567
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 427998
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 6266117741 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 137847516681 (128.38 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24704.1 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337169
telemt_connections_bad_total 24034
telemt_handshake_timeouts_total 29046
telemt_upstream_connect_attempt_total 6635
telemt_upstream_connect_success_total 6635
telemt_upstream_connect_attempts_per_request{bucket="1"} 6635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 6371
telemt_me_reconnect_success_total 5349
telemt_me_reader_eof_total 5620
telemt_me_idle_close_by_peer_total 5620
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 110491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271560
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5438
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5336
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 271238
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 3948376772 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 83340867916 (77.62 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24703.8 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356444
telemt_connections_bad_total 1067
telemt_handshake_timeouts_total 2272
telemt_upstream_connect_attempt_total 7647
telemt_upstream_connect_success_total 7617
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 10055
telemt_me_reconnect_success_total 6301
telemt_me_reader_eof_total 6598
telemt_me_idle_close_by_peer_total 6598
telemt_me_route_drop_no_conn_total 127727
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1976
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6511
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6301
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 334447
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 6271027664 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 115745142436 (107.80 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 64
```