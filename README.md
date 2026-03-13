# Server Metrics 2026-03-13 08:16:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94661.4 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2636755
telemt_connections_bad_total 36269
telemt_handshake_timeouts_total 28704
telemt_upstream_connect_attempt_total 18428
telemt_upstream_connect_success_total 18327
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22482
telemt_me_reconnect_success_total 13609
telemt_me_reader_eof_total 14666
telemt_me_idle_close_by_peer_total 14665
telemt_me_route_drop_no_conn_total 983538
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2412455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10898
telemt_desync_full_logged_total 2812
telemt_desync_suppressed_total 8086
telemt_desync_frames_bucket_total{bucket="1_2"} 2797
telemt_desync_frames_bucket_total{bucket="3_10"} 4069
telemt_desync_frames_bucket_total{bucket="gt_10"} 4032
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14075
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13596
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2412000
telemt_user_connections_current{user="hello"} 1690
telemt_user_octets_from_client{user="hello"} 34180821388 (31.83 GB)
telemt_user_octets_to_client{user="hello"} 804721097888 (749.45 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 124281.9 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076054
telemt_connections_bad_total 13526
telemt_handshake_timeouts_total 84900
telemt_upstream_connect_attempt_total 31036
telemt_upstream_connect_success_total 31005
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3630
telemt_me_reconnect_attempts_total 23300
telemt_me_reconnect_success_total 23179
telemt_me_reader_eof_total 24706
telemt_me_idle_close_by_peer_total 24706
telemt_me_route_drop_no_conn_total 331715
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4146
telemt_desync_full_logged_total 1267
telemt_desync_suppressed_total 2879
telemt_desync_frames_bucket_total{bucket="1_2"} 1535
telemt_desync_frames_bucket_total{bucket="3_10"} 1353
telemt_desync_frames_bucket_total{bucket="gt_10"} 1258
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 23408
telemt_me_writer_restored_same_endpoint_total 23170
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 938564
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 14379745224 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 349532055815 (325.53 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 124281.9 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2112206
telemt_connections_bad_total 23665
telemt_handshake_timeouts_total 141966
telemt_upstream_connect_attempt_total 28557
telemt_upstream_connect_success_total 28547
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 23285
telemt_me_reconnect_success_total 22004
telemt_me_reader_eof_total 23302
telemt_me_idle_close_by_peer_total 23301
telemt_me_route_drop_no_conn_total 682837
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1679619
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5678
telemt_desync_full_logged_total 1798
telemt_desync_suppressed_total 3880
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 2075
telemt_desync_frames_bucket_total{bucket="gt_10"} 2672
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22220
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21963
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1679083
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 27942108396 (26.02 GB)
telemt_user_octets_to_client{user="hello"} 610997736641 (569.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 124282.2 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334374
telemt_connections_bad_total 14217
telemt_handshake_timeouts_total 83298
telemt_upstream_connect_attempt_total 41598
telemt_upstream_connect_success_total 39297
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41324
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11446
telemt_me_reconnect_attempts_total 36195
telemt_me_reconnect_success_total 27256
telemt_me_reader_eof_total 29354
telemt_me_idle_close_by_peer_total 29347
telemt_me_route_drop_no_conn_total 470358
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1116867
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27726
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27232
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 1121619
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 16951922981 (15.79 GB)
telemt_user_octets_to_client{user="hello"} 449110865298 (418.27 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 124282.0 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1477087
telemt_connections_bad_total 28846
telemt_handshake_timeouts_total 12312
telemt_upstream_connect_attempt_total 39109
telemt_upstream_connect_success_total 38632
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 39109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_keepalive_timeout_total 2134
telemt_me_reconnect_attempts_total 46195
telemt_me_reconnect_success_total 32454
telemt_me_reader_eof_total 34060
telemt_me_idle_close_by_peer_total 34060
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 541072
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1355553
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4780
telemt_desync_full_logged_total 1707
telemt_desync_suppressed_total 3073
telemt_desync_frames_bucket_total{bucket="1_2"} 1457
telemt_desync_frames_bucket_total{bucket="3_10"} 1546
telemt_desync_frames_bucket_total{bucket="gt_10"} 1777
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33240
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32398
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 1355360
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 17269523572 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 468382309908 (436.22 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 108
```