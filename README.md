# Server Metrics 2026-03-14 23:38:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 5016.5 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72952
telemt_connections_bad_total 839
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 1082
telemt_upstream_connect_success_total 1078
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 800
telemt_me_reconnect_success_total 796
telemt_me_reader_eof_total 819
telemt_me_idle_close_by_peer_total 819
telemt_me_route_drop_no_conn_total 23476
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66678
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 66673
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 821578052 (783.52 MB)
telemt_user_octets_to_client{user="hello"} 25582193084 (23.83 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 5017.0 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28714
telemt_connections_bad_total 3937
telemt_handshake_timeouts_total 1864
telemt_upstream_connect_attempt_total 1746
telemt_upstream_connect_success_total 1734
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1151
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1149
telemt_me_idle_close_by_peer_total 1149
telemt_me_route_drop_no_conn_total 5654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21835
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1104
telemt_me_writer_restored_same_endpoint_total 1132
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 22132
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1254357423 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 5418526852 (5.05 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 5017.4 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46946
telemt_connections_bad_total 995
telemt_handshake_timeouts_total 2791
telemt_upstream_connect_attempt_total 1119
telemt_upstream_connect_success_total 1111
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 829
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 851
telemt_me_idle_close_by_peer_total 851
telemt_me_route_drop_no_conn_total 11676
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 835
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 42501
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 641912348 (612.18 MB)
telemt_user_octets_to_client{user="hello"} 13797004064 (12.85 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 5017.1 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33410
telemt_connections_bad_total 4385
telemt_handshake_timeouts_total 785
telemt_upstream_connect_attempt_total 1691
telemt_upstream_connect_success_total 1633
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 1691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1366
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 6924
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27709
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1353
telemt_me_writer_restored_same_endpoint_total 1330
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 27711
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 209726800 (200.01 MB)
telemt_user_octets_to_client{user="hello"} 7470299904 (6.96 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 5017.8 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25616
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 1016
telemt_upstream_connect_success_total 1012
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 733
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 5921
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24483
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 24483
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 190618748 (181.79 MB)
telemt_user_octets_to_client{user="hello"} 13433272996 (12.51 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 39
```