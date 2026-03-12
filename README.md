# Server Metrics 2026-03-12 04:58:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26010.7 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260761
telemt_connections_bad_total 1395
telemt_handshake_timeouts_total 3970
telemt_upstream_connect_attempt_total 5859
telemt_upstream_connect_success_total 5859
telemt_upstream_connect_attempts_per_request{bucket="1"} 5859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4581
telemt_me_reconnect_success_total 4564
telemt_me_reader_eof_total 4824
telemt_me_idle_close_by_peer_total 4824
telemt_me_route_drop_no_conn_total 92952
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248476
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4611
telemt_me_writer_restored_same_endpoint_total 4548
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 248205
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 2410617660 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 76209101828 (70.98 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26011.6 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86770
telemt_connections_bad_total 648
telemt_handshake_timeouts_total 1678
telemt_upstream_connect_attempt_total 7147
telemt_upstream_connect_success_total 7144
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 5684
telemt_me_reconnect_success_total 5652
telemt_me_reader_eof_total 6003
telemt_me_idle_close_by_peer_total 6003
telemt_me_route_drop_no_conn_total 25513
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78413
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 227
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5696
telemt_me_writer_restored_same_endpoint_total 5643
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 78601
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1260402727 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 29957288074 (27.90 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26011.3 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373179
telemt_connections_bad_total 1876
telemt_handshake_timeouts_total 24396
telemt_upstream_connect_attempt_total 7429
telemt_upstream_connect_success_total 7427
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 5823
telemt_me_reconnect_success_total 5762
telemt_me_reader_eof_total 6021
telemt_me_idle_close_by_peer_total 6021
telemt_me_route_drop_no_conn_total 47761
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146281
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5733
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5721
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 146597
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 1448648788 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 44539110153 (41.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26011.8 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126607
telemt_connections_bad_total 1683
telemt_handshake_timeouts_total 8258
telemt_upstream_connect_attempt_total 7679
telemt_upstream_connect_success_total 7645
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 6363
telemt_me_reconnect_success_total 6341
telemt_me_reader_eof_total 6732
telemt_me_idle_close_by_peer_total 6732
telemt_me_route_drop_no_conn_total 42479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114983
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6381
telemt_me_writer_restored_same_endpoint_total 6320
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 114960
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 916792976 (874.32 MB)
telemt_user_octets_to_client{user="hello"} 33431159480 (31.14 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26011.5 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147164
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 9554
telemt_upstream_connect_success_total 9449
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 9554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 9638
telemt_me_reconnect_success_total 8134
telemt_me_reader_eof_total 8459
telemt_me_idle_close_by_peer_total 8459
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 41568
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 517
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8248
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8116
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 140713
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 990227468 (944.35 MB)
telemt_user_octets_to_client{user="hello"} 31386337068 (29.23 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 80
```