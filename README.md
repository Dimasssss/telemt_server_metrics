# Server Metrics 2026-03-15 06:20:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 29144.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445618
telemt_connections_bad_total 6561
telemt_handshake_timeouts_total 2490
telemt_upstream_connect_attempt_total 6212
telemt_upstream_connect_success_total 6186
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4741
telemt_me_reconnect_success_total 4717
telemt_me_reader_eof_total 4984
telemt_me_idle_close_by_peer_total 4984
telemt_me_route_drop_no_conn_total 138278
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382891
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 974
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 669
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 400
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4768
telemt_me_writer_restored_same_endpoint_total 4706
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 382904
telemt_user_connections_current{user="hello"} 1489
telemt_user_octets_from_client{user="hello"} 4360158688 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 138586666396 (129.07 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 29145.0 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163867
telemt_connections_bad_total 18314
telemt_handshake_timeouts_total 5374
telemt_upstream_connect_attempt_total 8378
telemt_upstream_connect_success_total 8338
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 8378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 6552
telemt_me_reader_eof_total 6936
telemt_me_idle_close_by_peer_total 6936
telemt_me_route_drop_no_conn_total 40260
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135406
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6574
telemt_me_writer_restored_same_endpoint_total 6544
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 135701
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 2279976463 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 47104400608 (43.87 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 29145.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303251
telemt_connections_bad_total 7863
telemt_handshake_timeouts_total 30154
telemt_upstream_connect_attempt_total 6804
telemt_upstream_connect_success_total 6774
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 6804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5323
telemt_me_reconnect_success_total 5296
telemt_me_reader_eof_total 5603
telemt_me_idle_close_by_peer_total 5603
telemt_me_route_drop_no_conn_total 76765
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253087
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 483
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5352
telemt_me_writer_restored_same_endpoint_total 5277
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 252889
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 4050948932 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 105589287296 (98.34 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 29144.9 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211600
telemt_connections_bad_total 38811
telemt_handshake_timeouts_total 14024
telemt_upstream_connect_attempt_total 10004
telemt_upstream_connect_success_total 9785
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 10004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 15552
telemt_me_reconnect_success_total 8312
telemt_me_reader_eof_total 8810
telemt_me_idle_close_by_peer_total 8810
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 49927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154489
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
telemt_me_writer_removed_unexpected_total 8608
telemt_me_refill_failed_total 225
telemt_me_writer_restored_same_endpoint_total 8286
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 154492
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 1331399552 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 55515865276 (51.70 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 29146.1 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149496
telemt_connections_bad_total 235
telemt_handshake_timeouts_total 1533
telemt_upstream_connect_attempt_total 6606
telemt_upstream_connect_success_total 6578
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5131
telemt_me_reconnect_success_total 5108
telemt_me_reader_eof_total 5453
telemt_me_idle_close_by_peer_total 5453
telemt_me_route_drop_no_conn_total 42458
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140756
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5158
telemt_me_writer_restored_same_endpoint_total 5100
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 140775
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 1349164272 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 48838127200 (45.48 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 72
```