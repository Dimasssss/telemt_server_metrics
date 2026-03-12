# Server Metrics 2026-03-12 01:24:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13155.7 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107752
telemt_connections_bad_total 1343
telemt_handshake_timeouts_total 402
telemt_upstream_connect_attempt_total 3083
telemt_upstream_connect_success_total 3083
telemt_upstream_connect_attempts_per_request{bucket="1"} 3083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2410
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2529
telemt_me_route_drop_no_conn_total 40017
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102485
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2431
telemt_me_writer_restored_same_endpoint_total 2385
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 102371
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 724783388 (691.21 MB)
telemt_user_octets_to_client{user="hello"} 28531086372 (26.57 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13156.3 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36933
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 406
telemt_upstream_connect_attempt_total 3870
telemt_upstream_connect_success_total 3867
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 3012
telemt_me_reconnect_success_total 2990
telemt_me_reader_eof_total 3162
telemt_me_idle_close_by_peer_total 3162
telemt_me_route_drop_no_conn_total 10368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34977
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3012
telemt_me_writer_restored_same_endpoint_total 2981
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 35156
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 652281535 (622.06 MB)
telemt_user_octets_to_client{user="hello"} 12537094158 (11.68 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13156.2 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126976
telemt_connections_bad_total 913
telemt_handshake_timeouts_total 10644
telemt_upstream_connect_attempt_total 4243
telemt_upstream_connect_success_total 4241
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 3243
telemt_me_reconnect_success_total 3194
telemt_me_reader_eof_total 3274
telemt_me_idle_close_by_peer_total 3274
telemt_me_route_drop_no_conn_total 20170
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62127
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 109
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3135
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3153
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 62472
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 610112720 (581.85 MB)
telemt_user_octets_to_client{user="hello"} 23920964381 (22.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13156.5 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57805
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 1202
telemt_upstream_connect_attempt_total 4015
telemt_upstream_connect_success_total 3995
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 3319
telemt_me_reconnect_success_total 3308
telemt_me_reader_eof_total 3492
telemt_me_idle_close_by_peer_total 3492
telemt_me_route_drop_no_conn_total 19937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3328
telemt_me_writer_restored_same_endpoint_total 3287
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 55704
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 317206468 (302.51 MB)
telemt_user_octets_to_client{user="hello"} 13244235264 (12.33 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13156.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73923
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 5255
telemt_upstream_connect_success_total 5208
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 6002
telemt_me_reconnect_success_total 4509
telemt_me_reader_eof_total 4660
telemt_me_idle_close_by_peer_total 4660
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 18455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69854
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 183
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4587
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4501
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 69835
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 322450268 (307.51 MB)
telemt_user_octets_to_client{user="hello"} 15418542412 (14.36 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 30
```