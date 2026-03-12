# Server Metrics 2026-03-12 00:07:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8566.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76121
telemt_connections_bad_total 1321
telemt_handshake_timeouts_total 225
telemt_upstream_connect_attempt_total 2076
telemt_upstream_connect_success_total 2076
telemt_upstream_connect_attempts_per_request{bucket="1"} 2076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 1618
telemt_me_reconnect_success_total 1613
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1688
telemt_me_route_drop_no_conn_total 28087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71538
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1633
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 71494
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 484975132 (462.51 MB)
telemt_user_octets_to_client{user="hello"} 22196916512 (20.67 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8567.8 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27153
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 2607
telemt_upstream_connect_success_total 2604
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 1964
telemt_me_reconnect_success_total 1944
telemt_me_reader_eof_total 2040
telemt_me_idle_close_by_peer_total 2040
telemt_me_route_drop_no_conn_total 7088
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25617
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
telemt_me_writer_removed_unexpected_total 1955
telemt_me_writer_restored_same_endpoint_total 1935
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 25796
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 564736395 (538.57 MB)
telemt_user_octets_to_client{user="hello"} 10278628278 (9.57 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 8567.6 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77983
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 5803
telemt_upstream_connect_attempt_total 2993
telemt_upstream_connect_success_total 2991
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 2209
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2173
telemt_me_idle_close_by_peer_total 2173
telemt_me_route_drop_no_conn_total 12221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41925
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2096
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2123
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 42270
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 485663964 (463.17 MB)
telemt_user_octets_to_client{user="hello"} 20036593325 (18.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 8567.9 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40142
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 603
telemt_upstream_connect_attempt_total 2555
telemt_upstream_connect_success_total 2541
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 2080
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 2154
telemt_me_idle_close_by_peer_total 2154
telemt_me_route_drop_no_conn_total 13441
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38912
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2084
telemt_me_writer_restored_same_endpoint_total 2050
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 38908
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 190098156 (181.29 MB)
telemt_user_octets_to_client{user="hello"} 11445586632 (10.66 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8567.7 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52380
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 3850
telemt_upstream_connect_success_total 3815
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 4825
telemt_me_reconnect_success_total 3336
telemt_me_reader_eof_total 3410
telemt_me_idle_close_by_peer_total 3410
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 12523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48849
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
telemt_me_writer_removed_unexpected_total 3400
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3330
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 48845
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 250765796 (239.15 MB)
telemt_user_octets_to_client{user="hello"} 12726931740 (11.85 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 43
```