# Server Metrics 2026-03-14 20:19:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 25287.5 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971802
telemt_connections_bad_total 40429
telemt_handshake_timeouts_total 14354
telemt_upstream_connect_attempt_total 4620
telemt_upstream_connect_success_total 4599
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 4086
telemt_me_reconnect_success_total 3281
telemt_me_reader_eof_total 3454
telemt_me_idle_close_by_peer_total 3454
telemt_me_route_drop_no_conn_total 373031
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862750
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2987
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 2146
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1093
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3361
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3272
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 862696
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 15518760940 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 289622862836 (269.73 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 25292.6 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380321
telemt_connections_bad_total 27680
telemt_handshake_timeouts_total 11403
telemt_upstream_connect_attempt_total 5366
telemt_upstream_connect_success_total 5310
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 5366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 4788
telemt_me_reconnect_success_total 3994
telemt_me_reader_eof_total 4173
telemt_me_idle_close_by_peer_total 4173
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 114292
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320139
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 1141
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4103
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3972
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 320072
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 4799105944 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 112812307848 (105.06 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 25155.4 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816051
telemt_connections_bad_total 3333
telemt_handshake_timeouts_total 184742
telemt_upstream_connect_attempt_total 4823
telemt_upstream_connect_success_total 4807
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 7443
telemt_me_reconnect_success_total 3532
telemt_me_reader_eof_total 3788
telemt_me_idle_close_by_peer_total 3788
telemt_me_route_drop_no_conn_total 189560
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534470
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3692
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3499
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 534299
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 7998789412 (7.45 GB)
telemt_user_octets_to_client{user="hello"} 193265117348 (179.99 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 25009.9 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442999
telemt_connections_bad_total 98030
telemt_handshake_timeouts_total 52445
telemt_upstream_connect_attempt_total 5821
telemt_upstream_connect_success_total 5820
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 5473
telemt_me_reconnect_success_total 4552
telemt_me_reader_eof_total 4769
telemt_me_idle_close_by_peer_total 4769
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 101122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285110
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 651
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4632
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4541
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 285027
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 4031779884 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 88300085056 (82.24 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 25305.3 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372582
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 3869
telemt_upstream_connect_attempt_total 5418
telemt_upstream_connect_success_total 5309
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 4676
telemt_me_reconnect_success_total 4003
telemt_me_reader_eof_total 4218
telemt_me_idle_close_by_peer_total 4218
telemt_me_route_drop_no_conn_total 118140
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345211
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 877
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4096
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3985
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 345181
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 5615542960 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 146819869580 (136.74 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 66
```