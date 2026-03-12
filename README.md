# Server Metrics 2026-03-12 06:20:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 1289.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37978
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 325
telemt_upstream_connect_success_total 323
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 211
telemt_me_reconnect_success_total 210
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 12037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_restored_same_endpoint_total 197
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 36676
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 1186082176 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 10782907532 (10.04 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30910.4 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122458
telemt_connections_bad_total 1477
telemt_handshake_timeouts_total 3932
telemt_upstream_connect_attempt_total 8226
telemt_upstream_connect_success_total 8220
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 6504
telemt_me_reconnect_success_total 6466
telemt_me_reader_eof_total 6881
telemt_me_idle_close_by_peer_total 6881
telemt_me_route_drop_no_conn_total 36661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109973
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6522
telemt_me_writer_restored_same_endpoint_total 6457
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 110161
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 1678116647 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 46173212114 (43.00 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30910.1 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449681
telemt_connections_bad_total 2269
telemt_handshake_timeouts_total 32616
telemt_upstream_connect_attempt_total 8529
telemt_upstream_connect_success_total 8527
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6665
telemt_me_reconnect_success_total 6601
telemt_me_reader_eof_total 6916
telemt_me_idle_close_by_peer_total 6916
telemt_me_route_drop_no_conn_total 69242
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 881
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6581
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6560
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 208359
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 2178671416 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 62703443077 (58.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30910.6 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177244
telemt_connections_bad_total 1726
telemt_handshake_timeouts_total 12008
telemt_upstream_connect_attempt_total 8961
telemt_upstream_connect_success_total 8922
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 241
telemt_me_reconnect_attempts_total 7381
telemt_me_reconnect_success_total 7354
telemt_me_reader_eof_total 7811
telemt_me_idle_close_by_peer_total 7811
telemt_me_route_drop_no_conn_total 59179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7397
telemt_me_writer_restored_same_endpoint_total 7333
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 153347
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 1793586788 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 46584367164 (43.39 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30910.4 (8h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198505
telemt_connections_bad_total 308
telemt_handshake_timeouts_total 1217
telemt_upstream_connect_attempt_total 10735
telemt_upstream_connect_success_total 10614
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 10735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 10545
telemt_me_reconnect_success_total 9036
telemt_me_reader_eof_total 9418
telemt_me_idle_close_by_peer_total 9418
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 61023
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189586
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 695
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 9165
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9017
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 189540
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 1671142884 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 43780482548 (40.77 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 81
```