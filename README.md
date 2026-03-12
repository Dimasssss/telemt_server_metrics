# Server Metrics 2026-03-12 05:29:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27848.3 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300221
telemt_connections_bad_total 1481
telemt_handshake_timeouts_total 5439
telemt_upstream_connect_attempt_total 6200
telemt_upstream_connect_success_total 6200
telemt_upstream_connect_attempts_per_request{bucket="1"} 6200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4836
telemt_me_reconnect_success_total 4818
telemt_me_reader_eof_total 5096
telemt_me_idle_close_by_peer_total 5096
telemt_me_route_drop_no_conn_total 107059
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285499
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 723
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4868
telemt_me_writer_restored_same_endpoint_total 4802
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 285218
telemt_user_connections_current{user="hello"} 1057
telemt_user_octets_from_client{user="hello"} 2767038036 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 88590705188 (82.51 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27849.1 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97782
telemt_connections_bad_total 693
telemt_handshake_timeouts_total 2136
telemt_upstream_connect_attempt_total 7530
telemt_upstream_connect_success_total 7525
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 5981
telemt_me_reconnect_success_total 5945
telemt_me_reader_eof_total 6320
telemt_me_idle_close_by_peer_total 6320
telemt_me_route_drop_no_conn_total 29050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5995
telemt_me_writer_restored_same_endpoint_total 5936
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 88777
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1422797359 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 36338206890 (33.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27848.8 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401350
telemt_connections_bad_total 2070
telemt_handshake_timeouts_total 27173
telemt_upstream_connect_attempt_total 7821
telemt_upstream_connect_success_total 7819
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 6129
telemt_me_reconnect_success_total 6067
telemt_me_reader_eof_total 6346
telemt_me_idle_close_by_peer_total 6346
telemt_me_route_drop_no_conn_total 54950
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166221
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 657
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6042
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6026
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 166537
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 1756421776 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50940950945 (47.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27849.2 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141435
telemt_connections_bad_total 1690
telemt_handshake_timeouts_total 9689
telemt_upstream_connect_attempt_total 8120
telemt_upstream_connect_success_total 8085
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6716
telemt_me_reconnect_success_total 6693
telemt_me_reader_eof_total 7101
telemt_me_idle_close_by_peer_total 7101
telemt_me_route_drop_no_conn_total 47716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127910
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6734
telemt_me_writer_restored_same_endpoint_total 6672
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 127887
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1154943768 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 36633892748 (34.12 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27849.0 (7h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163260
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 998
telemt_upstream_connect_attempt_total 10067
telemt_upstream_connect_success_total 9955
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 10067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 10058
telemt_me_reconnect_success_total 8552
telemt_me_reader_eof_total 8897
telemt_me_idle_close_by_peer_total 8897
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 46768
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155994
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 583
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 8670
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8533
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 156019
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 1386776820 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 35197583628 (32.78 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 70
```