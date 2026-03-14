# Server Metrics 2026-03-14 20:03:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 24367.3 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946374
telemt_connections_bad_total 40391
telemt_handshake_timeouts_total 14256
telemt_upstream_connect_attempt_total 4454
telemt_upstream_connect_success_total 4436
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3977
telemt_me_reconnect_success_total 3172
telemt_me_reader_eof_total 3340
telemt_me_idle_close_by_peer_total 3340
telemt_me_route_drop_no_conn_total 363459
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 838684
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2920
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 2096
telemt_desync_frames_bucket_total{bucket="1_2"} 693
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 1151
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3252
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3163
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 838631
telemt_user_connections_current{user="hello"} 1538
telemt_user_octets_from_client{user="hello"} 15027339868 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 276743008848 (257.74 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 24372.7 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368427
telemt_connections_bad_total 26109
telemt_handshake_timeouts_total 10981
telemt_upstream_connect_attempt_total 5180
telemt_upstream_connect_success_total 5125
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 443
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 3855
telemt_me_reader_eof_total 4029
telemt_me_idle_close_by_peer_total 4029
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 112186
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310798
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1498
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 626
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3964
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3833
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 310731
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 4677850164 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 108759192108 (101.29 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 24235.5 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786859
telemt_connections_bad_total 3187
telemt_handshake_timeouts_total 172859
telemt_upstream_connect_attempt_total 4648
telemt_upstream_connect_success_total 4632
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 7311
telemt_me_reconnect_success_total 3401
telemt_me_reader_eof_total 3649
telemt_me_idle_close_by_peer_total 3649
telemt_me_route_drop_no_conn_total 185452
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521835
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 973
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3559
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3368
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 521664
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 7713009948 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 186670496516 (173.85 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 24090.0 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429223
telemt_connections_bad_total 95482
telemt_handshake_timeouts_total 50864
telemt_upstream_connect_attempt_total 5626
telemt_upstream_connect_success_total 5625
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 5321
telemt_me_reconnect_success_total 4400
telemt_me_reader_eof_total 4604
telemt_me_idle_close_by_peer_total 4604
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 98289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275773
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 602
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4478
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4389
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 275690
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 3882809464 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 86209675392 (80.29 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 24385.5 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362400
telemt_connections_bad_total 1330
telemt_handshake_timeouts_total 3817
telemt_upstream_connect_attempt_total 5247
telemt_upstream_connect_success_total 5139
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 5247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 4556
telemt_me_reconnect_success_total 3883
telemt_me_reader_eof_total 4074
telemt_me_idle_close_by_peer_total 4074
telemt_me_route_drop_no_conn_total 114702
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335700
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 825
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3973
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3865
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 335672
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 5486869544 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 143186706660 (133.35 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 77
```