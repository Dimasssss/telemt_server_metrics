# Server Metrics 2026-03-14 17:20:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 14542.4 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588324
telemt_connections_bad_total 32416
telemt_handshake_timeouts_total 7985
telemt_upstream_connect_attempt_total 2949
telemt_upstream_connect_success_total 2936
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2930
telemt_me_reconnect_success_total 2131
telemt_me_reader_eof_total 2227
telemt_me_idle_close_by_peer_total 2227
telemt_me_route_drop_no_conn_total 225006
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521216
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1831
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2189
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2122
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 521151
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 9412414348 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 161660819568 (150.56 GB)
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 14547.7 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235562
telemt_connections_bad_total 22492
telemt_handshake_timeouts_total 7292
telemt_upstream_connect_attempt_total 3067
telemt_upstream_connect_success_total 3032
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 3014
telemt_me_reconnect_success_total 2228
telemt_me_reader_eof_total 2324
telemt_me_idle_close_by_peer_total 2324
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 73046
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2307
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2213
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 191043
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 2788370444 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 74874844840 (69.73 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 14410.7 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489924
telemt_connections_bad_total 1949
telemt_handshake_timeouts_total 101328
telemt_upstream_connect_attempt_total 2920
telemt_upstream_connect_success_total 2911
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 6065
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2331
telemt_me_idle_close_by_peer_total 2331
telemt_me_route_drop_no_conn_total 121331
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329937
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 974
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 647
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2301
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2131
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 329835
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 4847919380 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 119644570512 (111.43 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 14265.0 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256267
telemt_connections_bad_total 54386
telemt_handshake_timeouts_total 37739
telemt_upstream_connect_attempt_total 3519
telemt_upstream_connect_success_total 3518
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 3691
telemt_me_reconnect_success_total 2778
telemt_me_reader_eof_total 2887
telemt_me_idle_close_by_peer_total 2887
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 58446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2835
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2771
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 160421
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2459542716 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 51763738516 (48.21 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 14560.4 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227752
telemt_connections_bad_total 891
telemt_handshake_timeouts_total 2915
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3153
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3033
telemt_me_reconnect_success_total 2368
telemt_me_reader_eof_total 2485
telemt_me_idle_close_by_peer_total 2485
telemt_me_route_drop_no_conn_total 74388
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209663
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 554
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2436
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2350
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 209679
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 3323519460 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 82406861788 (76.75 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 84
```