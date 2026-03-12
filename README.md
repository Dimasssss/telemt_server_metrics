# Server Metrics 2026-03-12 02:35:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17439.0 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144501
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2476
telemt_upstream_connect_attempt_total 4067
telemt_upstream_connect_success_total 4067
telemt_upstream_connect_attempts_per_request{bucket="1"} 4067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3178
telemt_me_reconnect_success_total 3165
telemt_me_reader_eof_total 3346
telemt_me_idle_close_by_peer_total 3346
telemt_me_route_drop_no_conn_total 52223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3202
telemt_me_writer_restored_same_endpoint_total 3149
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 136179
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 966209640 (921.45 MB)
telemt_user_octets_to_client{user="hello"} 40475030428 (37.70 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17439.7 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49342
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 824
telemt_upstream_connect_attempt_total 5067
telemt_upstream_connect_success_total 5064
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3993
telemt_me_reconnect_success_total 3966
telemt_me_reader_eof_total 4205
telemt_me_idle_close_by_peer_total 4205
telemt_me_route_drop_no_conn_total 13180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45982
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3995
telemt_me_writer_restored_same_endpoint_total 3957
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 46161
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 741403011 (707.06 MB)
telemt_user_octets_to_client{user="hello"} 17144952234 (15.97 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17439.4 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236809
telemt_connections_bad_total 1164
telemt_handshake_timeouts_total 15131
telemt_upstream_connect_attempt_total 5364
telemt_upstream_connect_success_total 5362
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 4149
telemt_me_reconnect_success_total 4095
telemt_me_reader_eof_total 4241
telemt_me_idle_close_by_peer_total 4241
telemt_me_route_drop_no_conn_total 26031
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84055
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 163
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4049
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4054
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 84393
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 718318368 (685.04 MB)
telemt_user_octets_to_client{user="hello"} 27341377833 (25.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17439.8 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75704
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 2188
telemt_upstream_connect_attempt_total 5226
telemt_upstream_connect_success_total 5198
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 4307
telemt_me_reconnect_success_total 4291
telemt_me_reader_eof_total 4543
telemt_me_idle_close_by_peer_total 4543
telemt_me_route_drop_no_conn_total 26095
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4317
telemt_me_writer_restored_same_endpoint_total 4270
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 72358
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 451454912 (430.54 MB)
telemt_user_octets_to_client{user="hello"} 16299368464 (15.18 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17439.6 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94586
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 629
telemt_upstream_connect_attempt_total 6521
telemt_upstream_connect_success_total 6456
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 6521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 7034
telemt_me_reconnect_success_total 5538
telemt_me_reader_eof_total 5753
telemt_me_idle_close_by_peer_total 5753
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 24050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90005
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 320
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5621
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5522
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 89983
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 519459560 (495.40 MB)
telemt_user_octets_to_client{user="hello"} 19947459100 (18.58 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 43
```