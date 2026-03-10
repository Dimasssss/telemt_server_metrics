# Server Metrics 2026-03-10 14:39:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 763.9 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28653
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 164
telemt_upstream_connect_success_total 163
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 94
telemt_me_reconnect_success_total 91
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 11650
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26859
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 70
telemt_me_writer_restored_same_endpoint_total 85
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_user_connections_total{user="hello"} 26858
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 223203780 (212.86 MB)
telemt_user_octets_to_client{user="hello"} 8262670788 (7.70 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 820.6 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12545
telemt_connections_bad_total 426
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 123
telemt_upstream_connect_success_total 122
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 53
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 2388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9823
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 9823
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 106009592 (101.10 MB)
telemt_user_octets_to_client{user="hello"} 3102121864 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 820.5 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20824
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 1140
telemt_upstream_connect_success_total 1121
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 33
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 5789
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18592
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 19594
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 236926329 (225.95 MB)
telemt_user_octets_to_client{user="hello"} 7171427685 (6.68 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 820.9 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13425
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 804
telemt_upstream_connect_attempt_total 113
telemt_upstream_connect_success_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 3794
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10857
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 10832
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 138341740 (131.93 MB)
telemt_user_octets_to_client{user="hello"} 2405453552 (2.24 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 820.7 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16116
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 168
telemt_upstream_connect_success_total 167
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 99
telemt_me_reconnect_success_total 98
telemt_me_reader_eof_total 69
telemt_me_idle_close_by_peer_total 69
telemt_me_route_drop_no_conn_total 3799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14796
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 92
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 14774
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 112730136 (107.51 MB)
telemt_user_octets_to_client{user="hello"} 3630464560 (3.38 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 100
```