# Server Metrics 2026-03-15 01:55:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 13257.4 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163551
telemt_connections_bad_total 1847
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 2793
telemt_upstream_connect_success_total 2784
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 2119
telemt_me_reconnect_success_total 2107
telemt_me_reader_eof_total 2216
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 50833
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143724
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2134
telemt_me_writer_restored_same_endpoint_total 2096
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 143712
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 1598715616 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 48282767696 (44.97 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 13258.0 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68823
telemt_connections_bad_total 12126
telemt_handshake_timeouts_total 3466
telemt_upstream_connect_attempt_total 3942
telemt_upstream_connect_success_total 3924
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2953
telemt_me_reconnect_success_total 2936
telemt_me_reader_eof_total 3064
telemt_me_idle_close_by_peer_total 3064
telemt_me_route_drop_no_conn_total 13087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51375
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2911
telemt_me_writer_restored_same_endpoint_total 2928
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 51671
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 1520685971 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 13694839048 (12.75 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 13258.2 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110732
telemt_connections_bad_total 2228
telemt_handshake_timeouts_total 10068
telemt_upstream_connect_attempt_total 3073
telemt_upstream_connect_success_total 3057
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2388
telemt_me_reconnect_success_total 2380
telemt_me_reader_eof_total 2504
telemt_me_idle_close_by_peer_total 2504
telemt_me_route_drop_no_conn_total 24422
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96221
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2405
telemt_me_writer_restored_same_endpoint_total 2361
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 96132
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 962109740 (917.54 MB)
telemt_user_octets_to_client{user="hello"} 32603062504 (30.36 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 13258.0 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97121
telemt_connections_bad_total 26186
telemt_handshake_timeouts_total 2606
telemt_upstream_connect_attempt_total 5024
telemt_upstream_connect_success_total 4913
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 5024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7779
telemt_me_reconnect_success_total 4232
telemt_me_reader_eof_total 4428
telemt_me_idle_close_by_peer_total 4428
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 17805
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66760
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4380
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4214
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 66762
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 394593580 (376.31 MB)
telemt_user_octets_to_client{user="hello"} 12315389220 (11.47 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 13258.6 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56864
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 707
telemt_upstream_connect_attempt_total 2962
telemt_upstream_connect_success_total 2948
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2280
telemt_me_reconnect_success_total 2271
telemt_me_reader_eof_total 2399
telemt_me_idle_close_by_peer_total 2399
telemt_me_route_drop_no_conn_total 14057
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2290
telemt_me_writer_restored_same_endpoint_total 2263
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 54510
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 499863480 (476.71 MB)
telemt_user_octets_to_client{user="hello"} 19285216884 (17.96 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 29
```