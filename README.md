# Server Metrics 2026-03-12 06:15:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 983.6 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29118
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 208
telemt_upstream_connect_success_total 206
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 111
telemt_me_reconnect_success_total 111
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 9210
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 28312
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 1095135748 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 7952058508 (7.41 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30604.1 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119401
telemt_connections_bad_total 1338
telemt_handshake_timeouts_total 3573
telemt_upstream_connect_attempt_total 8115
telemt_upstream_connect_success_total 8110
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 6436
telemt_me_reconnect_success_total 6399
telemt_me_reader_eof_total 6804
telemt_me_idle_close_by_peer_total 6804
telemt_me_route_drop_no_conn_total 35800
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 328
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6454
telemt_me_writer_restored_same_endpoint_total 6390
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 107690
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 1649510515 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 45297582606 (42.19 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30603.9 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444984
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 32071
telemt_upstream_connect_attempt_total 8411
telemt_upstream_connect_success_total 8409
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6590
telemt_me_reconnect_success_total 6526
telemt_me_reader_eof_total 6834
telemt_me_idle_close_by_peer_total 6834
telemt_me_route_drop_no_conn_total 67884
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204042
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 848
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 430
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6506
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6485
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 204350
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 2101624160 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 61340400681 (57.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30604.3 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170759
telemt_connections_bad_total 1721
telemt_handshake_timeouts_total 11796
telemt_upstream_connect_attempt_total 8834
telemt_upstream_connect_success_total 8795
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 7297
telemt_me_reconnect_success_total 7270
telemt_me_reader_eof_total 7712
telemt_me_idle_close_by_peer_total 7712
telemt_me_route_drop_no_conn_total 57932
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150886
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7313
telemt_me_writer_restored_same_endpoint_total 7249
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 150748
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 1760010196 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 45940411372 (42.79 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30604.1 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194927
telemt_connections_bad_total 306
telemt_handshake_timeouts_total 1199
telemt_upstream_connect_attempt_total 10626
telemt_upstream_connect_success_total 10508
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 10626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 10482
telemt_me_reconnect_success_total 8973
telemt_me_reader_eof_total 9349
telemt_me_idle_close_by_peer_total 9349
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 59765
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186357
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 677
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9101
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8954
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 186311
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 1647629464 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 43147505600 (40.18 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 80
```