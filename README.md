# Server Metrics 2026-03-14 18:11:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 17608.5 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712289
telemt_connections_bad_total 38513
telemt_handshake_timeouts_total 9475
telemt_upstream_connect_attempt_total 3480
telemt_upstream_connect_success_total 3465
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 3329
telemt_me_reconnect_success_total 2528
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2649
telemt_me_route_drop_no_conn_total 272295
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632174
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2196
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1564
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2592
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2519
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 632107
telemt_user_connections_current{user="hello"} 1921
telemt_user_octets_from_client{user="hello"} 10993935324 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 204193013456 (190.17 GB)
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 17613.9 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279993
telemt_connections_bad_total 22765
telemt_handshake_timeouts_total 8786
telemt_upstream_connect_attempt_total 3654
telemt_upstream_connect_success_total 3610
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 310
telemt_me_reconnect_attempts_total 3465
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2799
telemt_me_idle_close_by_peer_total 2799
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 87000
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230764
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 621
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2757
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2659
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 230705
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 3230801872 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 86100820224 (80.19 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 17476.8 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593122
telemt_connections_bad_total 2041
telemt_handshake_timeouts_total 122854
telemt_upstream_connect_attempt_total 3500
telemt_upstream_connect_success_total 3488
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6470
telemt_me_reconnect_success_total 2566
telemt_me_reader_eof_total 2761
telemt_me_idle_close_by_peer_total 2761
telemt_me_route_drop_no_conn_total 143887
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397537
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1260
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 820
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2711
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2533
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 397427
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 5815954636 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 141682747700 (131.95 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 17331.3 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319503
telemt_connections_bad_total 74434
telemt_handshake_timeouts_total 41261
telemt_upstream_connect_attempt_total 4189
telemt_upstream_connect_success_total 4188
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 4188
telemt_me_reconnect_success_total 3273
telemt_me_reader_eof_total 3421
telemt_me_idle_close_by_peer_total 3421
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 70948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 406
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3333
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3266
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 199092
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 2984608220 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 62066737244 (57.80 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 17627.1 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271778
telemt_connections_bad_total 1106
telemt_handshake_timeouts_total 3266
telemt_upstream_connect_attempt_total 3701
telemt_upstream_connect_success_total 3626
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 3701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3377
telemt_me_reconnect_success_total 2710
telemt_me_reader_eof_total 2853
telemt_me_idle_close_by_peer_total 2853
telemt_me_route_drop_no_conn_total 86561
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251064
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 617
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2785
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2692
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 251052
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 3934730732 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 104668534284 (97.48 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 88
```