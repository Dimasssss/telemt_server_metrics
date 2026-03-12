# Server Metrics 2026-03-12 03:26:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20500.5 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175881
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 3342
telemt_upstream_connect_attempt_total 4706
telemt_upstream_connect_success_total 4706
telemt_upstream_connect_attempts_per_request{bucket="1"} 4706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3686
telemt_me_reconnect_success_total 3671
telemt_me_reader_eof_total 3876
telemt_me_idle_close_by_peer_total 3876
telemt_me_route_drop_no_conn_total 63614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166135
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 338
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3711
telemt_me_writer_restored_same_endpoint_total 3655
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 165936
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 1430914116 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 51302251844 (47.78 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20501.1 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58411
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 1002
telemt_upstream_connect_attempt_total 5834
telemt_upstream_connect_success_total 5831
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 4631
telemt_me_reconnect_success_total 4601
telemt_me_reader_eof_total 4880
telemt_me_idle_close_by_peer_total 4880
telemt_me_route_drop_no_conn_total 16459
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54562
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 111
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4636
telemt_me_writer_restored_same_endpoint_total 4592
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 54741
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 968999079 (924.11 MB)
telemt_user_octets_to_client{user="hello"} 19039389826 (17.73 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20501.1 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319708
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 18069
telemt_upstream_connect_attempt_total 6188
telemt_upstream_connect_success_total 6186
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 4844
telemt_me_reconnect_success_total 4789
telemt_me_reader_eof_total 4980
telemt_me_idle_close_by_peer_total 4980
telemt_me_route_drop_no_conn_total 31772
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101562
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4751
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4748
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 101884
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 865821052 (825.71 MB)
telemt_user_octets_to_client{user="hello"} 31348712937 (29.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20501.2 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91945
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 4587
telemt_upstream_connect_attempt_total 6147
telemt_upstream_connect_success_total 6119
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 5099
telemt_me_reconnect_success_total 5081
telemt_me_reader_eof_total 5381
telemt_me_idle_close_by_peer_total 5381
telemt_me_route_drop_no_conn_total 31075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5114
telemt_me_writer_restored_same_endpoint_total 5060
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 85913
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 580508752 (553.62 MB)
telemt_user_octets_to_client{user="hello"} 21962132556 (20.45 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20501.0 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110502
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 7492
telemt_upstream_connect_success_total 7416
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 7492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 7865
telemt_me_reconnect_success_total 6367
telemt_me_reader_eof_total 6624
telemt_me_idle_close_by_peer_total 6624
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 28753
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 399
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6460
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6351
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 105396
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 640461188 (610.79 MB)
telemt_user_octets_to_client{user="hello"} 22895230524 (21.32 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 62
```