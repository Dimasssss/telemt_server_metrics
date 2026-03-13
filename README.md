# Server Metrics 2026-03-13 12:06:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108495.0 (30h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3215040
telemt_connections_bad_total 36547
telemt_handshake_timeouts_total 56086
telemt_upstream_connect_attempt_total 21517
telemt_upstream_connect_success_total 21400
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 21517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 2066
telemt_me_reconnect_attempts_total 26074
telemt_me_reconnect_success_total 15993
telemt_me_reader_eof_total 17195
telemt_me_idle_close_by_peer_total 17194
telemt_me_route_drop_no_conn_total 1191774
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2943927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12525
telemt_desync_full_logged_total 3248
telemt_desync_suppressed_total 9277
telemt_desync_frames_bucket_total{bucket="1_2"} 3205
telemt_desync_frames_bucket_total{bucket="3_10"} 4703
telemt_desync_frames_bucket_total{bucket="gt_10"} 4617
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16528
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15980
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 2943862
telemt_user_connections_current{user="hello"} 1782
telemt_user_octets_from_client{user="hello"} 40741665624 (37.94 GB)
telemt_user_octets_to_client{user="hello"} 950631446844 (885.34 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8158.9 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108621
telemt_connections_bad_total 6487
telemt_handshake_timeouts_total 2551
telemt_upstream_connect_attempt_total 2096
telemt_upstream_connect_success_total 2025
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 2096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 2787
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1627
telemt_me_idle_close_by_peer_total 1627
telemt_me_route_drop_no_conn_total 38387
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96915
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1608
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1554
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 96938
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 932987656 (889.77 MB)
telemt_user_octets_to_client{user="hello"} 24777642172 (23.08 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 138115.4 (38h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2450492
telemt_connections_bad_total 25649
telemt_handshake_timeouts_total 162905
telemt_upstream_connect_attempt_total 31534
telemt_upstream_connect_success_total 31523
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3109
telemt_me_reconnect_attempts_total 26838
telemt_me_reconnect_success_total 24292
telemt_me_reader_eof_total 25752
telemt_me_idle_close_by_peer_total 25751
telemt_me_route_drop_no_conn_total 815445
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1984920
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6603
telemt_desync_full_logged_total 2134
telemt_desync_suppressed_total 4469
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 2400
telemt_desync_frames_bucket_total{bucket="gt_10"} 3158
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 24573
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24251
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 1984332
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 33673991788 (31.36 GB)
telemt_user_octets_to_client{user="hello"} 709397610933 (660.68 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 138115.7 (38h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1558988
telemt_connections_bad_total 17833
telemt_handshake_timeouts_total 105526
telemt_upstream_connect_attempt_total 44799
telemt_upstream_connect_success_total 42482
telemt_upstream_connect_fail_total 2180
telemt_upstream_connect_attempts_per_request{bucket="1"} 44525
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11782
telemt_me_reconnect_attempts_total 38703
telemt_me_reconnect_success_total 29739
telemt_me_reader_eof_total 31984
telemt_me_idle_close_by_peer_total 31977
telemt_me_route_drop_no_conn_total 553651
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1300988
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2468
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 1646
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 947
telemt_desync_frames_bucket_total{bucket="gt_10"} 849
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 30236
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29715
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 1305711
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 19480602481 (18.14 GB)
telemt_user_octets_to_client{user="hello"} 510187852178 (475.15 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 7552.0 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108018
telemt_connections_bad_total 569
telemt_handshake_timeouts_total 734
telemt_upstream_connect_attempt_total 1554
telemt_upstream_connect_success_total 1492
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 1554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 9129
telemt_me_reconnect_success_total 1059
telemt_me_reader_eof_total 1281
telemt_me_idle_close_by_peer_total 1281
telemt_me_route_drop_no_conn_total 42342
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103191
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 379
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_me_writer_removed_unexpected_total 1303
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 103187
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 1205450108 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33601897392 (31.29 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 108
```