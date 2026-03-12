# Server Metrics 2026-03-12 21:59:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57627.5 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1896534
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20811
telemt_upstream_connect_attempt_total 11306
telemt_upstream_connect_success_total 11241
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 11306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 595
telemt_me_reconnect_attempts_total 17206
telemt_me_reconnect_success_total 8352
telemt_me_reader_eof_total 9014
telemt_me_idle_close_by_peer_total 9013
telemt_me_route_drop_no_conn_total 741696
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1765066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8471
telemt_desync_full_logged_total 2202
telemt_desync_suppressed_total 6269
telemt_desync_frames_bucket_total{bucket="1_2"} 2229
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 3190
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8748
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8339
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1764547
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 26811174816 (24.97 GB)
telemt_user_octets_to_client{user="hello"} 624323281712 (581.45 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87248.0 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788597
telemt_connections_bad_total 11690
telemt_handshake_timeouts_total 31159
telemt_upstream_connect_attempt_total 22011
telemt_upstream_connect_success_total 21982
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3405
telemt_me_reconnect_attempts_total 16082
telemt_me_reconnect_success_total 15989
telemt_me_reader_eof_total 17005
telemt_me_idle_close_by_peer_total 17005
telemt_me_route_drop_no_conn_total 255522
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711962
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2996
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16150
telemt_me_writer_restored_same_endpoint_total 15980
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 713842
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 12021268476 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 272837647375 (254.10 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87247.8 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1634876
telemt_connections_bad_total 7740
telemt_handshake_timeouts_total 113116
telemt_upstream_connect_attempt_total 20361
telemt_upstream_connect_success_total 20355
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1216
telemt_me_reconnect_attempts_total 16901
telemt_me_reconnect_success_total 15653
telemt_me_reader_eof_total 16534
telemt_me_idle_close_by_peer_total 16533
telemt_me_route_drop_no_conn_total 538939
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1269118
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4956
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 3435
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1791
telemt_desync_frames_bucket_total{bucket="gt_10"} 2375
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15801
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15612
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 1268724
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 19631786556 (18.28 GB)
telemt_user_octets_to_client{user="hello"} 470725369537 (438.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87248.2 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008302
telemt_connections_bad_total 12997
telemt_handshake_timeouts_total 71165
telemt_upstream_connect_attempt_total 22252
telemt_upstream_connect_success_total 22161
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 25550
telemt_me_reconnect_success_total 17821
telemt_me_reader_eof_total 19031
telemt_me_idle_close_by_peer_total 19031
telemt_me_route_drop_no_conn_total 360978
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18203
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17800
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 876914
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 14073939624 (13.11 GB)
telemt_user_octets_to_client{user="hello"} 352048600760 (327.87 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87248.2 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127420
telemt_connections_bad_total 12533
telemt_handshake_timeouts_total 9101
telemt_upstream_connect_attempt_total 26734
telemt_upstream_connect_success_total 26406
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 33091
telemt_me_reconnect_success_total 22053
telemt_me_reader_eof_total 23185
telemt_me_idle_close_by_peer_total 23185
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 422421
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037302
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3897
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2541
telemt_desync_frames_bucket_total{bucket="1_2"} 1146
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1467
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22651
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22009
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 1037167
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 12786148468 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 366858621116 (341.66 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 112
```