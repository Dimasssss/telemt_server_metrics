# Server Metrics 2026-03-12 10:04:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14750.8 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476539
telemt_connections_bad_total 1461
telemt_handshake_timeouts_total 2736
telemt_upstream_connect_attempt_total 2920
telemt_upstream_connect_success_total 2902
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 4758
telemt_me_reconnect_success_total 2122
telemt_me_reader_eof_total 2271
telemt_me_idle_close_by_peer_total 2271
telemt_me_route_drop_no_conn_total 163561
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461385
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2143
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1605
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2221
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 2109
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 461260
telemt_user_connections_current{user="hello"} 1439
telemt_user_octets_from_client{user="hello"} 7589737604 (7.07 GB)
telemt_user_octets_to_client{user="hello"} 125657096736 (117.03 GB)
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44371.0 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278189
telemt_connections_bad_total 2984
telemt_handshake_timeouts_total 8422
telemt_upstream_connect_attempt_total 11227
telemt_upstream_connect_success_total 11221
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 663
telemt_me_reconnect_attempts_total 8853
telemt_me_reconnect_success_total 8810
telemt_me_reader_eof_total 9358
telemt_me_idle_close_by_peer_total 9358
telemt_me_route_drop_no_conn_total 80866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248229
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 522
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8879
telemt_me_writer_restored_same_endpoint_total 8801
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 248667
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 3480143451 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 93120643370 (86.73 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44370.8 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718202
telemt_connections_bad_total 3409
telemt_handshake_timeouts_total 52640
telemt_upstream_connect_attempt_total 11253
telemt_upstream_connect_success_total 11248
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 8738
telemt_me_reconnect_success_total 8665
telemt_me_reader_eof_total 9102
telemt_me_idle_close_by_peer_total 9102
telemt_me_route_drop_no_conn_total 157707
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449622
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2062
telemt_desync_full_logged_total 615
telemt_desync_suppressed_total 1447
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 1084
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8674
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8624
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 449881
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 5421533748 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 148272806205 (138.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44371.3 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360212
telemt_connections_bad_total 1836
telemt_handshake_timeouts_total 26304
telemt_upstream_connect_attempt_total 12130
telemt_upstream_connect_success_total 12081
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 12130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 820
telemt_me_reconnect_attempts_total 9884
telemt_me_reconnect_success_total 9847
telemt_me_reader_eof_total 10447
telemt_me_idle_close_by_peer_total 10447
telemt_me_route_drop_no_conn_total 123192
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303965
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9910
telemt_me_writer_restored_same_endpoint_total 9826
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 303788
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 3733650372 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 119700491768 (111.48 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44371.1 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409617
telemt_connections_bad_total 462
telemt_handshake_timeouts_total 3161
telemt_upstream_connect_attempt_total 14449
telemt_upstream_connect_success_total 14276
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 13558
telemt_me_reconnect_success_total 12034
telemt_me_reader_eof_total 12524
telemt_me_idle_close_by_peer_total 12524
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 132420
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387100
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1640
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 12195
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12012
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 387032
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 4280964536 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 92953494776 (86.57 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 113
```