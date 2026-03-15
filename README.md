# Server Metrics 2026-03-15 01:35:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 12036.1 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150132
telemt_connections_bad_total 1707
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 2559
telemt_upstream_connect_success_total 2550
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1928
telemt_me_reconnect_success_total 1917
telemt_me_reader_eof_total 2016
telemt_me_idle_close_by_peer_total 2016
telemt_me_route_drop_no_conn_total 47028
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131469
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1941
telemt_me_writer_restored_same_endpoint_total 1906
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 131455
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 1477173160 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 44601556164 (41.54 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 12036.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62144
telemt_connections_bad_total 11167
telemt_handshake_timeouts_total 2413
telemt_upstream_connect_attempt_total 3629
telemt_upstream_connect_success_total 3611
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2683
telemt_me_reconnect_success_total 2667
telemt_me_reader_eof_total 2783
telemt_me_idle_close_by_peer_total 2783
telemt_me_route_drop_no_conn_total 12225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46841
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2641
telemt_me_writer_restored_same_endpoint_total 2659
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 47137
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 1487699979 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 12834436532 (11.95 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 12036.7 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100335
telemt_connections_bad_total 2187
telemt_handshake_timeouts_total 8415
telemt_upstream_connect_attempt_total 2786
telemt_upstream_connect_success_total 2772
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2146
telemt_me_reconnect_success_total 2138
telemt_me_reader_eof_total 2247
telemt_me_idle_close_by_peer_total 2247
telemt_me_route_drop_no_conn_total 22409
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2159
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 87877
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 886826628 (845.74 MB)
telemt_user_octets_to_client{user="hello"} 30835269404 (28.72 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 12036.6 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90830
telemt_connections_bad_total 25244
telemt_handshake_timeouts_total 2325
telemt_upstream_connect_attempt_total 4539
telemt_upstream_connect_success_total 4437
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 4539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6162
telemt_me_reconnect_success_total 3800
telemt_me_reader_eof_total 3953
telemt_me_idle_close_by_peer_total 3953
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 16589
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61760
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 101
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3905
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 3782
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 61762
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 355566584 (339.09 MB)
telemt_user_octets_to_client{user="hello"} 11932174952 (11.11 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 12037.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53122
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 695
telemt_upstream_connect_attempt_total 2669
telemt_upstream_connect_success_total 2657
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2032
telemt_me_reconnect_success_total 2023
telemt_me_reader_eof_total 2136
telemt_me_idle_close_by_peer_total 2136
telemt_me_route_drop_no_conn_total 13240
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50921
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2041
telemt_me_writer_restored_same_endpoint_total 2015
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 50921
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 483080696 (460.70 MB)
telemt_user_octets_to_client{user="hello"} 18638693472 (17.36 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```