# Server Metrics 2026-03-15 05:54:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 27617.7 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385546
telemt_connections_bad_total 6197
telemt_handshake_timeouts_total 1944
telemt_upstream_connect_attempt_total 5840
telemt_upstream_connect_success_total 5818
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4460
telemt_me_reconnect_success_total 4438
telemt_me_reader_eof_total 4693
telemt_me_idle_close_by_peer_total 4693
telemt_me_route_drop_no_conn_total 123176
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342938
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 840
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 579
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4489
telemt_me_writer_restored_same_endpoint_total 4427
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 342953
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 3893348136 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 124540758884 (115.99 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 27618.4 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147483
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 5145
telemt_upstream_connect_attempt_total 8038
telemt_upstream_connect_success_total 8000
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6334
telemt_me_reconnect_success_total 6303
telemt_me_reader_eof_total 6666
telemt_me_idle_close_by_peer_total 6666
telemt_me_route_drop_no_conn_total 34962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120206
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6322
telemt_me_writer_restored_same_endpoint_total 6295
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 120502
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 2088474787 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 39987244800 (37.24 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 27618.9 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276656
telemt_connections_bad_total 6216
telemt_handshake_timeouts_total 28798
telemt_upstream_connect_attempt_total 6429
telemt_upstream_connect_success_total 6402
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5039
telemt_me_reconnect_success_total 5014
telemt_me_reader_eof_total 5308
telemt_me_idle_close_by_peer_total 5308
telemt_me_route_drop_no_conn_total 68079
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229869
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 410
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5068
telemt_me_writer_restored_same_endpoint_total 4995
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 229672
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 3841266360 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 95324463868 (88.78 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 27618.5 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196982
telemt_connections_bad_total 37600
telemt_handshake_timeouts_total 13632
telemt_upstream_connect_attempt_total 9487
telemt_upstream_connect_success_total 9287
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 9487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12709
telemt_me_reconnect_success_total 7901
telemt_me_reader_eof_total 8315
telemt_me_idle_close_by_peer_total 8315
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 45075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141838
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8113
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 7875
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 141841
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 1209629844 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 49372913024 (45.98 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 27619.2 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131847
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 1420
telemt_upstream_connect_attempt_total 6306
telemt_upstream_connect_success_total 6279
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4918
telemt_me_reconnect_success_total 4897
telemt_me_reader_eof_total 5227
telemt_me_idle_close_by_peer_total 5227
telemt_me_route_drop_no_conn_total 36845
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125553
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4945
telemt_me_writer_restored_same_endpoint_total 4889
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 125558
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 1184527620 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 43450396680 (40.47 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 60
```