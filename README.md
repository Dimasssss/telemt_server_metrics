# Server Metrics 2026-03-14 13:34:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 1017.0 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42428
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 664
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 137
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 15428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40088
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_user_connections_total{user="hello"} 40083
telemt_user_connections_current{user="hello"} 1698
telemt_user_octets_from_client{user="hello"} 553830816 (528.17 MB)
telemt_user_octets_to_client{user="hello"} 8549034248 (7.96 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 1022.4 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18259
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 228
telemt_upstream_connect_success_total 226
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 117
telemt_me_reconnect_success_total 116
telemt_me_reader_eof_total 86
telemt_me_idle_close_by_peer_total 86
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 5238
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14556
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 108
telemt_me_writer_restored_same_endpoint_total 105
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 14524
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 270755828 (258.21 MB)
telemt_user_octets_to_client{user="hello"} 5246937360 (4.89 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 885.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26063
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 4625
telemt_upstream_connect_attempt_total 120
telemt_upstream_connect_success_total 119
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 5864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20328
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 20308
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 230309372 (219.64 MB)
telemt_user_octets_to_client{user="hello"} 5462869936 (5.09 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 229779.6 (63h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2698833
telemt_connections_bad_total 23547
telemt_handshake_timeouts_total 360544
telemt_upstream_connect_attempt_total 70568
telemt_upstream_connect_success_total 68056
telemt_upstream_connect_fail_total 2375
telemt_upstream_connect_attempts_per_request{bucket="1"} 70294
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2374
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21026
telemt_me_reconnect_attempts_total 62366
telemt_me_reconnect_success_total 49571
telemt_me_reader_eof_total 53101
telemt_me_idle_close_by_peer_total 53093
telemt_me_route_drop_no_conn_total 888931
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2099555
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 50403
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49546
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 832
telemt_user_connections_total{user="hello"} 2106311
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 31011051739 (28.88 GB)
telemt_user_octets_to_client{user="hello"} 747074502866 (695.77 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 1035.2 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16848
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 185
telemt_upstream_connect_success_total 178
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 77
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 55
telemt_me_idle_close_by_peer_total 55
telemt_me_route_drop_no_conn_total 5360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15211
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_restored_same_endpoint_total 57
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 15213
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 203015372 (193.61 MB)
telemt_user_octets_to_client{user="hello"} 6991431520 (6.51 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 101
```