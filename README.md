# Server Metrics 2026-03-12 00:02:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8261.1 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73573
telemt_connections_bad_total 1321
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 1994
telemt_upstream_connect_success_total 1994
telemt_upstream_connect_attempts_per_request{bucket="1"} 1994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1536
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1599
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 27366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69053
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 175
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1551
telemt_me_writer_restored_same_endpoint_total 1515
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 69010
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 471623324 (449.78 MB)
telemt_user_octets_to_client{user="hello"} 21346404600 (19.88 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8261.8 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26272
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 2510
telemt_upstream_connect_success_total 2507
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1867
telemt_me_reconnect_success_total 1847
telemt_me_reader_eof_total 1940
telemt_me_idle_close_by_peer_total 1940
telemt_me_route_drop_no_conn_total 6893
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1858
telemt_me_writer_restored_same_endpoint_total 1838
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 24951
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 562805051 (536.73 MB)
telemt_user_octets_to_client{user="hello"} 10130861422 (9.44 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8261.5 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74790
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 5509
telemt_upstream_connect_attempt_total 2898
telemt_upstream_connect_success_total 2896
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 2114
telemt_me_reconnect_success_total 2069
telemt_me_reader_eof_total 2075
telemt_me_idle_close_by_peer_total 2075
telemt_me_route_drop_no_conn_total 11757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40391
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2000
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 40736
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 482221944 (459.88 MB)
telemt_user_octets_to_client{user="hello"} 19849950729 (18.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8261.8 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38689
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 2456
telemt_upstream_connect_success_total 2442
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1981
telemt_me_reconnect_success_total 1972
telemt_me_reader_eof_total 2047
telemt_me_idle_close_by_peer_total 2047
telemt_me_route_drop_no_conn_total 12577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1985
telemt_me_writer_restored_same_endpoint_total 1951
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 37483
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 186643320 (178.00 MB)
telemt_user_octets_to_client{user="hello"} 11314002716 (10.54 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8261.6 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50537
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 499
telemt_upstream_connect_attempt_total 3661
telemt_upstream_connect_success_total 3626
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 4636
telemt_me_reconnect_success_total 3148
telemt_me_reader_eof_total 3221
telemt_me_idle_close_by_peer_total 3221
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 11727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 81
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3211
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3142
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 47040
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 247627112 (236.16 MB)
telemt_user_octets_to_client{user="hello"} 12581119920 (11.72 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```