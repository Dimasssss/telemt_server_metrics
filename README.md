# Server Metrics 2026-03-12 06:04:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 371.1 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12020
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 136
telemt_upstream_connect_success_total 135
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 67
telemt_me_reconnect_success_total 67
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 3842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 58
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 11582
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 922443348 (879.71 MB)
telemt_user_octets_to_client{user="hello"} 2998420640 (2.79 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29991.7 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114230
telemt_connections_bad_total 1094
telemt_handshake_timeouts_total 3145
telemt_upstream_connect_attempt_total 8032
telemt_upstream_connect_success_total 8027
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 6353
telemt_me_reconnect_success_total 6316
telemt_me_reader_eof_total 6719
telemt_me_idle_close_by_peer_total 6719
telemt_me_route_drop_no_conn_total 34417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103177
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 316
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6369
telemt_me_writer_restored_same_endpoint_total 6307
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 103365
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 1601800639 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 43854131846 (40.84 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29991.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434697
telemt_connections_bad_total 2259
telemt_handshake_timeouts_total 31099
telemt_upstream_connect_attempt_total 8318
telemt_upstream_connect_success_total 8316
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6497
telemt_me_reconnect_success_total 6434
telemt_me_reader_eof_total 6740
telemt_me_idle_close_by_peer_total 6740
telemt_me_route_drop_no_conn_total 64380
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194913
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 778
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 6412
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6393
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 195221
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 2012462668 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 58923156493 (54.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29991.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161657
telemt_connections_bad_total 1694
telemt_handshake_timeouts_total 11571
telemt_upstream_connect_attempt_total 8701
telemt_upstream_connect_success_total 8662
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 7164
telemt_me_reconnect_success_total 7138
telemt_me_reader_eof_total 7580
telemt_me_idle_close_by_peer_total 7580
telemt_me_route_drop_no_conn_total 55608
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146063
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7181
telemt_me_writer_restored_same_endpoint_total 7117
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 145920
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 1736524112 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 44551178752 (41.49 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29991.7 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187161
telemt_connections_bad_total 305
telemt_handshake_timeouts_total 1166
telemt_upstream_connect_attempt_total 10560
telemt_upstream_connect_success_total 10442
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 10560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 10416
telemt_me_reconnect_success_total 8907
telemt_me_reader_eof_total 9281
telemt_me_idle_close_by_peer_total 9281
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 56772
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179182
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 646
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9033
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8888
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 179140
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 1585978940 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 41198697048 (38.37 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 96
```