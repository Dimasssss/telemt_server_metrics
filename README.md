# Server Metrics 2026-03-13 14:19:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 116444.3 (32h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3554639
telemt_connections_bad_total 37400
telemt_handshake_timeouts_total 60587
telemt_upstream_connect_attempt_total 22794
telemt_upstream_connect_success_total 22666
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2150
telemt_me_reconnect_attempts_total 26952
telemt_me_reconnect_success_total 16867
telemt_me_reader_eof_total 18133
telemt_me_idle_close_by_peer_total 18132
telemt_me_route_drop_no_conn_total 1321812
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3263772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13466
telemt_desync_full_logged_total 3528
telemt_desync_suppressed_total 9938
telemt_desync_frames_bucket_total{bucket="1_2"} 3425
telemt_desync_frames_bucket_total{bucket="3_10"} 5092
telemt_desync_frames_bucket_total{bucket="gt_10"} 4949
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17417
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16854
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 3263483
telemt_user_connections_current{user="hello"} 1717
telemt_user_octets_from_client{user="hello"} 44898764264 (41.82 GB)
telemt_user_octets_to_client{user="hello"} 1036923551192 (965.71 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16108.0 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225963
telemt_connections_bad_total 12830
telemt_handshake_timeouts_total 5645
telemt_upstream_connect_attempt_total 3984
telemt_upstream_connect_success_total 3906
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 3984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5354
telemt_me_reconnect_success_total 3066
telemt_me_reader_eof_total 3237
telemt_me_idle_close_by_peer_total 3237
telemt_me_route_drop_no_conn_total 82275
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201518
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 774
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 585
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3168
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3059
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 201542
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 2106216252 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 58128496488 (54.14 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 146064.8 (40h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2660370
telemt_connections_bad_total 27310
telemt_handshake_timeouts_total 178087
telemt_upstream_connect_attempt_total 32959
telemt_upstream_connect_success_total 32949
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3238
telemt_me_reconnect_attempts_total 27876
telemt_me_reconnect_success_total 25329
telemt_me_reader_eof_total 26860
telemt_me_idle_close_by_peer_total 26859
telemt_me_route_drop_no_conn_total 894576
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2173260
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7713
telemt_desync_full_logged_total 2515
telemt_desync_suppressed_total 5198
telemt_desync_frames_bucket_total{bucket="1_2"} 1208
telemt_desync_frames_bucket_total{bucket="3_10"} 2808
telemt_desync_frames_bucket_total{bucket="gt_10"} 3697
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 25626
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25288
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2172642
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 36331901360 (33.84 GB)
telemt_user_octets_to_client{user="hello"} 771610279901 (718.62 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 146065.1 (40h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1695576
telemt_connections_bad_total 18071
telemt_handshake_timeouts_total 122554
telemt_upstream_connect_attempt_total 46397
telemt_upstream_connect_success_total 44072
telemt_upstream_connect_fail_total 2188
telemt_upstream_connect_attempts_per_request{bucket="1"} 46123
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11845
telemt_me_reconnect_attempts_total 39906
telemt_me_reconnect_success_total 30938
telemt_me_reader_eof_total 33264
telemt_me_idle_close_by_peer_total 33257
telemt_me_route_drop_no_conn_total 605565
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1417880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2821
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 1904
telemt_desync_frames_bucket_total{bucket="1_2"} 753
telemt_desync_frames_bucket_total{bucket="3_10"} 1173
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 31448
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30914
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1422595
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 21998224153 (20.49 GB)
telemt_user_octets_to_client{user="hello"} 549209531482 (511.49 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15500.8 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244612
telemt_connections_bad_total 3869
telemt_handshake_timeouts_total 2338
telemt_upstream_connect_attempt_total 3220
telemt_upstream_connect_success_total 3111
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10360
telemt_me_reconnect_success_total 2284
telemt_me_reader_eof_total 2564
telemt_me_idle_close_by_peer_total 2564
telemt_me_route_drop_no_conn_total 95744
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228518
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2541
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2280
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 228499
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 2532137844 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 74536794168 (69.42 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 96
```