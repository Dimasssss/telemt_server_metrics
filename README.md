# Server Metrics 2026-03-10 15:46:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4748.0 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173523
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 834
telemt_upstream_connect_attempt_total 1029
telemt_upstream_connect_success_total 1024
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 4699
telemt_me_reconnect_success_total 724
telemt_me_reader_eof_total 806
telemt_me_idle_close_by_peer_total 806
telemt_me_route_drop_no_conn_total 78261
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165512
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 521
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_me_writer_removed_unexpected_total 836
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 718
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 165462
telemt_user_connections_current{user="hello"} 1399
telemt_user_octets_from_client{user="hello"} 2165689836 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 45667180976 (42.53 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4804.6 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68806
telemt_connections_bad_total 1473
telemt_handshake_timeouts_total 6464
telemt_upstream_connect_attempt_total 1042
telemt_upstream_connect_success_total 1035
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 747
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 750
telemt_me_idle_close_by_peer_total 750
telemt_me_route_drop_no_conn_total 17959
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56801
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 56788
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 746284976 (711.71 MB)
telemt_user_octets_to_client{user="hello"} 16551685236 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4804.5 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121636
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 6315
telemt_upstream_connect_attempt_total 2235
telemt_upstream_connect_success_total 2195
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 2235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 868
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 39243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 883
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 103816
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 1037758945 (989.68 MB)
telemt_user_octets_to_client{user="hello"} 29973267605 (27.91 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4804.9 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80443
telemt_connections_bad_total 4738
telemt_handshake_timeouts_total 8267
telemt_upstream_connect_attempt_total 1032
telemt_upstream_connect_success_total 1032
telemt_upstream_connect_attempts_per_request{bucket="1"} 1032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 437
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 744
telemt_me_idle_close_by_peer_total 744
telemt_me_route_drop_no_conn_total 26022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63633
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 738
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 63565
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 827373828 (789.05 MB)
telemt_user_octets_to_client{user="hello"} 15418859876 (14.36 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4804.6 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89127
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 721
telemt_upstream_connect_attempt_total 1432
telemt_upstream_connect_success_total 1426
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1135
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1146
telemt_me_idle_close_by_peer_total 1146
telemt_me_route_drop_no_conn_total 33177
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82182
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 469
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_restored_same_endpoint_total 1128
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 82139
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 1488908008 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 22513317884 (20.97 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 86
```