# Server Metrics 2026-03-15 05:24:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 25784.4 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341059
telemt_connections_bad_total 4989
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 5527
telemt_upstream_connect_success_total 5506
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4234
telemt_me_reconnect_success_total 4213
telemt_me_reader_eof_total 4453
telemt_me_idle_close_by_peer_total 4453
telemt_me_route_drop_no_conn_total 109226
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304177
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 721
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4262
telemt_me_writer_restored_same_endpoint_total 4202
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 304195
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 3394936984 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 111862613200 (104.18 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 25785.1 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132456
telemt_connections_bad_total 18282
telemt_handshake_timeouts_total 4716
telemt_upstream_connect_attempt_total 7660
telemt_upstream_connect_success_total 7626
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6046
telemt_me_reconnect_success_total 6016
telemt_me_reader_eof_total 6359
telemt_me_idle_close_by_peer_total 6359
telemt_me_route_drop_no_conn_total 30050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106110
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6029
telemt_me_writer_restored_same_endpoint_total 6008
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 106406
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 1927523203 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 34790588108 (32.40 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 25785.4 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247448
telemt_connections_bad_total 4729
telemt_handshake_timeouts_total 26708
telemt_upstream_connect_attempt_total 5980
telemt_upstream_connect_success_total 5953
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4678
telemt_me_reconnect_success_total 4655
telemt_me_reader_eof_total 4930
telemt_me_idle_close_by_peer_total 4930
telemt_me_route_drop_no_conn_total 59193
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4704
telemt_me_writer_restored_same_endpoint_total 4636
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 205481
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 2883486808 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 79775732804 (74.30 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 25785.2 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181421
telemt_connections_bad_total 36143
telemt_handshake_timeouts_total 13096
telemt_upstream_connect_attempt_total 8837
telemt_upstream_connect_success_total 8651
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 8837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12127
telemt_me_reconnect_success_total 7354
telemt_me_reader_eof_total 7766
telemt_me_idle_close_by_peer_total 7766
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 39707
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128758
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 215
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7563
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7331
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 128761
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 1054093028 (1005.26 MB)
telemt_user_octets_to_client{user="hello"} 45877012128 (42.73 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 25786.5 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117051
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 5929
telemt_upstream_connect_success_total 5904
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4629
telemt_me_reconnect_success_total 4609
telemt_me_reader_eof_total 4917
telemt_me_idle_close_by_peer_total 4917
telemt_me_route_drop_no_conn_total 32512
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111753
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 456
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4654
telemt_me_writer_restored_same_endpoint_total 4601
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 111751
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 1070827132 (1021.22 MB)
telemt_user_octets_to_client{user="hello"} 38298322320 (35.67 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 64
```