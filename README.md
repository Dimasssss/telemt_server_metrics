# Server Metrics 2026-03-15 05:39:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 26700.4 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362224
telemt_connections_bad_total 5552
telemt_handshake_timeouts_total 1669
telemt_upstream_connect_attempt_total 5687
telemt_upstream_connect_success_total 5666
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4351
telemt_me_reconnect_success_total 4329
telemt_me_reader_eof_total 4579
telemt_me_idle_close_by_peer_total 4579
telemt_me_route_drop_no_conn_total 116026
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322923
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4380
telemt_me_writer_restored_same_endpoint_total 4318
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 322939
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 3681636572 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 117782844512 (109.69 GB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 26701.0 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140190
telemt_connections_bad_total 18306
telemt_handshake_timeouts_total 4788
telemt_upstream_connect_attempt_total 7840
telemt_upstream_connect_success_total 7804
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 7840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6182
telemt_me_reconnect_success_total 6151
telemt_me_reader_eof_total 6506
telemt_me_idle_close_by_peer_total 6506
telemt_me_route_drop_no_conn_total 32679
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113504
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 297
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6169
telemt_me_writer_restored_same_endpoint_total 6143
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 113800
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 2030004723 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 37532831824 (34.96 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 26701.3 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262010
telemt_connections_bad_total 5503
telemt_handshake_timeouts_total 27770
telemt_upstream_connect_attempt_total 6221
telemt_upstream_connect_success_total 6194
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4874
telemt_me_reconnect_success_total 4849
telemt_me_reader_eof_total 5126
telemt_me_idle_close_by_peer_total 5126
telemt_me_route_drop_no_conn_total 63503
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217568
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4900
telemt_me_writer_restored_same_endpoint_total 4830
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 217377
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 3459324904 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 88974817728 (82.86 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 26701.2 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189565
telemt_connections_bad_total 36853
telemt_handshake_timeouts_total 13536
telemt_upstream_connect_attempt_total 9113
telemt_upstream_connect_success_total 8921
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 9113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12354
telemt_me_reconnect_success_total 7580
telemt_me_reader_eof_total 7992
telemt_me_idle_close_by_peer_total 7992
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 42145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135563
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 228
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7789
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7557
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 135566
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 1122631904 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 47843929716 (44.56 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 26701.9 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124375
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 1365
telemt_upstream_connect_attempt_total 6127
telemt_upstream_connect_success_total 6101
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4783
telemt_me_reconnect_success_total 4762
telemt_me_reader_eof_total 5080
telemt_me_idle_close_by_peer_total 5080
telemt_me_route_drop_no_conn_total 34617
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118594
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4810
telemt_me_writer_restored_same_endpoint_total 4754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 118592
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 1118874280 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 40352085236 (37.58 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 83
```