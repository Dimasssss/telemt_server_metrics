# Server Metrics 2026-03-15 05:29:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 26090.2 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347536
telemt_connections_bad_total 5179
telemt_handshake_timeouts_total 1600
telemt_upstream_connect_attempt_total 5552
telemt_upstream_connect_success_total 5531
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4259
telemt_me_reconnect_success_total 4238
telemt_me_reader_eof_total 4478
telemt_me_idle_close_by_peer_total 4478
telemt_me_route_drop_no_conn_total 111372
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310014
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4287
telemt_me_writer_restored_same_endpoint_total 4227
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 310032
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 3495429280 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 113420968716 (105.63 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 26090.8 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135177
telemt_connections_bad_total 18282
telemt_handshake_timeouts_total 4738
telemt_upstream_connect_attempt_total 7686
telemt_upstream_connect_success_total 7652
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6072
telemt_me_reconnect_success_total 6043
telemt_me_reader_eof_total 6385
telemt_me_idle_close_by_peer_total 6385
telemt_me_route_drop_no_conn_total 30652
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108726
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6055
telemt_me_writer_restored_same_endpoint_total 6035
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 109023
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 1950786819 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 35656605492 (33.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 26091.0 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252099
telemt_connections_bad_total 4976
telemt_handshake_timeouts_total 26986
telemt_upstream_connect_attempt_total 6006
telemt_upstream_connect_success_total 5979
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4704
telemt_me_reconnect_success_total 4681
telemt_me_reader_eof_total 4956
telemt_me_idle_close_by_peer_total 4956
telemt_me_route_drop_no_conn_total 60751
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209750
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4730
telemt_me_writer_restored_same_endpoint_total 4662
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 209567
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 3067900552 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 82380381516 (76.72 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 26090.9 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184121
telemt_connections_bad_total 36375
telemt_handshake_timeouts_total 13265
telemt_upstream_connect_attempt_total 8870
telemt_upstream_connect_success_total 8684
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 8870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12160
telemt_me_reconnect_success_total 7387
telemt_me_reader_eof_total 7799
telemt_me_idle_close_by_peer_total 7799
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 40471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130972
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7596
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7364
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 130975
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 1065833816 (1016.46 MB)
telemt_user_octets_to_client{user="hello"} 46319657364 (43.14 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 26091.7 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119529
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 1319
telemt_upstream_connect_attempt_total 5963
telemt_upstream_connect_success_total 5938
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4663
telemt_me_reconnect_success_total 4643
telemt_me_reader_eof_total 4953
telemt_me_idle_close_by_peer_total 4953
telemt_me_route_drop_no_conn_total 33237
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114159
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 476
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4690
telemt_me_writer_restored_same_endpoint_total 4635
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 114157
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 1091496640 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 39020725260 (36.34 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 63
```