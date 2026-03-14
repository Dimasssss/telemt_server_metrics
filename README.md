# Server Metrics 2026-03-14 23:53:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 5932.6 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82430
telemt_connections_bad_total 994
telemt_handshake_timeouts_total 382
telemt_upstream_connect_attempt_total 1272
telemt_upstream_connect_success_total 1267
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 946
telemt_me_reconnect_success_total 941
telemt_me_reader_eof_total 974
telemt_me_idle_close_by_peer_total 974
telemt_me_route_drop_no_conn_total 26183
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75168
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_restored_same_endpoint_total 930
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 75161
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 873733520 (833.26 MB)
telemt_user_octets_to_client{user="hello"} 29184697016 (27.18 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 5933.1 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32276
telemt_connections_bad_total 4686
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 2008
telemt_upstream_connect_success_total 1995
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1369
telemt_me_reconnect_success_total 1358
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1381
telemt_me_route_drop_no_conn_total 6325
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24420
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
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_restored_same_endpoint_total 1350
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 24717
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 1284070359 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 5916307812 (5.51 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 5933.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53600
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 3368
telemt_upstream_connect_attempt_total 1316
telemt_upstream_connect_success_total 1308
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 983
telemt_me_reconnect_success_total 980
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 13175
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48567
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 989
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 48487
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 665423692 (634.60 MB)
telemt_user_octets_to_client{user="hello"} 14894888000 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 5933.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39503
telemt_connections_bad_total 5180
telemt_handshake_timeouts_total 863
telemt_upstream_connect_attempt_total 2068
telemt_upstream_connect_success_total 2005
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 2068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2975
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1720
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 8011
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32806
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1722
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 32808
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 227316548 (216.79 MB)
telemt_user_octets_to_client{user="hello"} 9011089508 (8.39 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 5933.7 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29573
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 1218
telemt_upstream_connect_success_total 1214
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 892
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 919
telemt_me_idle_close_by_peer_total 919
telemt_me_route_drop_no_conn_total 7188
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28342
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 28342
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 237422752 (226.42 MB)
telemt_user_octets_to_client{user="hello"} 14196394552 (13.22 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 36
```