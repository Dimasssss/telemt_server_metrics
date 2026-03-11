# Server Metrics 2026-03-11 02:38:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43856.1 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854764
telemt_connections_bad_total 10059
telemt_handshake_timeouts_total 15025
telemt_upstream_connect_attempt_total 9544
telemt_upstream_connect_success_total 9535
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 18958
telemt_me_reconnect_success_total 7289
telemt_me_reader_eof_total 7961
telemt_me_idle_close_by_peer_total 7961
telemt_me_route_drop_no_conn_total 342781
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 802435
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3666
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 2632
telemt_desync_frames_bucket_total{bucket="1_2"} 1075
telemt_desync_frames_bucket_total{bucket="3_10"} 1370
telemt_desync_frames_bucket_total{bucket="gt_10"} 1221
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7716
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7283
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 802169
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 10873871032 (10.13 GB)
telemt_user_octets_to_client{user="hello"} 239946299316 (223.47 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43912.9 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361584
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18206
telemt_upstream_connect_attempt_total 17170
telemt_upstream_connect_success_total 14280
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1744
telemt_me_reconnect_attempts_total 9936
telemt_me_reconnect_success_total 9119
telemt_me_reader_eof_total 9629
telemt_me_idle_close_by_peer_total 9627
telemt_me_route_drop_no_conn_total 177398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9234
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9098
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 312016
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 2943409866 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 73086427752 (68.07 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43912.7 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602932
telemt_connections_bad_total 4907
telemt_handshake_timeouts_total 34637
telemt_upstream_connect_attempt_total 11977
telemt_upstream_connect_success_total 11816
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 11977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 19594
telemt_me_reconnect_success_total 8527
telemt_me_reader_eof_total 9262
telemt_me_idle_close_by_peer_total 9262
telemt_me_route_drop_no_conn_total 205043
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534595
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1548
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8989
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 535495
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 7017138021 (6.54 GB)
telemt_user_octets_to_client{user="hello"} 164470804933 (153.18 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43913.1 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452576
telemt_connections_bad_total 41546
telemt_handshake_timeouts_total 43835
telemt_upstream_connect_attempt_total 12788
telemt_upstream_connect_success_total 12788
telemt_upstream_connect_attempts_per_request{bucket="1"} 12788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 438
telemt_me_reconnect_attempts_total 11613
telemt_me_reconnect_success_total 10575
telemt_me_reader_eof_total 11212
telemt_me_idle_close_by_peer_total 11212
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 135704
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353576
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 10702
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10556
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 353245
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 4340668536 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 94547011476 (88.05 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43912.8 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476899
telemt_connections_bad_total 5791
telemt_handshake_timeouts_total 3019
telemt_upstream_connect_attempt_total 12941
telemt_upstream_connect_success_total 12887
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 12941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 14411
telemt_me_reconnect_success_total 10636
telemt_me_reader_eof_total 11210
telemt_me_idle_close_by_peer_total 11210
telemt_me_route_drop_no_conn_total 154412
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435030
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2314
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1412
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 10890
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10636
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 434697
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 8502604288 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 153622896800 (143.07 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 37
```