# Server Metrics 2026-03-13 10:36:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 103068.1 (28h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2992120
telemt_connections_bad_total 36447
telemt_handshake_timeouts_total 54104
telemt_upstream_connect_attempt_total 20330
telemt_upstream_connect_success_total 20219
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 25159
telemt_me_reconnect_success_total 15088
telemt_me_reader_eof_total 16239
telemt_me_idle_close_by_peer_total 16238
telemt_me_route_drop_no_conn_total 1104145
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2730022
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11910
telemt_desync_full_logged_total 3068
telemt_desync_suppressed_total 8842
telemt_desync_frames_bucket_total{bucket="1_2"} 3045
telemt_desync_frames_bucket_total{bucket="3_10"} 4471
telemt_desync_frames_bucket_total{bucket="gt_10"} 4394
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15610
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15075
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2729959
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 37507556536 (34.93 GB)
telemt_user_octets_to_client{user="hello"} 884791715732 (824.03 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2731.8 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27351
telemt_connections_bad_total 2364
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 612
telemt_upstream_connect_success_total 544
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 447
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 9340
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23830
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 375
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 23831
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 317845928 (303.12 MB)
telemt_user_octets_to_client{user="hello"} 4688720280 (4.37 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 132688.6 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315299
telemt_connections_bad_total 25096
telemt_handshake_timeouts_total 157348
telemt_upstream_connect_attempt_total 30283
telemt_upstream_connect_success_total 30273
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 24605
telemt_me_reconnect_success_total 23315
telemt_me_reader_eof_total 24702
telemt_me_idle_close_by_peer_total 24701
telemt_me_route_drop_no_conn_total 759429
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1859947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6113
telemt_desync_full_logged_total 1953
telemt_desync_suppressed_total 4160
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 2232
telemt_desync_frames_bucket_total{bucket="gt_10"} 2887
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23549
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23274
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1859386
telemt_user_connections_current{user="hello"} 1011
telemt_user_octets_from_client{user="hello"} 31963399856 (29.77 GB)
telemt_user_octets_to_client{user="hello"} 670624126009 (624.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 132688.9 (36h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1462732
telemt_connections_bad_total 14239
telemt_handshake_timeouts_total 91324
telemt_upstream_connect_attempt_total 43284
telemt_upstream_connect_success_total 40974
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 43010
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11507
telemt_me_reconnect_attempts_total 37462
telemt_me_reconnect_success_total 28511
telemt_me_reader_eof_total 30694
telemt_me_idle_close_by_peer_total 30687
telemt_me_route_drop_no_conn_total 518522
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1223862
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2300
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 784
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 28997
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28487
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1228598
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 18568946205 (17.29 GB)
telemt_user_octets_to_client{user="hello"} 487013987398 (453.57 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2124.2 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20925
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 90
telemt_upstream_connect_attempt_total 626
telemt_upstream_connect_success_total 612
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 449
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 6570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19877
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_me_writer_removed_unexpected_total 435
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 446
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 19871
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 219200912 (209.05 MB)
telemt_user_octets_to_client{user="hello"} 8375257776 (7.80 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 132
```