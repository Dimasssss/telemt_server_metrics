# Server Metrics 2026-03-12 04:48:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25398.8 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249024
telemt_connections_bad_total 1390
telemt_handshake_timeouts_total 3843
telemt_upstream_connect_attempt_total 5782
telemt_upstream_connect_success_total 5782
telemt_upstream_connect_attempts_per_request{bucket="1"} 5782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 4504
telemt_me_reconnect_success_total 4487
telemt_me_reader_eof_total 4746
telemt_me_idle_close_by_peer_total 4746
telemt_me_route_drop_no_conn_total 88883
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237217
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 500
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4533
telemt_me_writer_restored_same_endpoint_total 4471
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 236951
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 2331129988 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 73295681104 (68.26 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25399.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83485
telemt_connections_bad_total 628
telemt_handshake_timeouts_total 1625
telemt_upstream_connect_attempt_total 7031
telemt_upstream_connect_success_total 7028
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 5568
telemt_me_reconnect_success_total 5536
telemt_me_reader_eof_total 5887
telemt_me_idle_close_by_peer_total 5887
telemt_me_route_drop_no_conn_total 24414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 218
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5580
telemt_me_writer_restored_same_endpoint_total 5527
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 75538
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 1201557711 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 27612178834 (25.72 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25399.5 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366549
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 23669
telemt_upstream_connect_attempt_total 7332
telemt_upstream_connect_success_total 7330
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 5726
telemt_me_reconnect_success_total 5666
telemt_me_reader_eof_total 5924
telemt_me_idle_close_by_peer_total 5924
telemt_me_route_drop_no_conn_total 45814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 500
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5636
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5625
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 141074
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 1390605124 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 43266328905 (40.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25399.7 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122452
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 7847
telemt_upstream_connect_attempt_total 7568
telemt_upstream_connect_success_total 7534
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 6252
telemt_me_reconnect_success_total 6230
telemt_me_reader_eof_total 6620
telemt_me_idle_close_by_peer_total 6620
telemt_me_route_drop_no_conn_total 41360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6269
telemt_me_writer_restored_same_endpoint_total 6209
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 111315
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 869105248 (828.84 MB)
telemt_user_octets_to_client{user="hello"} 32014161668 (29.82 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25399.8 (7h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142629
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 840
telemt_upstream_connect_attempt_total 9435
telemt_upstream_connect_success_total 9330
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 9434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 9519
telemt_me_reconnect_success_total 8015
telemt_me_reader_eof_total 8341
telemt_me_idle_close_by_peer_total 8341
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 40147
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136350
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 507
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8129
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7998
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 136329
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 943066900 (899.38 MB)
telemt_user_octets_to_client{user="hello"} 30060143664 (28.00 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 44
```