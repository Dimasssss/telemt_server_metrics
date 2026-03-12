# Server Metrics 2026-03-12 02:50:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18357.4 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153060
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 2933
telemt_upstream_connect_attempt_total 4258
telemt_upstream_connect_success_total 4258
telemt_upstream_connect_attempts_per_request{bucket="1"} 4258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3326
telemt_me_reconnect_success_total 3313
telemt_me_reader_eof_total 3501
telemt_me_idle_close_by_peer_total 3501
telemt_me_route_drop_no_conn_total 55181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144230
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3350
telemt_me_writer_restored_same_endpoint_total 3297
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 144066
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 1029293852 (981.61 MB)
telemt_user_octets_to_client{user="hello"} 45880300192 (42.73 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18358.1 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51935
telemt_connections_bad_total 124
telemt_handshake_timeouts_total 881
telemt_upstream_connect_attempt_total 5292
telemt_upstream_connect_success_total 5289
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 4175
telemt_me_reconnect_success_total 4148
telemt_me_reader_eof_total 4397
telemt_me_idle_close_by_peer_total 4397
telemt_me_route_drop_no_conn_total 13978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48450
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4177
telemt_me_writer_restored_same_endpoint_total 4139
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 48629
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 765150599 (729.70 MB)
telemt_user_octets_to_client{user="hello"} 17862908158 (16.64 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18358.0 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262632
telemt_connections_bad_total 1327
telemt_handshake_timeouts_total 16092
telemt_upstream_connect_attempt_total 5619
telemt_upstream_connect_success_total 5617
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4361
telemt_me_reconnect_success_total 4306
telemt_me_reader_eof_total 4466
telemt_me_idle_close_by_peer_total 4466
telemt_me_route_drop_no_conn_total 27447
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88596
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 191
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4263
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4265
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 88934
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 743617816 (709.17 MB)
telemt_user_octets_to_client{user="hello"} 28477407441 (26.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18358.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80751
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 2739
telemt_upstream_connect_attempt_total 5494
telemt_upstream_connect_success_total 5466
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 4532
telemt_me_reconnect_success_total 4516
telemt_me_reader_eof_total 4785
telemt_me_idle_close_by_peer_total 4785
telemt_me_route_drop_no_conn_total 27672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76713
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4545
telemt_me_writer_restored_same_endpoint_total 4495
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 76699
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 490913532 (468.17 MB)
telemt_user_octets_to_client{user="hello"} 17247490520 (16.06 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18358.0 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98697
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 646
telemt_upstream_connect_attempt_total 6842
telemt_upstream_connect_success_total 6770
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 6842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 7305
telemt_me_reconnect_success_total 5806
telemt_me_reader_eof_total 6029
telemt_me_idle_close_by_peer_total 6029
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 25176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94013
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 330
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5897
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 5790
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 93990
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 555898772 (530.15 MB)
telemt_user_octets_to_client{user="hello"} 20669977860 (19.25 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```