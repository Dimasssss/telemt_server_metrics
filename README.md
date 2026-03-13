# Server Metrics 2026-03-13 02:03:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72313.5 (20h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2061268
telemt_connections_bad_total 26149
telemt_handshake_timeouts_total 21984
telemt_upstream_connect_attempt_total 14351
telemt_upstream_connect_success_total 14268
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1261
telemt_me_reconnect_attempts_total 19503
telemt_me_reconnect_success_total 10642
telemt_me_reader_eof_total 11501
telemt_me_idle_close_by_peer_total 11500
telemt_me_route_drop_no_conn_total 801019
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1912650
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8701
telemt_desync_full_logged_total 2265
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2293
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11069
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10629
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 1912107
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 27996005564 (26.07 GB)
telemt_user_octets_to_client{user="hello"} 667583550540 (621.74 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101934.0 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847100
telemt_connections_bad_total 11794
telemt_handshake_timeouts_total 32067
telemt_upstream_connect_attempt_total 25960
telemt_upstream_connect_success_total 25931
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3450
telemt_me_reconnect_attempts_total 19299
telemt_me_reconnect_success_total 19192
telemt_me_reader_eof_total 20446
telemt_me_idle_close_by_peer_total 20446
telemt_me_route_drop_no_conn_total 272706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 768189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3085
telemt_desync_full_logged_total 968
telemt_desync_suppressed_total 2117
telemt_desync_frames_bucket_total{bucket="1_2"} 1252
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 19380
telemt_me_writer_restored_same_endpoint_total 19183
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 770092
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 12304463200 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 290832787923 (270.86 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101933.8 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1758188
telemt_connections_bad_total 9009
telemt_handshake_timeouts_total 117825
telemt_upstream_connect_attempt_total 23796
telemt_upstream_connect_success_total 23786
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1596
telemt_me_reconnect_attempts_total 19600
telemt_me_reconnect_success_total 18337
telemt_me_reader_eof_total 19421
telemt_me_idle_close_by_peer_total 19420
telemt_me_route_drop_no_conn_total 574650
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1382238
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18511
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18296
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1381834
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 20143311076 (18.76 GB)
telemt_user_octets_to_client{user="hello"} 499751233373 (465.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101934.0 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100216
telemt_connections_bad_total 13112
telemt_handshake_timeouts_total 72905
telemt_upstream_connect_attempt_total 35686
telemt_upstream_connect_success_total 33414
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 35412
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11280
telemt_me_reconnect_attempts_total 31376
telemt_me_reconnect_success_total 22454
telemt_me_reader_eof_total 24267
telemt_me_idle_close_by_peer_total 24260
telemt_me_route_drop_no_conn_total 390095
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22877
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22431
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 948462
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 14503262097 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 371825395950 (346.29 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 101934.1 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214120
telemt_connections_bad_total 12600
telemt_handshake_timeouts_total 9482
telemt_upstream_connect_attempt_total 31941
telemt_upstream_connect_success_total 31547
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 31941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 1873
telemt_me_reconnect_attempts_total 38907
telemt_me_reconnect_success_total 26450
telemt_me_reader_eof_total 27798
telemt_me_idle_close_by_peer_total 27798
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 454481
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1122102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4183
telemt_desync_full_logged_total 1483
telemt_desync_suppressed_total 2700
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1384
telemt_desync_frames_bucket_total{bucket="gt_10"} 1545
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27145
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 26402
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 695
telemt_user_connections_total{user="hello"} 1121958
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 13781213900 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 386752086324 (360.19 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 44
```