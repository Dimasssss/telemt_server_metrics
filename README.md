# Server Metrics 2026-03-12 01:08:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12237.9 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101099
telemt_connections_bad_total 1340
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 2875
telemt_upstream_connect_success_total 2875
telemt_upstream_connect_attempts_per_request{bucket="1"} 2875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2245
telemt_me_reconnect_success_total 2238
telemt_me_reader_eof_total 2352
telemt_me_idle_close_by_peer_total 2352
telemt_me_route_drop_no_conn_total 37572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96012
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2266
telemt_me_writer_restored_same_endpoint_total 2222
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 95907
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 671773176 (640.65 MB)
telemt_user_octets_to_client{user="hello"} 27871189488 (25.96 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12238.7 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34915
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 396
telemt_upstream_connect_attempt_total 3641
telemt_upstream_connect_success_total 3638
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 3641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2826
telemt_me_reconnect_success_total 2804
telemt_me_reader_eof_total 2962
telemt_me_idle_close_by_peer_total 2962
telemt_me_route_drop_no_conn_total 9778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2823
telemt_me_writer_restored_same_endpoint_total 2795
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 33215
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 611089975 (582.78 MB)
telemt_user_octets_to_client{user="hello"} 11859147334 (11.04 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12238.4 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113001
telemt_connections_bad_total 857
telemt_handshake_timeouts_total 9733
telemt_upstream_connect_attempt_total 4004
telemt_upstream_connect_success_total 4002
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3047
telemt_me_reconnect_success_total 2998
telemt_me_reader_eof_total 3064
telemt_me_idle_close_by_peer_total 3064
telemt_me_route_drop_no_conn_total 18552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58623
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2937
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 2957
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 58967
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 590104088 (562.77 MB)
telemt_user_octets_to_client{user="hello"} 22811533729 (21.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12239.0 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54896
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 1024
telemt_upstream_connect_attempt_total 3722
telemt_upstream_connect_success_total 3704
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 3071
telemt_me_reconnect_success_total 3060
telemt_me_reader_eof_total 3219
telemt_me_idle_close_by_peer_total 3219
telemt_me_route_drop_no_conn_total 18710
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52994
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3079
telemt_me_writer_restored_same_endpoint_total 3039
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 52989
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 287894480 (274.56 MB)
telemt_user_octets_to_client{user="hello"} 12827591240 (11.95 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12238.7 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69710
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 4999
telemt_upstream_connect_success_total 4958
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 5795
telemt_me_reconnect_success_total 4303
telemt_me_reader_eof_total 4450
telemt_me_idle_close_by_peer_total 4450
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 17207
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65737
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 165
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4375
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4295
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 65719
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 306881412 (292.66 MB)
telemt_user_octets_to_client{user="hello"} 14965692800 (13.94 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 33
```