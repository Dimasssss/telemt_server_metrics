# Server Metrics 2026-03-11 23:52:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7649.3 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68531
telemt_connections_bad_total 1292
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 1869
telemt_upstream_connect_success_total 1869
telemt_upstream_connect_attempts_per_request{bucket="1"} 1869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1455
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1516
telemt_me_idle_close_by_peer_total 1516
telemt_me_route_drop_no_conn_total 25822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64109
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1470
telemt_me_writer_restored_same_endpoint_total 1434
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 64065
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 434967032 (414.82 MB)
telemt_user_octets_to_client{user="hello"} 20249304536 (18.86 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 7650.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24380
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 2174
telemt_upstream_connect_success_total 2174
telemt_upstream_connect_attempts_per_request{bucket="1"} 2174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1755
telemt_me_reconnect_success_total 1742
telemt_me_reader_eof_total 1829
telemt_me_idle_close_by_peer_total 1829
telemt_me_route_drop_no_conn_total 6515
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23118
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
telemt_me_writer_removed_unexpected_total 1751
telemt_me_writer_restored_same_endpoint_total 1733
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 23117
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 551287532 (525.75 MB)
telemt_user_octets_to_client{user="hello"} 9825183560 (9.15 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 7649.9 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69095
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 4871
telemt_upstream_connect_attempt_total 2749
telemt_upstream_connect_success_total 2747
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 2008
telemt_me_reconnect_success_total 1964
telemt_me_reader_eof_total 1959
telemt_me_idle_close_by_peer_total 1959
telemt_me_route_drop_no_conn_total 11200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37990
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
telemt_me_writer_removed_unexpected_total 1892
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1923
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 38335
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 474151960 (452.19 MB)
telemt_user_octets_to_client{user="hello"} 19361232457 (18.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 7650.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36090
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 2305
telemt_upstream_connect_success_total 2293
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1875
telemt_me_reconnect_success_total 1866
telemt_me_reader_eof_total 1936
telemt_me_idle_close_by_peer_total 1936
telemt_me_route_drop_no_conn_total 11432
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_restored_same_endpoint_total 1845
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 34985
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 180711112 (172.34 MB)
telemt_user_octets_to_client{user="hello"} 11156523980 (10.39 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7650.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47070
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 3409
telemt_upstream_connect_success_total 3377
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 4431
telemt_me_reconnect_success_total 2943
telemt_me_reader_eof_total 3013
telemt_me_idle_close_by_peer_total 3013
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 10868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 76
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3003
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 2937
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 43883
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 241044936 (229.88 MB)
telemt_user_octets_to_client{user="hello"} 12255336356 (11.41 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 34
```