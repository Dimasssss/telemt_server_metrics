# Server Metrics 2026-03-13 13:48:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 114609.4 (31h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3476432
telemt_connections_bad_total 37389
telemt_handshake_timeouts_total 59414
telemt_upstream_connect_attempt_total 22494
telemt_upstream_connect_success_total 22370
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2125
telemt_me_reconnect_attempts_total 26742
telemt_me_reconnect_success_total 16658
telemt_me_reader_eof_total 17910
telemt_me_idle_close_by_peer_total 17909
telemt_me_route_drop_no_conn_total 1289752
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3190701
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13264
telemt_desync_full_logged_total 3463
telemt_desync_suppressed_total 9801
telemt_desync_frames_bucket_total{bucket="1_2"} 3377
telemt_desync_frames_bucket_total{bucket="3_10"} 5023
telemt_desync_frames_bucket_total{bucket="gt_10"} 4864
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17205
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16645
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 3190572
telemt_user_connections_current{user="hello"} 1834
telemt_user_octets_from_client{user="hello"} 44067947940 (41.04 GB)
telemt_user_octets_to_client{user="hello"} 1015558990712 (945.81 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 14273.3 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198906
telemt_connections_bad_total 11323
telemt_handshake_timeouts_total 5122
telemt_upstream_connect_attempt_total 3403
telemt_upstream_connect_success_total 3327
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 3809
telemt_me_reconnect_success_total 2578
telemt_me_reader_eof_total 2707
telemt_me_idle_close_by_peer_total 2707
telemt_me_route_drop_no_conn_total 72402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177297
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2638
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2571
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 177321
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1755976812 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 50041540980 (46.60 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 144229.9 (40h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2610496
telemt_connections_bad_total 26847
telemt_handshake_timeouts_total 174985
telemt_upstream_connect_attempt_total 32629
telemt_upstream_connect_success_total 32619
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3205
telemt_me_reconnect_attempts_total 27632
telemt_me_reconnect_success_total 25086
telemt_me_reader_eof_total 26599
telemt_me_idle_close_by_peer_total 26598
telemt_me_route_drop_no_conn_total 876492
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2128571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7398
telemt_desync_full_logged_total 2413
telemt_desync_suppressed_total 4985
telemt_desync_frames_bucket_total{bucket="1_2"} 1165
telemt_desync_frames_bucket_total{bucket="3_10"} 2691
telemt_desync_frames_bucket_total{bucket="gt_10"} 3542
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 25378
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25045
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 2127992
telemt_user_connections_current{user="hello"} 1132
telemt_user_octets_from_client{user="hello"} 35540928012 (33.10 GB)
telemt_user_octets_to_client{user="hello"} 758752768893 (706.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 144230.4 (40h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1663937
telemt_connections_bad_total 18044
telemt_handshake_timeouts_total 118069
telemt_upstream_connect_attempt_total 46042
telemt_upstream_connect_success_total 43720
telemt_upstream_connect_fail_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 45768
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11834
telemt_me_reconnect_attempts_total 39640
telemt_me_reconnect_success_total 30674
telemt_me_reader_eof_total 32983
telemt_me_idle_close_by_peer_total 32976
telemt_me_route_drop_no_conn_total 593728
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1391807
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2805
telemt_desync_full_logged_total 907
telemt_desync_suppressed_total 1898
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1168
telemt_desync_frames_bucket_total{bucket="gt_10"} 888
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 31182
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30650
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 1396531
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 21545872553 (20.07 GB)
telemt_user_octets_to_client{user="hello"} 541650872526 (504.45 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13665.9 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214707
telemt_connections_bad_total 3857
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 2796
telemt_upstream_connect_success_total 2697
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 2796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 10033
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2223
telemt_me_route_drop_no_conn_total 84035
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200715
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2211
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 200698
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 2078441620 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 60225542692 (56.09 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 123
```