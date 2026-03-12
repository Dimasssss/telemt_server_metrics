# Server Metrics 2026-03-12 04:38:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24787.2 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237335
telemt_connections_bad_total 1389
telemt_handshake_timeouts_total 3802
telemt_upstream_connect_attempt_total 5647
telemt_upstream_connect_success_total 5647
telemt_upstream_connect_attempts_per_request{bucket="1"} 5647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 4412
telemt_me_reconnect_success_total 4395
telemt_me_reader_eof_total 4647
telemt_me_idle_close_by_peer_total 4647
telemt_me_route_drop_no_conn_total 84936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225802
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 459
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4441
telemt_me_writer_restored_same_endpoint_total 4379
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 225545
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 2261674016 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 70168197552 (65.35 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24787.9 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79837
telemt_connections_bad_total 363
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 6869
telemt_upstream_connect_success_total 6866
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 5449
telemt_me_reconnect_success_total 5417
telemt_me_reader_eof_total 5756
telemt_me_idle_close_by_peer_total 5756
telemt_me_route_drop_no_conn_total 23316
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 214
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5461
telemt_me_writer_restored_same_endpoint_total 5408
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 72529
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1163461779 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 25298482126 (23.56 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24787.7 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360291
telemt_connections_bad_total 1784
telemt_handshake_timeouts_total 23008
telemt_upstream_connect_attempt_total 7195
telemt_upstream_connect_success_total 7192
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 5632
telemt_me_reconnect_success_total 5572
telemt_me_reader_eof_total 5821
telemt_me_idle_close_by_peer_total 5821
telemt_me_route_drop_no_conn_total 43904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135334
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 457
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5543
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5531
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 135650
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 1334327532 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 42080962605 (39.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24788.1 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118737
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 7490
telemt_upstream_connect_attempt_total 7389
telemt_upstream_connect_success_total 7356
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 6117
telemt_me_reconnect_success_total 6095
telemt_me_reader_eof_total 6469
telemt_me_idle_close_by_peer_total 6469
telemt_me_route_drop_no_conn_total 39682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6133
telemt_me_writer_restored_same_endpoint_total 6074
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 108007
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 850176476 (810.79 MB)
telemt_user_octets_to_client{user="hello"} 30848244564 (28.73 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24788.0 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138524
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 808
telemt_upstream_connect_attempt_total 9227
telemt_upstream_connect_success_total 9127
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 9227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 9358
telemt_me_reconnect_success_total 7856
telemt_me_reader_eof_total 8159
telemt_me_idle_close_by_peer_total 8159
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 38449
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132488
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 500
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 7966
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7839
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 132467
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 901728896 (859.96 MB)
telemt_user_octets_to_client{user="hello"} 29075753504 (27.08 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 56
```