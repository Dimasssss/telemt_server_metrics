# Server Metrics 2026-03-11 22:46:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3670.7 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36471
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 843
telemt_upstream_connect_success_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 615
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 12793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33884
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
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 33873
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 209025764 (199.34 MB)
telemt_user_octets_to_client{user="hello"} 9145570784 (8.52 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3671.3 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13749
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 1068
telemt_upstream_connect_success_total 1068
telemt_upstream_connect_attempts_per_request{bucket="1"} 1068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 834
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 3645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13121
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
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 13119
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 476514156 (454.44 MB)
telemt_user_octets_to_client{user="hello"} 6458321692 (6.01 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3671.1 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28290
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 3020
telemt_upstream_connect_attempt_total 1615
telemt_upstream_connect_success_total 1614
telemt_upstream_connect_attempts_per_request{bucket="1"} 1614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1062
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 6131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21916
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
telemt_me_writer_removed_unexpected_total 940
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 982
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 22270
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 191202996 (182.35 MB)
telemt_user_octets_to_client{user="hello"} 11677577021 (10.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3671.5 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20049
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 307
telemt_upstream_connect_attempt_total 1144
telemt_upstream_connect_success_total 1135
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 5320
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19368
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
telemt_me_writer_removed_unexpected_total 909
telemt_me_writer_restored_same_endpoint_total 887
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 19368
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 118083168 (112.61 MB)
telemt_user_octets_to_client{user="hello"} 8449950308 (7.87 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3671.3 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23758
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 1327
telemt_upstream_connect_success_total 1314
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 1100
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 5554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22445
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
telemt_me_writer_removed_unexpected_total 1085
telemt_me_writer_restored_same_endpoint_total 1088
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 22441
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 132375888 (126.24 MB)
telemt_user_octets_to_client{user="hello"} 6424819236 (5.98 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 27
```