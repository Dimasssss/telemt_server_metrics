# Server Metrics 2026-03-12 01:59:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15297.4 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125479
telemt_connections_bad_total 1350
telemt_handshake_timeouts_total 1740
telemt_upstream_connect_attempt_total 3518
telemt_upstream_connect_success_total 3518
telemt_upstream_connect_attempts_per_request{bucket="1"} 3518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 2758
telemt_me_reconnect_success_total 2746
telemt_me_reader_eof_total 2894
telemt_me_idle_close_by_peer_total 2894
telemt_me_route_drop_no_conn_total 45151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118408
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2779
telemt_me_writer_restored_same_endpoint_total 2730
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 118272
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 848963044 (809.63 MB)
telemt_user_octets_to_client{user="hello"} 35500947104 (33.06 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15298.1 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42962
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 475
telemt_upstream_connect_attempt_total 4437
telemt_upstream_connect_success_total 4434
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3493
telemt_me_reconnect_success_total 3468
telemt_me_reader_eof_total 3669
telemt_me_idle_close_by_peer_total 3669
telemt_me_route_drop_no_conn_total 11766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40120
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3493
telemt_me_writer_restored_same_endpoint_total 3459
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 40299
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 682863295 (651.23 MB)
telemt_user_octets_to_client{user="hello"} 13774647978 (12.83 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15297.7 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176556
telemt_connections_bad_total 1119
telemt_handshake_timeouts_total 13195
telemt_upstream_connect_attempt_total 4754
telemt_upstream_connect_success_total 4752
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 3668
telemt_me_reconnect_success_total 3618
telemt_me_reader_eof_total 3727
telemt_me_idle_close_by_peer_total 3727
telemt_me_route_drop_no_conn_total 23082
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72531
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3567
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 3577
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 72874
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 656495580 (626.08 MB)
telemt_user_octets_to_client{user="hello"} 25171508033 (23.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15298.2 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65047
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 1478
telemt_upstream_connect_attempt_total 4573
telemt_upstream_connect_success_total 4550
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3788
telemt_me_reconnect_success_total 3774
telemt_me_reader_eof_total 3987
telemt_me_idle_close_by_peer_total 3987
telemt_me_route_drop_no_conn_total 22845
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62580
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3798
telemt_me_writer_restored_same_endpoint_total 3753
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 62570
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 355353136 (338.89 MB)
telemt_user_octets_to_client{user="hello"} 14211656328 (13.24 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15298.1 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83903
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 5845
telemt_upstream_connect_success_total 5790
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 6498
telemt_me_reconnect_success_total 5004
telemt_me_reader_eof_total 5185
telemt_me_idle_close_by_peer_total 5185
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 20718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 249
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5087
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 4991
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 79573
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 363785396 (346.93 MB)
telemt_user_octets_to_client{user="hello"} 16383492868 (15.26 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```