# Server Metrics 2026-03-15 06:35:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 30060.8 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479079
telemt_connections_bad_total 7496
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 6355
telemt_upstream_connect_success_total 6329
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4841
telemt_me_reconnect_success_total 4817
telemt_me_reader_eof_total 5090
telemt_me_idle_close_by_peer_total 5090
telemt_me_route_drop_no_conn_total 146948
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407743
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 728
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4870
telemt_me_writer_restored_same_endpoint_total 4806
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 407753
telemt_user_connections_current{user="hello"} 1584
telemt_user_octets_from_client{user="hello"} 4682985420 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 145323602316 (135.34 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 30061.7 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174330
telemt_connections_bad_total 18315
telemt_handshake_timeouts_total 5497
telemt_upstream_connect_attempt_total 8554
telemt_upstream_connect_success_total 8510
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 8554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6715
telemt_me_reconnect_success_total 6680
telemt_me_reader_eof_total 7073
telemt_me_idle_close_by_peer_total 7073
telemt_me_route_drop_no_conn_total 43441
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145403
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 441
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6706
telemt_me_writer_restored_same_endpoint_total 6672
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 145696
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 2400723391 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 53003476276 (49.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 30061.8 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319854
telemt_connections_bad_total 8588
telemt_handshake_timeouts_total 30555
telemt_upstream_connect_attempt_total 6983
telemt_upstream_connect_success_total 6951
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 6983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5457
telemt_me_reconnect_success_total 5428
telemt_me_reader_eof_total 5743
telemt_me_idle_close_by_peer_total 5743
telemt_me_route_drop_no_conn_total 81977
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267162
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5486
telemt_me_writer_restored_same_endpoint_total 5409
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 266951
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 4214468812 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 110963288036 (103.34 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 30061.7 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220810
telemt_connections_bad_total 39834
telemt_handshake_timeouts_total 14307
telemt_upstream_connect_attempt_total 10253
telemt_upstream_connect_success_total 10022
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 10253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 17058
telemt_me_reconnect_success_total 8504
telemt_me_reader_eof_total 9045
telemt_me_idle_close_by_peer_total 9045
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 52674
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162084
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8843
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 8478
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 162088
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 1380032292 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 56976700080 (53.06 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 30062.5 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159951
telemt_connections_bad_total 246
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 6782
telemt_upstream_connect_success_total 6754
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5264
telemt_me_reconnect_success_total 5241
telemt_me_reader_eof_total 5593
telemt_me_idle_close_by_peer_total 5593
telemt_me_route_drop_no_conn_total 46235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150189
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 599
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5291
telemt_me_writer_restored_same_endpoint_total 5233
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 150194
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 1459258616 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 53262752808 (49.60 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 81
```