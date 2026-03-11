# Server Metrics 2026-03-11 22:41:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3364.0 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34322
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 734
telemt_upstream_connect_success_total 734
telemt_upstream_connect_attempts_per_request{bucket="1"} 734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 536
telemt_me_reconnect_success_total 534
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 11889
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31779
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 543
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 31768
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 202443408 (193.07 MB)
telemt_user_octets_to_client{user="hello"} 8909219056 (8.30 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3365.0 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12717
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 998
telemt_upstream_connect_success_total 998
telemt_upstream_connect_attempts_per_request{bucket="1"} 998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 510
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 796
telemt_me_reconnect_success_total 790
telemt_me_reader_eof_total 806
telemt_me_idle_close_by_peer_total 806
telemt_me_route_drop_no_conn_total 3454
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 792
telemt_me_writer_restored_same_endpoint_total 781
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 12106
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 472341612 (450.46 MB)
telemt_user_octets_to_client{user="hello"} 6217894540 (5.79 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3364.7 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25663
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 2832
telemt_upstream_connect_attempt_total 1545
telemt_upstream_connect_success_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 1545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 983
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 918
telemt_me_route_drop_no_conn_total 5760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20636
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 900
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 20990
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 180059824 (171.72 MB)
telemt_user_octets_to_client{user="hello"} 10021155289 (9.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3365.2 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18449
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 304
telemt_upstream_connect_attempt_total 1079
telemt_upstream_connect_success_total 1072
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 386
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 871
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 4859
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 866
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 17804
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 112084548 (106.89 MB)
telemt_user_octets_to_client{user="hello"} 7807782212 (7.27 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3365.0 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21926
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 264
telemt_upstream_connect_attempt_total 1180
telemt_upstream_connect_success_total 1167
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 967
telemt_me_reconnect_success_total 958
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 5143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20754
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 952
telemt_me_writer_restored_same_endpoint_total 954
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 20750
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 128559248 (122.60 MB)
telemt_user_octets_to_client{user="hello"} 6106801372 (5.69 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 43
```