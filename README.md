# Server Metrics 2026-03-14 23:43:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 5322.1 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76224
telemt_connections_bad_total 898
telemt_handshake_timeouts_total 335
telemt_upstream_connect_attempt_total 1114
telemt_upstream_connect_success_total 1110
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 832
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 851
telemt_me_idle_close_by_peer_total 851
telemt_me_route_drop_no_conn_total 24330
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69623
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 229
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 840
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 69617
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 842406684 (803.38 MB)
telemt_user_octets_to_client{user="hello"} 27165143548 (25.30 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 5322.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30067
telemt_connections_bad_total 4194
telemt_handshake_timeouts_total 1884
telemt_upstream_connect_attempt_total 1801
telemt_upstream_connect_success_total 1789
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 1195
telemt_me_reader_eof_total 1204
telemt_me_idle_close_by_peer_total 1204
telemt_me_route_drop_no_conn_total 5978
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22780
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_restored_same_endpoint_total 1187
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 23077
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1262185959 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 5608216196 (5.22 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 5322.8 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49329
telemt_connections_bad_total 995
telemt_handshake_timeouts_total 2934
telemt_upstream_connect_attempt_total 1154
telemt_upstream_connect_success_total 1146
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 864
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 886
telemt_me_idle_close_by_peer_total 886
telemt_me_route_drop_no_conn_total 12304
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44799
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 843
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 44719
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 654104352 (623.80 MB)
telemt_user_octets_to_client{user="hello"} 14234484936 (13.26 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 5322.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35614
telemt_connections_bad_total 4660
telemt_handshake_timeouts_total 805
telemt_upstream_connect_attempt_total 1817
telemt_upstream_connect_success_total 1759
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 1817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 1469
telemt_me_reader_eof_total 1477
telemt_me_idle_close_by_peer_total 1477
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 7526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29577
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1479
telemt_me_writer_restored_same_endpoint_total 1456
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 29579
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 213628408 (203.73 MB)
telemt_user_octets_to_client{user="hello"} 7648870060 (7.12 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 5323.3 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27020
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 1055
telemt_upstream_connect_success_total 1051
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 789
telemt_me_route_drop_no_conn_total 6368
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25846
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
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_restored_same_endpoint_total 760
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 25846
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 196737876 (187.62 MB)
telemt_user_octets_to_client{user="hello"} 13713913700 (12.77 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 39
```