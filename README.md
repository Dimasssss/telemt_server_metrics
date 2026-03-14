# Server Metrics 2026-03-14 13:39:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 1323.5 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54208
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 788
telemt_upstream_connect_attempt_total 233
telemt_upstream_connect_success_total 231
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 116
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 20294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51487
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 117
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 51483
telemt_user_connections_current{user="hello"} 1598
telemt_user_octets_from_client{user="hello"} 996154632 (950.01 MB)
telemt_user_octets_to_client{user="hello"} 11018852024 (10.26 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 1328.9 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23236
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 1036
telemt_upstream_connect_attempt_total 298
telemt_upstream_connect_success_total 296
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 185
telemt_me_reader_eof_total 156
telemt_me_idle_close_by_peer_total 156
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 6920
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18751
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_restored_same_endpoint_total 174
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_user_connections_total{user="hello"} 18718
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 408997708 (390.05 MB)
telemt_user_octets_to_client{user="hello"} 7389953792 (6.88 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 1191.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33927
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 5507
telemt_upstream_connect_attempt_total 220
telemt_upstream_connect_success_total 217
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 108
telemt_me_reconnect_success_total 103
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 8292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26683
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 26663
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 447818756 (427.07 MB)
telemt_user_octets_to_client{user="hello"} 7726563432 (7.20 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 230083.8 (63h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2703095
telemt_connections_bad_total 23548
telemt_handshake_timeouts_total 362838
telemt_upstream_connect_attempt_total 70631
telemt_upstream_connect_success_total 68118
telemt_upstream_connect_fail_total 2375
telemt_upstream_connect_attempts_per_request{bucket="1"} 70356
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2374
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21036
telemt_me_reconnect_attempts_total 62429
telemt_me_reconnect_success_total 49633
telemt_me_reader_eof_total 53164
telemt_me_idle_close_by_peer_total 53156
telemt_me_route_drop_no_conn_total 889733
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2101556
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
telemt_me_writer_removed_unexpected_total 50466
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49608
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 833
telemt_user_connections_total{user="hello"} 2108314
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 31025647143 (28.89 GB)
telemt_user_octets_to_client{user="hello"} 747557396518 (696.22 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 1341.8 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22004
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 273
telemt_upstream_connect_success_total 266
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 157
telemt_me_reconnect_success_total 155
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 7222
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19797
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 159
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 19799
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 242719548 (231.48 MB)
telemt_user_octets_to_client{user="hello"} 8777739576 (8.17 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 101
```