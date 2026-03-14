# Server Metrics 2026-03-14 19:38:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 22833.6 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903773
telemt_connections_bad_total 40374
telemt_handshake_timeouts_total 13415
telemt_upstream_connect_attempt_total 4247
telemt_upstream_connect_success_total 4230
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 3833
telemt_me_reconnect_success_total 3029
telemt_me_reader_eof_total 3188
telemt_me_idle_close_by_peer_total 3188
telemt_me_route_drop_no_conn_total 346386
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799165
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2741
telemt_desync_full_logged_total 784
telemt_desync_suppressed_total 1957
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3105
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3020
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 799109
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 14263253620 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 263031504460 (244.97 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 22838.9 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348848
telemt_connections_bad_total 23938
telemt_handshake_timeouts_total 10333
telemt_upstream_connect_attempt_total 4836
telemt_upstream_connect_success_total 4782
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 4377
telemt_me_reconnect_success_total 3584
telemt_me_reader_eof_total 3751
telemt_me_idle_close_by_peer_total 3751
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 108015
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294675
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1316
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3689
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3566
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 294606
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 3960757268 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 103260419260 (96.17 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 22701.6 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732096
telemt_connections_bad_total 2891
telemt_handshake_timeouts_total 146613
telemt_upstream_connect_attempt_total 4418
telemt_upstream_connect_success_total 4402
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 7124
telemt_me_reconnect_success_total 3215
telemt_me_reader_eof_total 3455
telemt_me_idle_close_by_peer_total 3455
telemt_me_route_drop_no_conn_total 176901
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497999
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1803
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1102
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 928
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3370
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3182
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 497830
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 7326948584 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 178052392868 (165.82 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 22556.1 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405356
telemt_connections_bad_total 91285
telemt_handshake_timeouts_total 48045
telemt_upstream_connect_attempt_total 5300
telemt_upstream_connect_success_total 5299
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 5056
telemt_me_reconnect_success_total 4137
telemt_me_reader_eof_total 4325
telemt_me_idle_close_by_peer_total 4325
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 93728
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259310
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 565
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4214
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4126
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 259227
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 3727903392 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 82964217212 (77.27 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 22851.5 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344879
telemt_connections_bad_total 1308
telemt_handshake_timeouts_total 3738
telemt_upstream_connect_attempt_total 4798
telemt_upstream_connect_success_total 4698
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 4798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4189
telemt_me_reconnect_success_total 3518
telemt_me_reader_eof_total 3707
telemt_me_idle_close_by_peer_total 3707
telemt_me_route_drop_no_conn_total 109610
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319210
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3606
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3500
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 319183
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 4884087860 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 135354774792 (126.06 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 82
```