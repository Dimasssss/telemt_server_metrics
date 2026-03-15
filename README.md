# Server Metrics 2026-03-15 05:44:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 27005.8 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370151
telemt_connections_bad_total 5626
telemt_handshake_timeouts_total 1726
telemt_upstream_connect_attempt_total 5712
telemt_upstream_connect_success_total 5691
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4376
telemt_me_reconnect_success_total 4354
telemt_me_reader_eof_total 4604
telemt_me_idle_close_by_peer_total 4604
telemt_me_route_drop_no_conn_total 118256
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330022
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4405
telemt_me_writer_restored_same_endpoint_total 4343
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 330037
telemt_user_connections_current{user="hello"} 1201
telemt_user_octets_from_client{user="hello"} 3746958860 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 120434532972 (112.16 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 27006.5 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142513
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 4817
telemt_upstream_connect_attempt_total 7870
telemt_upstream_connect_success_total 7834
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 7870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6212
telemt_me_reconnect_success_total 6181
telemt_me_reader_eof_total 6537
telemt_me_idle_close_by_peer_total 6537
telemt_me_route_drop_no_conn_total 33326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115712
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6200
telemt_me_writer_restored_same_endpoint_total 6173
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 116008
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 2047091255 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 38188774536 (35.57 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 27006.7 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267137
telemt_connections_bad_total 5733
telemt_handshake_timeouts_total 28291
telemt_upstream_connect_attempt_total 6278
telemt_upstream_connect_success_total 6251
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4931
telemt_me_reconnect_success_total 4906
telemt_me_reader_eof_total 5184
telemt_me_idle_close_by_peer_total 5184
telemt_me_route_drop_no_conn_total 65115
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221828
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 371
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4958
telemt_me_writer_restored_same_endpoint_total 4887
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 221633
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 3631636280 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 90963363472 (84.72 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 27006.5 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192255
telemt_connections_bad_total 37114
telemt_handshake_timeouts_total 13575
telemt_upstream_connect_attempt_total 9185
telemt_upstream_connect_success_total 8993
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 9185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12426
telemt_me_reconnect_success_total 7651
telemt_me_reader_eof_total 8063
telemt_me_idle_close_by_peer_total 8063
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 43235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137766
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7860
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7628
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 137769
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 1158383356 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 48280182428 (44.96 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 27007.5 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126754
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 6166
telemt_upstream_connect_success_total 6140
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4822
telemt_me_reconnect_success_total 4801
telemt_me_reader_eof_total 5119
telemt_me_idle_close_by_peer_total 5119
telemt_me_route_drop_no_conn_total 35304
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120781
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4849
telemt_me_writer_restored_same_endpoint_total 4793
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 120783
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 1140105400 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 42133576472 (39.24 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 61
```