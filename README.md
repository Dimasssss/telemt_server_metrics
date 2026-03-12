# Server Metrics 2026-03-12 06:45:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2820.2 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81032
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 826
telemt_upstream_connect_attempt_total 602
telemt_upstream_connect_success_total 597
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 398
telemt_me_reconnect_success_total 397
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_route_drop_no_conn_total 25932
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77333
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 77294
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 1661642952 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 23696485984 (22.07 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32440.8 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137926
telemt_connections_bad_total 1864
telemt_handshake_timeouts_total 5435
telemt_upstream_connect_attempt_total 8504
telemt_upstream_connect_success_total 8499
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 6724
telemt_me_reconnect_success_total 6687
telemt_me_reader_eof_total 7110
telemt_me_idle_close_by_peer_total 7110
telemt_me_route_drop_no_conn_total 40831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6743
telemt_me_writer_restored_same_endpoint_total 6678
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 122801
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 1888675703 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 53117072530 (49.47 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32440.6 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476120
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 35195
telemt_upstream_connect_attempt_total 8778
telemt_upstream_connect_success_total 8776
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 6857
telemt_me_reconnect_success_total 6792
telemt_me_reader_eof_total 7116
telemt_me_idle_close_by_peer_total 7116
telemt_me_route_drop_no_conn_total 77064
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1013
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 693
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 514
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6775
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6751
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 231585
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 2443068636 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 80597245613 (75.06 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32441.1 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208307
telemt_connections_bad_total 1738
telemt_handshake_timeouts_total 13240
telemt_upstream_connect_attempt_total 9265
telemt_upstream_connect_success_total 9226
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 247
telemt_me_reconnect_attempts_total 7636
telemt_me_reconnect_success_total 7608
telemt_me_reader_eof_total 8076
telemt_me_idle_close_by_peer_total 8076
telemt_me_route_drop_no_conn_total 65599
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7652
telemt_me_writer_restored_same_endpoint_total 7587
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 168060
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 1913624136 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 52479412664 (48.88 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32440.8 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219508
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 1374
telemt_upstream_connect_attempt_total 10990
telemt_upstream_connect_success_total 10865
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 10990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 10747
telemt_me_reconnect_success_total 9236
telemt_me_reader_eof_total 9627
telemt_me_idle_close_by_peer_total 9627
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 67156
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208209
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 821
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9369
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9217
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 208165
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 1836119028 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 47757234964 (44.48 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 127
```