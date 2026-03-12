# Server Metrics 2026-03-12 09:54:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14140.3 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454407
telemt_connections_bad_total 1457
telemt_handshake_timeouts_total 2693
telemt_upstream_connect_attempt_total 2781
telemt_upstream_connect_success_total 2766
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 280
telemt_me_reconnect_attempts_total 3323
telemt_me_reconnect_success_total 2030
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2137
telemt_me_route_drop_no_conn_total 155421
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439795
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2041
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 1529
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2087
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 439670
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 6514428296 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 119106055312 (110.93 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43760.8 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269896
telemt_connections_bad_total 2982
telemt_handshake_timeouts_total 8292
telemt_upstream_connect_attempt_total 11052
telemt_upstream_connect_success_total 11046
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 662
telemt_me_reconnect_attempts_total 8722
telemt_me_reconnect_success_total 8679
telemt_me_reader_eof_total 9227
telemt_me_idle_close_by_peer_total 9227
telemt_me_route_drop_no_conn_total 78379
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 508
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8748
telemt_me_writer_restored_same_endpoint_total 8670
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 240708
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 3344181327 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 91011940010 (84.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43760.6 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705265
telemt_connections_bad_total 3400
telemt_handshake_timeouts_total 51883
telemt_upstream_connect_attempt_total 11093
telemt_upstream_connect_success_total 11088
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 8622
telemt_me_reconnect_success_total 8549
telemt_me_reader_eof_total 8983
telemt_me_idle_close_by_peer_total 8983
telemt_me_route_drop_no_conn_total 153150
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437653
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2032
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 1059
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8554
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8508
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 437912
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 5357444612 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 145948844037 (135.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43761.0 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351803
telemt_connections_bad_total 1835
telemt_handshake_timeouts_total 25503
telemt_upstream_connect_attempt_total 11987
telemt_upstream_connect_success_total 11939
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 11987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 818
telemt_me_reconnect_attempts_total 9786
telemt_me_reconnect_success_total 9749
telemt_me_reader_eof_total 10341
telemt_me_idle_close_by_peer_total 10341
telemt_me_route_drop_no_conn_total 120173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296472
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 651
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9811
telemt_me_writer_restored_same_endpoint_total 9728
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 296295
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 3670356304 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 116874774444 (108.85 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43760.8 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398905
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 3092
telemt_upstream_connect_attempt_total 14196
telemt_upstream_connect_success_total 14028
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 14196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 620
telemt_me_reconnect_attempts_total 13353
telemt_me_reconnect_success_total 11830
telemt_me_reader_eof_total 12315
telemt_me_idle_close_by_peer_total 12315
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 128990
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377147
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1604
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11985
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11808
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 377082
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 4155245188 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 90843674996 (84.60 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 105
```