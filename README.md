# Server Metrics 2026-03-15 04:48:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 23646.8 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299633
telemt_connections_bad_total 4050
telemt_handshake_timeouts_total 1431
telemt_upstream_connect_attempt_total 5063
telemt_upstream_connect_success_total 5045
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3861
telemt_me_reconnect_success_total 3840
telemt_me_reader_eof_total 4056
telemt_me_idle_close_by_peer_total 4056
telemt_me_route_drop_no_conn_total 95032
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266348
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3885
telemt_me_writer_restored_same_endpoint_total 3829
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 266318
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 2924406680 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 94747794712 (88.24 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 23647.5 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117440
telemt_connections_bad_total 18095
telemt_handshake_timeouts_total 4382
telemt_upstream_connect_attempt_total 7206
telemt_upstream_connect_success_total 7174
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5682
telemt_me_reconnect_success_total 5655
telemt_me_reader_eof_total 5975
telemt_me_idle_close_by_peer_total 5975
telemt_me_route_drop_no_conn_total 24866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92115
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 207
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5661
telemt_me_writer_restored_same_endpoint_total 5647
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 92410
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 1801253931 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 26866775660 (25.02 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 23647.8 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212667
telemt_connections_bad_total 3656
telemt_handshake_timeouts_total 23874
telemt_upstream_connect_attempt_total 5559
telemt_upstream_connect_success_total 5537
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4348
telemt_me_reconnect_success_total 4329
telemt_me_reader_eof_total 4583
telemt_me_idle_close_by_peer_total 4583
telemt_me_route_drop_no_conn_total 47798
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4373
telemt_me_writer_restored_same_endpoint_total 4310
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 179655
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 1590764152 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 60859765672 (56.68 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 23647.5 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162907
telemt_connections_bad_total 34228
telemt_handshake_timeouts_total 10181
telemt_upstream_connect_attempt_total 8353
telemt_upstream_connect_success_total 8176
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11739
telemt_me_reconnect_success_total 6968
telemt_me_reader_eof_total 7357
telemt_me_idle_close_by_peer_total 7357
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 34682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115768
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7176
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6945
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 115771
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 962214368 (917.64 MB)
telemt_user_octets_to_client{user="hello"} 39125508828 (36.44 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 23648.7 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101525
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 1179
telemt_upstream_connect_attempt_total 5490
telemt_upstream_connect_success_total 5466
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4277
telemt_me_reconnect_success_total 4259
telemt_me_reader_eof_total 4544
telemt_me_idle_close_by_peer_total 4544
telemt_me_route_drop_no_conn_total 26911
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97000
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 416
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4300
telemt_me_writer_restored_same_endpoint_total 4251
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 96997
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 865866600 (825.75 MB)
telemt_user_octets_to_client{user="hello"} 31318458232 (29.17 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 38
```