# Server Metrics 2026-03-12 15:20:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33726.4 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1213141
telemt_connections_bad_total 20231
telemt_handshake_timeouts_total 12269
telemt_upstream_connect_attempt_total 6769
telemt_upstream_connect_success_total 6733
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 8913
telemt_me_reconnect_success_total 5008
telemt_me_reader_eof_total 5330
telemt_me_idle_close_by_peer_total 5329
telemt_me_route_drop_no_conn_total 430914
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6073
telemt_desync_full_logged_total 1518
telemt_desync_suppressed_total 4555
telemt_desync_frames_bucket_total{bucket="1_2"} 1557
telemt_desync_frames_bucket_total{bucket="3_10"} 2183
telemt_desync_frames_bucket_total{bucket="gt_10"} 2333
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5190
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4995
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1141251
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 17944101380 (16.71 GB)
telemt_user_octets_to_client{user="hello"} 332892903608 (310.03 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63347.0 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548914
telemt_connections_bad_total 6619
telemt_handshake_timeouts_total 27263
telemt_upstream_connect_attempt_total 15264
telemt_upstream_connect_success_total 15257
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 11967
telemt_me_reconnect_success_total 11900
telemt_me_reader_eof_total 12642
telemt_me_idle_close_by_peer_total 12642
telemt_me_route_drop_no_conn_total 160924
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489427
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1287
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12014
telemt_me_writer_restored_same_endpoint_total 11891
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 489926
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 7487980751 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 172847308178 (160.98 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63346.8 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171686
telemt_connections_bad_total 6159
telemt_handshake_timeouts_total 81827
telemt_upstream_connect_attempt_total 15259
telemt_upstream_connect_success_total 15254
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 985
telemt_me_reconnect_attempts_total 12942
telemt_me_reconnect_success_total 11719
telemt_me_reader_eof_total 12357
telemt_me_idle_close_by_peer_total 12357
telemt_me_route_drop_no_conn_total 314130
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859608
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3578
telemt_desync_full_logged_total 1101
telemt_desync_suppressed_total 2477
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 1294
telemt_desync_frames_bucket_total{bucket="gt_10"} 1739
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11805
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11678
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 859796
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 11409248140 (10.63 GB)
telemt_user_octets_to_client{user="hello"} 269457818413 (250.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63347.5 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693653
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 57772
telemt_upstream_connect_attempt_total 16799
telemt_upstream_connect_success_total 16730
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 18791
telemt_me_reconnect_success_total 13554
telemt_me_reader_eof_total 14453
telemt_me_idle_close_by_peer_total 14453
telemt_me_route_drop_no_conn_total 235416
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1180
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 772
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13819
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13533
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 593892
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 7144205504 (6.65 GB)
telemt_user_octets_to_client{user="hello"} 235280417444 (219.12 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63347.2 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780771
telemt_connections_bad_total 7230
telemt_handshake_timeouts_total 6203
telemt_upstream_connect_attempt_total 20020
telemt_upstream_connect_success_total 19771
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 20020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1114
telemt_me_reconnect_attempts_total 23827
telemt_me_reconnect_success_total 16590
telemt_me_reader_eof_total 17360
telemt_me_idle_close_by_peer_total 17360
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 271891
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721223
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2866
telemt_desync_full_logged_total 970
telemt_desync_suppressed_total 1896
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 1074
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16988
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16556
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 721122
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 8579836208 (7.99 GB)
telemt_user_octets_to_client{user="hello"} 202230129016 (188.34 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 117
```