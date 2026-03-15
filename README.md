# Server Metrics 2026-03-15 04:07:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 21202.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263103
telemt_connections_bad_total 3594
telemt_handshake_timeouts_total 1307
telemt_upstream_connect_attempt_total 4536
telemt_upstream_connect_success_total 4518
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3464
telemt_me_reconnect_success_total 3446
telemt_me_reader_eof_total 3640
telemt_me_idle_close_by_peer_total 3640
telemt_me_route_drop_no_conn_total 82366
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232987
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3485
telemt_me_writer_restored_same_endpoint_total 3435
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 232960
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 2486571276 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 82558037944 (76.89 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 21203.3 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106001
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4249
telemt_upstream_connect_attempt_total 6346
telemt_upstream_connect_success_total 6319
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4959
telemt_me_reconnect_success_total 4936
telemt_me_reader_eof_total 5210
telemt_me_idle_close_by_peer_total 5210
telemt_me_route_drop_no_conn_total 21261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81044
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 131
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4933
telemt_me_writer_restored_same_endpoint_total 4928
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 81340
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1716646343 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 24075093208 (22.42 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 21203.4 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184100
telemt_connections_bad_total 3606
telemt_handshake_timeouts_total 19241
telemt_upstream_connect_attempt_total 4955
telemt_upstream_connect_success_total 4934
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3874
telemt_me_reconnect_success_total 3855
telemt_me_reader_eof_total 4071
telemt_me_idle_close_by_peer_total 4071
telemt_me_route_drop_no_conn_total 39842
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157609
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3894
telemt_me_writer_restored_same_endpoint_total 3836
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 157489
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 1315504336 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 48398536844 (45.07 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 21203.3 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144552
telemt_connections_bad_total 32311
telemt_handshake_timeouts_total 6796
telemt_upstream_connect_attempt_total 7481
telemt_upstream_connect_success_total 7322
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 7481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 6245
telemt_me_reader_eof_total 6555
telemt_me_idle_close_by_peer_total 6555
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 29419
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103382
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6412
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 6225
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 103387
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 831464060 (792.95 MB)
telemt_user_octets_to_client{user="hello"} 31557828300 (29.39 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 21204.2 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88549
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 4925
telemt_upstream_connect_success_total 4902
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3843
telemt_me_reconnect_success_total 3828
telemt_me_reader_eof_total 4081
telemt_me_idle_close_by_peer_total 4081
telemt_me_route_drop_no_conn_total 23608
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84650
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3864
telemt_me_writer_restored_same_endpoint_total 3820
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 84648
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 714562040 (681.46 MB)
telemt_user_octets_to_client{user="hello"} 27001390108 (25.15 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 40
```