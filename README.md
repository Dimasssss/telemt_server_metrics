# Server Metrics 2026-03-15 01:24:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 11425.7 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143714
telemt_connections_bad_total 1638
telemt_handshake_timeouts_total 508
telemt_upstream_connect_attempt_total 2417
telemt_upstream_connect_success_total 2408
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1829
telemt_me_reconnect_success_total 1819
telemt_me_reader_eof_total 1910
telemt_me_idle_close_by_peer_total 1910
telemt_me_route_drop_no_conn_total 44992
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125707
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 319
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1843
telemt_me_writer_restored_same_endpoint_total 1808
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 125694
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 1443090532 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 42695102228 (39.76 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 11426.2 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58980
telemt_connections_bad_total 10611
telemt_handshake_timeouts_total 2345
telemt_upstream_connect_attempt_total 3450
telemt_upstream_connect_success_total 3432
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2547
telemt_me_reconnect_success_total 2531
telemt_me_reader_eof_total 2635
telemt_me_idle_close_by_peer_total 2635
telemt_me_route_drop_no_conn_total 11745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44366
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2504
telemt_me_writer_restored_same_endpoint_total 2523
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 44662
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 1481161959 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 12538794360 (11.68 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 11426.4 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95117
telemt_connections_bad_total 1793
telemt_handshake_timeouts_total 7961
telemt_upstream_connect_attempt_total 2614
telemt_upstream_connect_success_total 2603
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 2020
telemt_me_reconnect_success_total 2013
telemt_me_reader_eof_total 2112
telemt_me_idle_close_by_peer_total 2112
telemt_me_route_drop_no_conn_total 21504
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2032
telemt_me_writer_restored_same_endpoint_total 1994
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 83577
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 861031128 (821.14 MB)
telemt_user_octets_to_client{user="hello"} 29243813028 (27.24 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 11426.3 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87580
telemt_connections_bad_total 24759
telemt_handshake_timeouts_total 2003
telemt_upstream_connect_attempt_total 4209
telemt_upstream_connect_success_total 4114
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 4209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4826
telemt_me_reconnect_success_total 3520
telemt_me_reader_eof_total 3638
telemt_me_idle_close_by_peer_total 3638
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 15992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59395
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3590
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 3502
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 59397
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 345289452 (329.29 MB)
telemt_user_octets_to_client{user="hello"} 11758766816 (10.95 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 11426.7 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51029
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 691
telemt_upstream_connect_attempt_total 2491
telemt_upstream_connect_success_total 2479
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1898
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1991
telemt_me_idle_close_by_peer_total 1991
telemt_me_route_drop_no_conn_total 12446
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48874
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1907
telemt_me_writer_restored_same_endpoint_total 1881
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 48874
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 355704764 (339.23 MB)
telemt_user_octets_to_client{user="hello"} 18005809288 (16.77 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 27
```