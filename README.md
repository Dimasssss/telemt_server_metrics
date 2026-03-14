# Server Metrics 2026-03-14 23:58:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 6237.7 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85284
telemt_connections_bad_total 1038
telemt_handshake_timeouts_total 396
telemt_upstream_connect_attempt_total 1305
telemt_upstream_connect_success_total 1300
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 979
telemt_me_reconnect_success_total 974
telemt_me_reader_eof_total 1008
telemt_me_idle_close_by_peer_total 1008
telemt_me_route_drop_no_conn_total 27474
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77718
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 77711
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 909760592 (867.62 MB)
telemt_user_octets_to_client{user="hello"} 29714804736 (27.67 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 6238.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33538
telemt_connections_bad_total 4935
telemt_handshake_timeouts_total 1919
telemt_upstream_connect_attempt_total 2058
telemt_upstream_connect_success_total 2045
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1419
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 6588
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25385
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 75
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1373
telemt_me_writer_restored_same_endpoint_total 1399
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 25682
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1287595515 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 6189385044 (5.76 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 6238.5 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55468
telemt_connections_bad_total 1015
telemt_handshake_timeouts_total 3519
telemt_upstream_connect_attempt_total 1357
telemt_upstream_connect_success_total 1349
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1024
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 1054
telemt_me_idle_close_by_peer_total 1054
telemt_me_route_drop_no_conn_total 13735
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50268
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1030
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 50188
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 670289796 (639.24 MB)
telemt_user_octets_to_client{user="hello"} 15094116872 (14.06 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 6238.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41432
telemt_connections_bad_total 5433
telemt_handshake_timeouts_total 889
telemt_upstream_connect_attempt_total 2154
telemt_upstream_connect_success_total 2091
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 2154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3061
telemt_me_reconnect_success_total 1758
telemt_me_reader_eof_total 1808
telemt_me_idle_close_by_peer_total 1808
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 8302
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34403
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1810
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1745
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 34405
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 231093972 (220.39 MB)
telemt_user_octets_to_client{user="hello"} 9208273972 (8.58 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 6239.0 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30842
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 1257
telemt_upstream_connect_success_total 1253
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 931
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 7521
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29574
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 936
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 29574
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 243317088 (232.05 MB)
telemt_user_octets_to_client{user="hello"} 14387192656 (13.40 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 33
```