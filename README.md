# Server Metrics 2026-03-14 15:01:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 6222.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248536
telemt_connections_bad_total 7571
telemt_handshake_timeouts_total 3293
telemt_upstream_connect_attempt_total 1218
telemt_upstream_connect_success_total 1211
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 1645
telemt_me_reconnect_success_total 862
telemt_me_reader_eof_total 892
telemt_me_idle_close_by_peer_total 892
telemt_me_route_drop_no_conn_total 97077
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227372
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 896
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 227363
telemt_user_connections_current{user="hello"} 1743
telemt_user_octets_from_client{user="hello"} 3842362104 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 65829967336 (61.31 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 6227.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99455
telemt_connections_bad_total 8520
telemt_handshake_timeouts_total 3736
telemt_upstream_connect_attempt_total 1306
telemt_upstream_connect_success_total 1294
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 969
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 30856
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79914
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 457
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 351
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 966
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 79872
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 1095908036 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 34916421184 (32.52 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 6090.6 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187448
telemt_connections_bad_total 662
telemt_handshake_timeouts_total 37874
telemt_upstream_connect_attempt_total 1403
telemt_upstream_connect_success_total 1398
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2194
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 1075
telemt_me_idle_close_by_peer_total 1075
telemt_me_route_drop_no_conn_total 51790
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140000
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 235
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1085
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 1021
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 139926
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 2117367640 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 43452491232 (40.47 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 5945.1 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96300
telemt_connections_bad_total 23730
telemt_handshake_timeouts_total 13089
telemt_upstream_connect_attempt_total 1574
telemt_upstream_connect_success_total 1574
telemt_upstream_connect_attempts_per_request{bucket="1"} 1574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1242
telemt_me_reconnect_success_total 1234
telemt_me_reader_eof_total 1243
telemt_me_idle_close_by_peer_total 1243
telemt_me_route_drop_no_conn_total 22092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58376
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1233
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 58342
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 1213422520 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 17127509716 (15.95 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 6240.4 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99274
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 1645
telemt_upstream_connect_attempt_total 1396
telemt_upstream_connect_success_total 1368
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1681
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1072
telemt_me_idle_close_by_peer_total 1072
telemt_me_route_drop_no_conn_total 33865
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91270
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1073
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 91271
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 1384256764 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 31053219468 (28.92 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 106
```