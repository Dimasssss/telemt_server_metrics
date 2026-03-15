# Server Metrics 2026-03-15 04:43:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 23341.2 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295206
telemt_connections_bad_total 4003
telemt_handshake_timeouts_total 1420
telemt_upstream_connect_attempt_total 4938
telemt_upstream_connect_success_total 4920
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3780
telemt_me_reconnect_success_total 3759
telemt_me_reader_eof_total 3974
telemt_me_idle_close_by_peer_total 3974
telemt_me_route_drop_no_conn_total 93570
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262243
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3803
telemt_me_writer_restored_same_endpoint_total 3748
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 262213
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 2879601332 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 93536335512 (87.11 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 23341.7 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115836
telemt_connections_bad_total 18095
telemt_handshake_timeouts_total 4376
telemt_upstream_connect_attempt_total 7058
telemt_upstream_connect_success_total 7030
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5581
telemt_me_reconnect_success_total 5554
telemt_me_reader_eof_total 5849
telemt_me_idle_close_by_peer_total 5849
telemt_me_route_drop_no_conn_total 24440
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90535
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 197
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5560
telemt_me_writer_restored_same_endpoint_total 5546
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 90830
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 1789897307 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 26060780276 (24.27 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 23342.1 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208180
telemt_connections_bad_total 3656
telemt_handshake_timeouts_total 23279
telemt_upstream_connect_attempt_total 5447
telemt_upstream_connect_success_total 5425
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4279
telemt_me_reconnect_success_total 4260
telemt_me_reader_eof_total 4502
telemt_me_idle_close_by_peer_total 4502
telemt_me_route_drop_no_conn_total 46869
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177147
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 296
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4304
telemt_me_writer_restored_same_endpoint_total 4241
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 177020
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 1563585312 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 57807027268 (53.84 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 23341.7 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160459
telemt_connections_bad_total 33975
telemt_handshake_timeouts_total 9664
telemt_upstream_connect_attempt_total 8229
telemt_upstream_connect_success_total 8058
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 8229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11664
telemt_me_reconnect_success_total 6893
telemt_me_reader_eof_total 7271
telemt_me_idle_close_by_peer_total 7271
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 34083
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114200
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7101
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6873
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 114203
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 949217800 (905.24 MB)
telemt_user_octets_to_client{user="hello"} 38104221304 (35.49 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 23343.0 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99728
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 1173
telemt_upstream_connect_attempt_total 5380
telemt_upstream_connect_success_total 5356
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4210
telemt_me_reconnect_success_total 4193
telemt_me_reader_eof_total 4468
telemt_me_idle_close_by_peer_total 4468
telemt_me_route_drop_no_conn_total 26546
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95265
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 414
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4233
telemt_me_writer_restored_same_endpoint_total 4185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 95262
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 830918484 (792.43 MB)
telemt_user_octets_to_client{user="hello"} 30453297600 (28.36 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```