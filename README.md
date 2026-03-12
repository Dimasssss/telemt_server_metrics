# Server Metrics 2026-03-12 05:03:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26317.1 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267601
telemt_connections_bad_total 1396
telemt_handshake_timeouts_total 4139
telemt_upstream_connect_attempt_total 5952
telemt_upstream_connect_success_total 5952
telemt_upstream_connect_attempts_per_request{bucket="1"} 5952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4631
telemt_me_reconnect_success_total 4614
telemt_me_reader_eof_total 4880
telemt_me_idle_close_by_peer_total 4880
telemt_me_route_drop_no_conn_total 95551
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255020
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 538
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4661
telemt_me_writer_restored_same_endpoint_total 4598
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 254758
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 2463486396 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 78319146652 (72.94 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26317.8 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88582
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 1693
telemt_upstream_connect_attempt_total 7250
telemt_upstream_connect_success_total 7247
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 5744
telemt_me_reconnect_success_total 5712
telemt_me_reader_eof_total 6075
telemt_me_idle_close_by_peer_total 6075
telemt_me_route_drop_no_conn_total 26114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80123
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5756
telemt_me_writer_restored_same_endpoint_total 5703
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 80311
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 1278475595 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 30955948234 (28.83 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26317.7 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378378
telemt_connections_bad_total 2066
telemt_handshake_timeouts_total 24788
telemt_upstream_connect_attempt_total 7531
telemt_upstream_connect_success_total 7529
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 5882
telemt_me_reconnect_success_total 5820
telemt_me_reader_eof_total 6089
telemt_me_idle_close_by_peer_total 6089
telemt_me_route_drop_no_conn_total 49030
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150029
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 558
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5791
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5779
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 150345
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 1471400020 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 45579149857 (42.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26318.0 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129242
telemt_connections_bad_total 1687
telemt_handshake_timeouts_total 8517
telemt_upstream_connect_attempt_total 7778
telemt_upstream_connect_success_total 7743
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 6417
telemt_me_reconnect_success_total 6395
telemt_me_reader_eof_total 6794
telemt_me_idle_close_by_peer_total 6794
telemt_me_route_drop_no_conn_total 43357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117340
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6435
telemt_me_writer_restored_same_endpoint_total 6374
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 117316
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 952618816 (908.49 MB)
telemt_user_octets_to_client{user="hello"} 34265460648 (31.91 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26317.6 (7h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150074
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 9684
telemt_upstream_connect_success_total 9575
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 9721
telemt_me_reconnect_success_total 8216
telemt_me_reader_eof_total 8541
telemt_me_idle_close_by_peer_total 8541
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 42556
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143395
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 519
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8331
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8197
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 143376
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 1025716952 (978.20 MB)
telemt_user_octets_to_client{user="hello"} 32076810480 (29.87 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 67
```