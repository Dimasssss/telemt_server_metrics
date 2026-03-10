# Server Metrics 2026-03-10 20:06:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20367.0 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616387
telemt_connections_bad_total 8007
telemt_handshake_timeouts_total 5910
telemt_upstream_connect_attempt_total 4175
telemt_upstream_connect_success_total 4166
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 331
telemt_me_reconnect_attempts_total 13541
telemt_me_reconnect_success_total 3076
telemt_me_reader_eof_total 3426
telemt_me_idle_close_by_peer_total 3426
telemt_me_route_drop_no_conn_total 258538
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581765
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3071
telemt_desync_full_logged_total 829
telemt_desync_suppressed_total 2242
telemt_desync_frames_bucket_total{bucket="1_2"} 848
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3422
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 3070
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 581587
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 8379818140 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 171299331176 (159.53 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20423.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263196
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 16678
telemt_upstream_connect_attempt_total 9612
telemt_upstream_connect_success_total 6865
telemt_upstream_connect_fail_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 9612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1887
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2747
telemt_me_keepalive_timeout_total 728
telemt_me_reconnect_attempts_total 4602
telemt_me_reconnect_success_total 3812
telemt_me_reader_eof_total 3985
telemt_me_idle_close_by_peer_total 3983
telemt_me_route_drop_no_conn_total 142926
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225781
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1185
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3883
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3791
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 227081
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 2387047986 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 55611459486 (51.79 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20423.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440626
telemt_connections_bad_total 1520
telemt_handshake_timeouts_total 32415
telemt_upstream_connect_attempt_total 6243
telemt_upstream_connect_success_total 6149
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 9649
telemt_me_reconnect_success_total 4019
telemt_me_reader_eof_total 4316
telemt_me_idle_close_by_peer_total 4316
telemt_me_route_drop_no_conn_total 151970
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381150
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1279
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 928
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4268
telemt_me_refill_failed_total 174
telemt_me_writer_restored_same_endpoint_total 4008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 382095
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 5504316281 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 118846683421 (110.68 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20424.0 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295790
telemt_connections_bad_total 20144
telemt_handshake_timeouts_total 25818
telemt_upstream_connect_attempt_total 5578
telemt_upstream_connect_success_total 5578
telemt_upstream_connect_attempts_per_request{bucket="1"} 5578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 5531
telemt_me_reconnect_success_total 4514
telemt_me_reader_eof_total 4718
telemt_me_idle_close_by_peer_total 4718
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 96604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238190
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 641
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4590
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4501
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 237892
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 3681248368 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 73221819612 (68.19 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20423.6 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311140
telemt_connections_bad_total 882
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 6492
telemt_upstream_connect_success_total 6466
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6441
telemt_me_reconnect_success_total 5378
telemt_me_reader_eof_total 5555
telemt_me_idle_close_by_peer_total 5555
telemt_me_route_drop_no_conn_total 114264
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293218
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1657
telemt_desync_full_logged_total 618
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 702
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5493
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5378
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 293133
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 5682870564 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 97354240080 (90.67 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 73
```