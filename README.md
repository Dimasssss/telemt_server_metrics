# Server Metrics 2026-03-14 19:53:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 23753.8 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929344
telemt_connections_bad_total 40387
telemt_handshake_timeouts_total 13940
telemt_upstream_connect_attempt_total 4393
telemt_upstream_connect_success_total 4375
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3935
telemt_me_reconnect_success_total 3130
telemt_me_reader_eof_total 3298
telemt_me_idle_close_by_peer_total 3298
telemt_me_route_drop_no_conn_total 356255
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822967
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2826
telemt_desync_full_logged_total 808
telemt_desync_suppressed_total 2018
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1037
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3210
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3121
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 822914
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 14708928508 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 270929824720 (252.32 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 23758.9 (6h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360616
telemt_connections_bad_total 25351
telemt_handshake_timeouts_total 10738
telemt_upstream_connect_attempt_total 5095
telemt_upstream_connect_success_total 5041
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 4593
telemt_me_reconnect_success_total 3800
telemt_me_reader_eof_total 3972
telemt_me_idle_close_by_peer_total 3972
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 110606
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304223
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1453
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3907
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3778
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 304154
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 4061157760 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 106322130492 (99.02 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 23621.8 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762463
telemt_connections_bad_total 3187
telemt_handshake_timeouts_total 160040
telemt_upstream_connect_attempt_total 4580
telemt_upstream_connect_success_total 4564
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 7243
telemt_me_reconnect_success_total 3334
telemt_me_reader_eof_total 3582
telemt_me_idle_close_by_peer_total 3582
telemt_me_route_drop_no_conn_total 182186
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511973
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1129
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3492
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3301
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 511802
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 7558605824 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 183710794068 (171.09 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 23476.3 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420306
telemt_connections_bad_total 93849
telemt_handshake_timeouts_total 50311
telemt_upstream_connect_attempt_total 5490
telemt_upstream_connect_success_total 5489
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 5193
telemt_me_reconnect_success_total 4273
telemt_me_reader_eof_total 4471
telemt_me_idle_close_by_peer_total 4471
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 96557
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269203
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 593
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4351
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4262
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 269120
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 3787615568 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 85030308492 (79.19 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 23771.7 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355189
telemt_connections_bad_total 1315
telemt_handshake_timeouts_total 3790
telemt_upstream_connect_attempt_total 5054
telemt_upstream_connect_success_total 4948
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 5054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 4396
telemt_me_reconnect_success_total 3724
telemt_me_reader_eof_total 3914
telemt_me_idle_close_by_peer_total 3914
telemt_me_route_drop_no_conn_total 112518
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3813
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3706
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 328871
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 5313905076 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 140285373384 (130.65 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 71
```