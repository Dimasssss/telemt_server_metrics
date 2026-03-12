# Server Metrics 2026-03-12 05:34:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28154.3 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307185
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 5472
telemt_upstream_connect_attempt_total 6300
telemt_upstream_connect_success_total 6300
telemt_upstream_connect_attempts_per_request{bucket="1"} 6300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4893
telemt_me_reconnect_success_total 4874
telemt_me_reader_eof_total 5159
telemt_me_idle_close_by_peer_total 5159
telemt_me_route_drop_no_conn_total 109295
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292309
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4925
telemt_me_writer_restored_same_endpoint_total 4858
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 292025
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 2828943176 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 90562338900 (84.34 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28155.0 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99775
telemt_connections_bad_total 698
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 7640
telemt_upstream_connect_success_total 7635
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 6048
telemt_me_reconnect_success_total 6012
telemt_me_reader_eof_total 6396
telemt_me_idle_close_by_peer_total 6396
telemt_me_route_drop_no_conn_total 29777
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6062
telemt_me_writer_restored_same_endpoint_total 6003
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 90646
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 1438432431 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 36917338962 (34.38 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28154.8 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406089
telemt_connections_bad_total 2070
telemt_handshake_timeouts_total 27826
telemt_upstream_connect_attempt_total 7927
telemt_upstream_connect_success_total 7925
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 6192
telemt_me_reconnect_success_total 6130
telemt_me_reader_eof_total 6418
telemt_me_idle_close_by_peer_total 6418
telemt_me_route_drop_no_conn_total 56270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170133
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6106
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6089
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 170449
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1789938720 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 52426480157 (48.83 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28155.2 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144172
telemt_connections_bad_total 1690
telemt_handshake_timeouts_total 9943
telemt_upstream_connect_attempt_total 8232
telemt_upstream_connect_success_total 8197
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 6785
telemt_me_reconnect_success_total 6762
telemt_me_reader_eof_total 7182
telemt_me_idle_close_by_peer_total 7182
telemt_me_route_drop_no_conn_total 48616
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 184
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6803
telemt_me_writer_restored_same_endpoint_total 6741
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 130354
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 1234932652 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 37925218224 (35.32 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28155.1 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166052
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1049
telemt_upstream_connect_attempt_total 10178
telemt_upstream_connect_success_total 10066
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 10178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 10126
telemt_me_reconnect_success_total 8619
telemt_me_reader_eof_total 8976
telemt_me_idle_close_by_peer_total 8976
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 47778
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158625
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 586
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 8739
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8600
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 158650
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 1413285992 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 35825833332 (33.37 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 67
```