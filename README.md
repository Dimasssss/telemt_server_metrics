# Server Metrics 2026-03-12 07:46:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 6494.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192035
telemt_connections_bad_total 1201
telemt_handshake_timeouts_total 1618
telemt_upstream_connect_attempt_total 1340
telemt_upstream_connect_success_total 1331
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 584
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 960
telemt_me_reconnect_success_total 955
telemt_me_reader_eof_total 973
telemt_me_idle_close_by_peer_total 973
telemt_me_route_drop_no_conn_total 64013
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185430
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 923
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 692
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 185349
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 2960059672 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 54653173660 (50.90 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36115.1 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179977
telemt_connections_bad_total 2542
telemt_handshake_timeouts_total 6933
telemt_upstream_connect_attempt_total 9317
telemt_upstream_connect_success_total 9311
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 7335
telemt_me_reconnect_success_total 7295
telemt_me_reader_eof_total 7752
telemt_me_idle_close_by_peer_total 7752
telemt_me_route_drop_no_conn_total 52015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155819
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7354
telemt_me_writer_restored_same_endpoint_total 7286
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 156089
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 2358259891 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 62831674782 (58.52 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36115.0 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546402
telemt_connections_bad_total 2538
telemt_handshake_timeouts_total 40777
telemt_upstream_connect_attempt_total 9526
telemt_upstream_connect_success_total 9521
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 7421
telemt_me_reconnect_success_total 7352
telemt_me_reader_eof_total 7716
telemt_me_idle_close_by_peer_total 7716
telemt_me_route_drop_no_conn_total 100814
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294507
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1330
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 920
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 700
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7342
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7311
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 294788
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 3174273136 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 105926348041 (98.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36115.3 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250738
telemt_connections_bad_total 1782
telemt_handshake_timeouts_total 15560
telemt_upstream_connect_attempt_total 10065
telemt_upstream_connect_success_total 10025
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 8232
telemt_me_reconnect_success_total 8203
telemt_me_reader_eof_total 8710
telemt_me_idle_close_by_peer_total 8710
telemt_me_route_drop_no_conn_total 82610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 352
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8254
telemt_me_writer_restored_same_endpoint_total 8182
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 207436
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 2417854888 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 69650176940 (64.87 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36115.3 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273663
telemt_connections_bad_total 348
telemt_handshake_timeouts_total 2221
telemt_upstream_connect_attempt_total 12086
telemt_upstream_connect_success_total 11940
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 12086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 11615
telemt_me_reconnect_success_total 10103
telemt_me_reader_eof_total 10512
telemt_me_idle_close_by_peer_total 10512
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 85261
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257056
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1021
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10244
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10082
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 257006
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 2497729744 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 61847684884 (57.60 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 108
```