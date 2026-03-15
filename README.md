# Server Metrics 2026-03-15 06:30:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 29755.6 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468563
telemt_connections_bad_total 6626
telemt_handshake_timeouts_total 2800
telemt_upstream_connect_attempt_total 6276
telemt_upstream_connect_success_total 6250
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4787
telemt_me_reconnect_success_total 4763
telemt_me_reader_eof_total 5032
telemt_me_idle_close_by_peer_total 5032
telemt_me_route_drop_no_conn_total 143667
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399019
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1024
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 701
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4816
telemt_me_writer_restored_same_endpoint_total 4752
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 399029
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 4600233992 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 143224259236 (133.39 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 29756.4 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171192
telemt_connections_bad_total 18315
telemt_handshake_timeouts_total 5476
telemt_upstream_connect_attempt_total 8450
telemt_upstream_connect_success_total 8407
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6635
telemt_me_reconnect_success_total 6601
telemt_me_reader_eof_total 6987
telemt_me_idle_close_by_peer_total 6987
telemt_me_route_drop_no_conn_total 42182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142375
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6625
telemt_me_writer_restored_same_endpoint_total 6593
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 142668
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 2359614103 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 51938798972 (48.37 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 29756.6 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314183
telemt_connections_bad_total 8343
telemt_handshake_timeouts_total 30442
telemt_upstream_connect_attempt_total 6887
telemt_upstream_connect_success_total 6855
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 6887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5387
telemt_me_reconnect_success_total 5359
telemt_me_reader_eof_total 5668
telemt_me_idle_close_by_peer_total 5668
telemt_me_route_drop_no_conn_total 80071
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262144
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 5417
telemt_me_writer_restored_same_endpoint_total 5340
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 261944
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 4152168328 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 109132922176 (101.64 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 29756.4 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217165
telemt_connections_bad_total 39278
telemt_handshake_timeouts_total 14199
telemt_upstream_connect_attempt_total 10156
telemt_upstream_connect_success_total 9934
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 10155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 15689
telemt_me_reconnect_success_total 8448
telemt_me_reader_eof_total 8946
telemt_me_idle_close_by_peer_total 8946
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 51694
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159254
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8744
telemt_me_refill_failed_total 225
telemt_me_writer_restored_same_endpoint_total 8422
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 159257
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1360272012 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 56386372856 (52.51 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 29757.1 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156358
telemt_connections_bad_total 237
telemt_handshake_timeouts_total 1572
telemt_upstream_connect_attempt_total 6695
telemt_upstream_connect_success_total 6667
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5198
telemt_me_reconnect_success_total 5175
telemt_me_reader_eof_total 5520
telemt_me_idle_close_by_peer_total 5520
telemt_me_route_drop_no_conn_total 44600
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146772
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5225
telemt_me_writer_restored_same_endpoint_total 5167
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 146787
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 1425559220 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 51836418936 (48.28 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 101
```