# Server Metrics 2026-03-11 23:57:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7955.2 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71099
telemt_connections_bad_total 1292
telemt_handshake_timeouts_total 212
telemt_upstream_connect_attempt_total 1906
telemt_upstream_connect_success_total 1906
telemt_upstream_connect_attempts_per_request{bucket="1"} 1906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 1487
telemt_me_reader_eof_total 1553
telemt_me_idle_close_by_peer_total 1553
telemt_me_route_drop_no_conn_total 26627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66637
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1507
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 66595
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 449710724 (428.88 MB)
telemt_user_octets_to_client{user="hello"} 20884320212 (19.45 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7955.9 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25309
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 2405
telemt_upstream_connect_success_total 2402
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 2405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 1787
telemt_me_reader_eof_total 1874
telemt_me_idle_close_by_peer_total 1874
telemt_me_route_drop_no_conn_total 6671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23829
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1798
telemt_me_writer_restored_same_endpoint_total 1778
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 24008
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 553280687 (527.65 MB)
telemt_user_octets_to_client{user="hello"} 9905601142 (9.23 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7955.9 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73229
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 5203
telemt_upstream_connect_attempt_total 2803
telemt_upstream_connect_success_total 2801
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 2062
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 2015
telemt_me_idle_close_by_peer_total 2015
telemt_me_route_drop_no_conn_total 11413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39146
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1948
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1976
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 39491
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 478818228 (456.64 MB)
telemt_user_octets_to_client{user="hello"} 19628770177 (18.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7956.1 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37324
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 571
telemt_upstream_connect_attempt_total 2355
telemt_upstream_connect_success_total 2343
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 1988
telemt_me_idle_close_by_peer_total 1988
telemt_me_route_drop_no_conn_total 12032
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36174
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1929
telemt_me_writer_restored_same_endpoint_total 1895
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 36170
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 183339860 (174.85 MB)
telemt_user_octets_to_client{user="hello"} 11206498776 (10.44 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7956.0 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48731
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 3514
telemt_upstream_connect_success_total 3481
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 4536
telemt_me_reconnect_success_total 3047
telemt_me_reader_eof_total 3120
telemt_me_idle_close_by_peer_total 3120
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 11231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45373
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 78
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3110
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 3041
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 45369
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 244029272 (232.72 MB)
telemt_user_octets_to_client{user="hello"} 12353068924 (11.50 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 40
```