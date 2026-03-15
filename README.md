# Server Metrics 2026-03-15 06:50:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 30977.9 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509957
telemt_connections_bad_total 10831
telemt_handshake_timeouts_total 3604
telemt_upstream_connect_attempt_total 6531
telemt_upstream_connect_success_total 6505
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4973
telemt_me_reconnect_success_total 4947
telemt_me_reader_eof_total 5227
telemt_me_idle_close_by_peer_total 5227
telemt_me_route_drop_no_conn_total 156447
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432339
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5007
telemt_me_writer_restored_same_endpoint_total 4936
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 432346
telemt_user_connections_current{user="hello"} 1580
telemt_user_octets_from_client{user="hello"} 4990687276 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 153097142336 (142.58 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 30978.7 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183824
telemt_connections_bad_total 18330
telemt_handshake_timeouts_total 5635
telemt_upstream_connect_attempt_total 8766
telemt_upstream_connect_success_total 8721
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6882
telemt_me_reconnect_success_total 6845
telemt_me_reader_eof_total 7240
telemt_me_idle_close_by_peer_total 7240
telemt_me_route_drop_no_conn_total 46899
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154417
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 502
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6873
telemt_me_writer_restored_same_endpoint_total 6837
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 154709
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2521308551 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 56604898856 (52.72 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 30978.8 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336761
telemt_connections_bad_total 9421
telemt_handshake_timeouts_total 31213
telemt_upstream_connect_attempt_total 7158
telemt_upstream_connect_success_total 7126
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5589
telemt_me_reconnect_success_total 5559
telemt_me_reader_eof_total 5883
telemt_me_idle_close_by_peer_total 5883
telemt_me_route_drop_no_conn_total 86298
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 546
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5619
telemt_me_writer_restored_same_endpoint_total 5540
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 280927
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 4372923260 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 118389475428 (110.26 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 30978.5 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232125
telemt_connections_bad_total 42288
telemt_handshake_timeouts_total 14758
telemt_upstream_connect_attempt_total 10450
telemt_upstream_connect_success_total 10210
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 10450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 18547
telemt_me_reconnect_success_total 8648
telemt_me_reader_eof_total 9233
telemt_me_idle_close_by_peer_total 9233
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 55557
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170200
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9031
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 8622
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 170203
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 1462251136 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 59019122184 (54.97 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 30979.2 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170291
telemt_connections_bad_total 247
telemt_handshake_timeouts_total 1635
telemt_upstream_connect_attempt_total 6956
telemt_upstream_connect_success_total 6928
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5394
telemt_me_reconnect_success_total 5370
telemt_me_reader_eof_total 5732
telemt_me_idle_close_by_peer_total 5732
telemt_me_route_drop_no_conn_total 50642
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159955
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 640
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5422
telemt_me_writer_restored_same_endpoint_total 5362
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 159961
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 1540800520 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 58743178776 (54.71 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 89
```