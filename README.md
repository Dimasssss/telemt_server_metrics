# Server Metrics 2026-03-11 22:51:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3976.8 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38760
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 928
telemt_upstream_connect_success_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 687
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 702
telemt_me_route_drop_no_conn_total 14005
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36118
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 36107
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 223092880 (212.76 MB)
telemt_user_octets_to_client{user="hello"} 9491715892 (8.84 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3977.7 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14691
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 1170
telemt_upstream_connect_success_total 1170
telemt_upstream_connect_attempts_per_request{bucket="1"} 1170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 924
telemt_me_reconnect_success_total 917
telemt_me_reader_eof_total 944
telemt_me_idle_close_by_peer_total 944
telemt_me_route_drop_no_conn_total 3888
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13992
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 920
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 13990
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 481584412 (459.27 MB)
telemt_user_octets_to_client{user="hello"} 7395170160 (6.89 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3977.4 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29872
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 3248
telemt_upstream_connect_attempt_total 1717
telemt_upstream_connect_success_total 1717
telemt_upstream_connect_attempts_per_request{bucket="1"} 1717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1151
telemt_me_reconnect_success_total 1112
telemt_me_reader_eof_total 1057
telemt_me_idle_close_by_peer_total 1057
telemt_me_route_drop_no_conn_total 6480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23259
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1029
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1071
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 23613
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 195542316 (186.48 MB)
telemt_user_octets_to_client{user="hello"} 12047081849 (11.22 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3977.9 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21488
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 1290
telemt_upstream_connect_success_total 1281
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 495
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1036
telemt_me_reconnect_success_total 1030
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 5870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20786
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
telemt_me_writer_removed_unexpected_total 1033
telemt_me_writer_restored_same_endpoint_total 1009
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 20786
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 124299136 (118.54 MB)
telemt_user_octets_to_client{user="hello"} 9191743412 (8.56 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3977.8 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25588
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 1573
telemt_upstream_connect_success_total 1555
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 1311
telemt_me_reconnect_success_total 1303
telemt_me_reader_eof_total 1273
telemt_me_idle_close_by_peer_total 1273
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 6028
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24155
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 26
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 1297
telemt_me_writer_restored_same_endpoint_total 1299
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 24151
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 176915924 (168.72 MB)
telemt_user_octets_to_client{user="hello"} 6633544736 (6.18 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 34
```