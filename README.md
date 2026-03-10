# Server Metrics 2026-03-10 21:22:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24952.2 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691420
telemt_connections_bad_total 8152
telemt_handshake_timeouts_total 8078
telemt_upstream_connect_attempt_total 5434
telemt_upstream_connect_success_total 5425
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 15757
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4538
telemt_me_idle_close_by_peer_total 4538
telemt_me_route_drop_no_conn_total 288398
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653179
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3306
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 933
telemt_desync_frames_bucket_total{bucket="3_10"} 1245
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4493
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4093
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 652984
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 9266731316 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 198523999408 (184.89 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25009.0 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303031
telemt_connections_bad_total 1888
telemt_handshake_timeouts_total 17203
telemt_upstream_connect_attempt_total 11758
telemt_upstream_connect_success_total 8896
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1344
telemt_me_reconnect_attempts_total 5463
telemt_me_reconnect_success_total 4660
telemt_me_reader_eof_total 4879
telemt_me_idle_close_by_peer_total 4877
telemt_me_route_drop_no_conn_total 161853
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254319
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 1071
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4741
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4639
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 256592
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 2595721910 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 60870037168 (56.69 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25008.9 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492990
telemt_connections_bad_total 2797
telemt_handshake_timeouts_total 33501
telemt_upstream_connect_attempt_total 7094
telemt_upstream_connect_success_total 6984
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 7094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 15670
telemt_me_reconnect_success_total 4624
telemt_me_reader_eof_total 5101
telemt_me_idle_close_by_peer_total 5101
telemt_me_route_drop_no_conn_total 171405
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429818
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1402
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 480
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 5045
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4613
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 430755
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 6310854297 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 138542574501 (129.03 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25009.3 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340000
telemt_connections_bad_total 24312
telemt_handshake_timeouts_total 29352
telemt_upstream_connect_attempt_total 6694
telemt_upstream_connect_success_total 6694
telemt_upstream_connect_attempts_per_request{bucket="1"} 6694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 6430
telemt_me_reconnect_success_total 5409
telemt_me_reader_eof_total 5680
telemt_me_idle_close_by_peer_total 5680
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 111584
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273813
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
telemt_me_writer_removed_unexpected_total 5498
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5396
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 273491
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 3955811140 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 83831707756 (78.07 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25008.9 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359070
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 2283
telemt_upstream_connect_attempt_total 7726
telemt_upstream_connect_success_total 7696
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 10134
telemt_me_reconnect_success_total 6380
telemt_me_reader_eof_total 6677
telemt_me_idle_close_by_peer_total 6677
telemt_me_route_drop_no_conn_total 128301
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336947
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1998
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 849
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6590
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6380
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 336824
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 6283981784 (5.85 GB)
telemt_user_octets_to_client{user="hello"} 116230669976 (108.25 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 63
```