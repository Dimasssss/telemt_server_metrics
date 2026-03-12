# Server Metrics 2026-03-12 19:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49664.5 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739868
telemt_connections_bad_total 20544
telemt_handshake_timeouts_total 17906
telemt_upstream_connect_attempt_total 9758
telemt_upstream_connect_success_total 9703
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 574
telemt_me_reconnect_attempts_total 16016
telemt_me_reconnect_success_total 7170
telemt_me_reader_eof_total 7762
telemt_me_idle_close_by_peer_total 7761
telemt_me_route_drop_no_conn_total 685444
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1625000
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8124
telemt_desync_full_logged_total 2087
telemt_desync_suppressed_total 6037
telemt_desync_frames_bucket_total{bucket="1_2"} 2121
telemt_desync_frames_bucket_total{bucket="3_10"} 2929
telemt_desync_frames_bucket_total{bucket="gt_10"} 3074
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 7549
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7157
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 1624490
telemt_user_connections_current{user="hello"} 1208
telemt_user_octets_from_client{user="hello"} 25212292216 (23.48 GB)
telemt_user_octets_to_client{user="hello"} 558173273492 (519.84 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79285.0 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739122
telemt_connections_bad_total 10388
telemt_handshake_timeouts_total 30010
telemt_upstream_connect_attempt_total 20123
telemt_upstream_connect_success_total 20094
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3375
telemt_me_reconnect_attempts_total 14548
telemt_me_reconnect_success_total 14461
telemt_me_reader_eof_total 15371
telemt_me_idle_close_by_peer_total 15371
telemt_me_route_drop_no_conn_total 237098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2879
telemt_desync_full_logged_total 883
telemt_desync_suppressed_total 1996
telemt_desync_frames_bucket_total{bucket="1_2"} 1121
telemt_desync_frames_bucket_total{bucket="3_10"} 950
telemt_desync_frames_bucket_total{bucket="gt_10"} 808
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 14611
telemt_me_writer_restored_same_endpoint_total 14452
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 668067
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 11350120348 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 250947590599 (233.71 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79285.0 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1528097
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 103958
telemt_upstream_connect_attempt_total 18683
telemt_upstream_connect_success_total 18678
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1187
telemt_me_reconnect_attempts_total 15573
telemt_me_reconnect_success_total 14328
telemt_me_reader_eof_total 15116
telemt_me_idle_close_by_peer_total 15115
telemt_me_route_drop_no_conn_total 503507
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1173651
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4789
telemt_desync_full_logged_total 1476
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14461
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14287
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 1173500
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 18291575392 (17.04 GB)
telemt_user_octets_to_client{user="hello"} 435162603325 (405.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79285.5 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935515
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 70034
telemt_upstream_connect_attempt_total 20331
telemt_upstream_connect_success_total 20250
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1647
telemt_me_reconnect_attempts_total 23998
telemt_me_reconnect_success_total 16273
telemt_me_reader_eof_total 17378
telemt_me_idle_close_by_peer_total 17378
telemt_me_route_drop_no_conn_total 331765
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809539
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16646
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16252
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 808894
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 12589622336 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 331469639892 (308.71 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79285.3 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051233
telemt_connections_bad_total 12339
telemt_handshake_timeouts_total 8668
telemt_upstream_connect_attempt_total 24558
telemt_upstream_connect_success_total 24261
telemt_upstream_connect_fail_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 24558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 297
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 31305
telemt_me_reconnect_success_total 20269
telemt_me_reader_eof_total 21296
telemt_me_idle_close_by_peer_total 21296
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 393329
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 964126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3613
telemt_desync_full_logged_total 1262
telemt_desync_suppressed_total 2351
telemt_desync_frames_bucket_total{bucket="1_2"} 1026
telemt_desync_frames_bucket_total{bucket="3_10"} 1204
telemt_desync_frames_bucket_total{bucket="gt_10"} 1383
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20842
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20225
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 963996
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 11927322836 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 330463725064 (307.77 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 78
```