# Server Metrics 2026-03-15 04:53:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 23952.5 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304600
telemt_connections_bad_total 4124
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 5150
telemt_upstream_connect_success_total 5132
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3948
telemt_me_reconnect_success_total 3928
telemt_me_reader_eof_total 4143
telemt_me_idle_close_by_peer_total 4143
telemt_me_route_drop_no_conn_total 96326
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270933
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 677
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3972
telemt_me_writer_restored_same_endpoint_total 3917
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 270914
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 3005526468 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 96835705636 (90.19 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 23953.2 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119267
telemt_connections_bad_total 18095
telemt_handshake_timeouts_total 4382
telemt_upstream_connect_attempt_total 7268
telemt_upstream_connect_success_total 7236
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5744
telemt_me_reconnect_success_total 5715
telemt_me_reader_eof_total 6036
telemt_me_idle_close_by_peer_total 6036
telemt_me_route_drop_no_conn_total 25606
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93891
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5722
telemt_me_writer_restored_same_endpoint_total 5707
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 94186
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 1816869687 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 28158941184 (26.23 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 23953.3 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218094
telemt_connections_bad_total 3656
telemt_handshake_timeouts_total 24290
telemt_upstream_connect_attempt_total 5609
telemt_upstream_connect_success_total 5587
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4398
telemt_me_reconnect_success_total 4379
telemt_me_reader_eof_total 4635
telemt_me_idle_close_by_peer_total 4635
telemt_me_route_drop_no_conn_total 49097
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183245
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
telemt_me_writer_removed_unexpected_total 4425
telemt_me_writer_restored_same_endpoint_total 4360
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 183112
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 1748434476 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 62425516488 (58.14 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 23953.1 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165124
telemt_connections_bad_total 34462
telemt_handshake_timeouts_total 10699
telemt_upstream_connect_attempt_total 8406
telemt_upstream_connect_success_total 8229
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11792
telemt_me_reconnect_success_total 7021
telemt_me_reader_eof_total 7410
telemt_me_idle_close_by_peer_total 7410
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 35254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117149
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
telemt_me_writer_removed_unexpected_total 7229
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6998
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 117152
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 971465940 (926.46 MB)
telemt_user_octets_to_client{user="hello"} 40053928356 (37.30 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 23953.8 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103520
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 1195
telemt_upstream_connect_attempt_total 5540
telemt_upstream_connect_success_total 5516
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4327
telemt_me_reconnect_success_total 4309
telemt_me_reader_eof_total 4594
telemt_me_idle_close_by_peer_total 4594
telemt_me_route_drop_no_conn_total 27996
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98921
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
telemt_me_writer_removed_unexpected_total 4350
telemt_me_writer_restored_same_endpoint_total 4301
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 98918
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 902603012 (860.79 MB)
telemt_user_octets_to_client{user="hello"} 32408505928 (30.18 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 56
```