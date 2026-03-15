# Server Metrics 2026-03-15 06:25:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 29449.9 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459549
telemt_connections_bad_total 6593
telemt_handshake_timeouts_total 2650
telemt_upstream_connect_attempt_total 6245
telemt_upstream_connect_success_total 6219
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4774
telemt_me_reconnect_success_total 4750
telemt_me_reader_eof_total 5017
telemt_me_idle_close_by_peer_total 5017
telemt_me_route_drop_no_conn_total 141067
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390936
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1002
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4801
telemt_me_writer_restored_same_endpoint_total 4739
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 390949
telemt_user_connections_current{user="hello"} 1478
telemt_user_octets_from_client{user="hello"} 4523611000 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 140909339684 (131.23 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 29450.8 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167335
telemt_connections_bad_total 18314
telemt_handshake_timeouts_total 5425
telemt_upstream_connect_attempt_total 8406
telemt_upstream_connect_success_total 8366
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 8406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6613
telemt_me_reconnect_success_total 6580
telemt_me_reader_eof_total 6966
telemt_me_idle_close_by_peer_total 6966
telemt_me_route_drop_no_conn_total 41204
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138696
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 431
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6604
telemt_me_writer_restored_same_endpoint_total 6572
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 138991
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 2311327455 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 49377899380 (45.99 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 29451.0 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308973
telemt_connections_bad_total 8114
telemt_handshake_timeouts_total 30275
telemt_upstream_connect_attempt_total 6847
telemt_upstream_connect_success_total 6817
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 6847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5366
telemt_me_reconnect_success_total 5338
telemt_me_reader_eof_total 5647
telemt_me_idle_close_by_peer_total 5647
telemt_me_route_drop_no_conn_total 78341
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257838
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 498
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 283
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5396
telemt_me_writer_restored_same_endpoint_total 5319
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 257638
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 4102533844 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 107394997284 (100.02 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 29450.7 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214386
telemt_connections_bad_total 39046
telemt_handshake_timeouts_total 14109
telemt_upstream_connect_attempt_total 10073
telemt_upstream_connect_success_total 9854
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 10073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 15621
telemt_me_reconnect_success_total 8380
telemt_me_reader_eof_total 8878
telemt_me_idle_close_by_peer_total 8878
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 50828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156873
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8676
telemt_me_refill_failed_total 225
telemt_me_writer_restored_same_endpoint_total 8354
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 156876
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1343475972 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 55924833388 (52.08 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 29451.7 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152802
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 1549
telemt_upstream_connect_attempt_total 6644
telemt_upstream_connect_success_total 6616
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5169
telemt_me_reconnect_success_total 5146
telemt_me_reader_eof_total 5491
telemt_me_idle_close_by_peer_total 5491
telemt_me_route_drop_no_conn_total 43468
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143584
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 566
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5196
telemt_me_writer_restored_same_endpoint_total 5138
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 143603
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 1401616212 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 50244426836 (46.79 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 68
```