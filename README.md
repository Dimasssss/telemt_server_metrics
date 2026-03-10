# Server Metrics 2026-03-10 19:51:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19448.5 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597267
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 5112
telemt_upstream_connect_attempt_total 3892
telemt_upstream_connect_success_total 3883
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 327
telemt_me_reconnect_attempts_total 13303
telemt_me_reconnect_success_total 2841
telemt_me_reader_eof_total 3187
telemt_me_idle_close_by_peer_total 3187
telemt_me_route_drop_no_conn_total 250373
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563853
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 2199
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 1149
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3183
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2835
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 563676
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 8188427728 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 163383349780 (152.16 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19505.2 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257169
telemt_connections_bad_total 1827
telemt_handshake_timeouts_total 16589
telemt_upstream_connect_attempt_total 9363
telemt_upstream_connect_success_total 6616
telemt_upstream_connect_fail_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 9363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1884
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2747
telemt_me_keepalive_timeout_total 715
telemt_me_reconnect_attempts_total 4399
telemt_me_reconnect_success_total 3609
telemt_me_reader_eof_total 3762
telemt_me_idle_close_by_peer_total 3760
telemt_me_route_drop_no_conn_total 140776
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220155
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1136
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3676
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3588
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 221454
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 2348693230 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 54741666402 (50.98 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19505.2 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427719
telemt_connections_bad_total 1420
telemt_handshake_timeouts_total 32380
telemt_upstream_connect_attempt_total 5992
telemt_upstream_connect_success_total 5900
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 8203
telemt_me_reconnect_success_total 3821
telemt_me_reader_eof_total 4077
telemt_me_idle_close_by_peer_total 4077
telemt_me_route_drop_no_conn_total 146802
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1192
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 863
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4029
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 3810
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 369531
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 5349552101 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 115995203409 (108.03 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19505.6 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285603
telemt_connections_bad_total 19304
telemt_handshake_timeouts_total 25018
telemt_upstream_connect_attempt_total 5277
telemt_upstream_connect_success_total 5277
telemt_upstream_connect_attempts_per_request{bucket="1"} 5277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 5275
telemt_me_reconnect_success_total 4259
telemt_me_reader_eof_total 4460
telemt_me_idle_close_by_peer_total 4460
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 93651
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229802
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4332
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4246
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 229532
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 3593180156 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 68972533540 (64.24 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19505.2 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300766
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 1977
telemt_upstream_connect_attempt_total 6119
telemt_upstream_connect_success_total 6096
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 6119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 5091
telemt_me_reconnect_success_total 5052
telemt_me_reader_eof_total 5191
telemt_me_idle_close_by_peer_total 5191
telemt_me_route_drop_no_conn_total 110964
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283773
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1591
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5128
telemt_me_writer_restored_same_endpoint_total 5052
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 283692
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 5563750420 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 94230074612 (87.76 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 64
```