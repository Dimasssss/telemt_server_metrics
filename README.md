# Server Metrics 2026-03-14 21:25:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 29273.4 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1072367
telemt_connections_bad_total 42569
telemt_handshake_timeouts_total 14804
telemt_upstream_connect_attempt_total 5341
telemt_upstream_connect_success_total 5318
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4620
telemt_me_reconnect_success_total 3812
telemt_me_reader_eof_total 4024
telemt_me_idle_close_by_peer_total 4024
telemt_me_route_drop_no_conn_total 409143
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955168
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3191
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2263
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 1195
telemt_desync_frames_bucket_total{bucket="gt_10"} 1242
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3898
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3803
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 955138
telemt_user_connections_current{user="hello"} 1191
telemt_user_octets_from_client{user="hello"} 16958650860 (15.79 GB)
telemt_user_octets_to_client{user="hello"} 320957893156 (298.92 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 29278.4 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422814
telemt_connections_bad_total 32317
telemt_handshake_timeouts_total 13068
telemt_upstream_connect_attempt_total 6281
telemt_upstream_connect_success_total 6219
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 483
telemt_me_reconnect_attempts_total 5512
telemt_me_reconnect_success_total 4714
telemt_me_reader_eof_total 4933
telemt_me_idle_close_by_peer_total 4933
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 123456
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353715
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1766
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1306
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 431
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4834
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4691
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 353659
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 5622059300 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 122523856292 (114.11 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 29141.3 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918273
telemt_connections_bad_total 3897
telemt_handshake_timeouts_total 229157
telemt_upstream_connect_attempt_total 5673
telemt_upstream_connect_success_total 5656
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 8077
telemt_me_reconnect_success_total 4163
telemt_me_reader_eof_total 4463
telemt_me_idle_close_by_peer_total 4463
telemt_me_route_drop_no_conn_total 205402
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587027
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2206
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 1365
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4333
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4130
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 586853
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 9025026484 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 219321229304 (204.26 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 28996.0 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487106
telemt_connections_bad_total 101132
telemt_handshake_timeouts_total 55327
telemt_upstream_connect_attempt_total 6686
telemt_upstream_connect_success_total 6685
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 6122
telemt_me_reconnect_success_total 5199
telemt_me_reader_eof_total 5462
telemt_me_idle_close_by_peer_total 5462
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 112948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322458
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 704
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5287
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5187
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 322372
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 4528989084 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 98811153964 (92.03 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 29291.2 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408544
telemt_connections_bad_total 1397
telemt_handshake_timeouts_total 4047
telemt_upstream_connect_attempt_total 6214
telemt_upstream_connect_success_total 6090
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 5281
telemt_me_reconnect_success_total 4603
telemt_me_reader_eof_total 4862
telemt_me_idle_close_by_peer_total 4862
telemt_me_route_drop_no_conn_total 128431
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379326
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1084
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4705
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4585
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 379291
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 5997202892 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 155940548300 (145.23 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 53
```