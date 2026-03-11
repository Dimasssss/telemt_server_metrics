# Server Metrics 2026-03-11 23:16:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5506.6 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50912
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 1359
telemt_upstream_connect_success_total 1359
telemt_upstream_connect_attempts_per_request{bucket="1"} 1359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 1052
telemt_me_idle_close_by_peer_total 1052
telemt_me_route_drop_no_conn_total 19102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48038
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_restored_same_endpoint_total 1013
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 48015
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 290613584 (277.15 MB)
telemt_user_octets_to_client{user="hello"} 12426770304 (11.57 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5507.2 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18534
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 1573
telemt_upstream_connect_success_total 1573
telemt_upstream_connect_attempts_per_request{bucket="1"} 1573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 814
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1240
telemt_me_reconnect_success_total 1232
telemt_me_reader_eof_total 1273
telemt_me_idle_close_by_peer_total 1273
telemt_me_route_drop_no_conn_total 4782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17621
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 17619
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 512914656 (489.15 MB)
telemt_user_octets_to_client{user="hello"} 8207678860 (7.64 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5507.1 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44305
telemt_connections_bad_total 500
telemt_handshake_timeouts_total 3716
telemt_upstream_connect_attempt_total 2076
telemt_upstream_connect_success_total 2075
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 1427
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1342
telemt_me_route_drop_no_conn_total 8482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29446
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1306
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1346
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 29794
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 236406828 (225.46 MB)
telemt_user_octets_to_client{user="hello"} 16212214657 (15.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5507.4 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28304
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 1725
telemt_upstream_connect_success_total 1715
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 694
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1385
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 1408
telemt_me_idle_close_by_peer_total 1408
telemt_me_route_drop_no_conn_total 8459
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27508
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1384
telemt_me_writer_restored_same_endpoint_total 1357
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 27507
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 157633392 (150.33 MB)
telemt_user_octets_to_client{user="hello"} 10405329492 (9.69 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5507.2 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34801
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 438
telemt_upstream_connect_attempt_total 2568
telemt_upstream_connect_success_total 2541
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2606
telemt_me_reconnect_success_total 2209
telemt_me_reader_eof_total 2203
telemt_me_idle_close_by_peer_total 2203
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 7830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32749
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 31
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 2228
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 2204
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 32746
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 203903712 (194.46 MB)
telemt_user_octets_to_client{user="hello"} 9910059472 (9.23 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```