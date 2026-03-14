# Server Metrics 2026-03-14 17:50:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 16382.3 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662880
telemt_connections_bad_total 37342
telemt_handshake_timeouts_total 8892
telemt_upstream_connect_attempt_total 3293
telemt_upstream_connect_success_total 3279
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3186
telemt_me_reconnect_success_total 2385
telemt_me_reader_eof_total 2497
telemt_me_idle_close_by_peer_total 2497
telemt_me_route_drop_no_conn_total 251614
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586605
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2025
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1443
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2448
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2376
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 586542
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 10405279516 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 186367553528 (173.57 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 16387.5 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261394
telemt_connections_bad_total 22623
telemt_handshake_timeouts_total 8405
telemt_upstream_connect_attempt_total 3443
telemt_upstream_connect_success_total 3402
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 303
telemt_me_reconnect_attempts_total 3300
telemt_me_reconnect_success_total 2510
telemt_me_reader_eof_total 2627
telemt_me_idle_close_by_peer_total 2627
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 81191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213267
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 826
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 565
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2591
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2495
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 213208
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 3062004768 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 81715813504 (76.10 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 16250.5 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552165
telemt_connections_bad_total 1979
telemt_handshake_timeouts_total 110526
telemt_upstream_connect_attempt_total 3247
telemt_upstream_connect_success_total 3238
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 6289
telemt_me_reconnect_success_total 2386
telemt_me_reader_eof_total 2569
telemt_me_idle_close_by_peer_total 2569
telemt_me_route_drop_no_conn_total 134516
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370706
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1131
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 571
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2529
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2353
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 370602
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 5600731864 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 133511201452 (124.34 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 16105.0 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294211
telemt_connections_bad_total 64884
telemt_handshake_timeouts_total 40694
telemt_upstream_connect_attempt_total 3897
telemt_upstream_connect_success_total 3896
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3982
telemt_me_reconnect_success_total 3067
telemt_me_reader_eof_total 3195
telemt_me_idle_close_by_peer_total 3195
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 65896
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184365
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3125
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3060
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 184319
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 2831076924 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 58585471144 (54.56 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 16400.6 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254872
telemt_connections_bad_total 979
telemt_handshake_timeouts_total 3092
telemt_upstream_connect_attempt_total 3508
telemt_upstream_connect_success_total 3438
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 3508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3232
telemt_me_reconnect_success_total 2566
telemt_me_reader_eof_total 2699
telemt_me_idle_close_by_peer_total 2699
telemt_me_route_drop_no_conn_total 81656
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235112
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 589
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2637
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2548
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 235122
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 3603736640 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 93291943984 (86.88 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 109
```