# Server Metrics 2026-03-14 00:21:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 152582.1 (42h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4598594
telemt_connections_bad_total 38395
telemt_handshake_timeouts_total 107849
telemt_upstream_connect_attempt_total 32106
telemt_upstream_connect_success_total 31889
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 32106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6660
telemt_me_reconnect_attempts_total 32076
telemt_me_reconnect_success_total 21944
telemt_me_reader_eof_total 23538
telemt_me_idle_close_by_peer_total 23537
telemt_me_route_drop_no_conn_total 1740241
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4215286
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16623
telemt_desync_full_logged_total 4479
telemt_desync_suppressed_total 12144
telemt_desync_frames_bucket_total{bucket="1_2"} 4138
telemt_desync_frames_bucket_total{bucket="3_10"} 6360
telemt_desync_frames_bucket_total{bucket="gt_10"} 6125
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 22576
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21931
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 4217163
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 62230231180 (57.96 GB)
telemt_user_octets_to_client{user="hello"} 1333278558005 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52245.8 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640731
telemt_connections_bad_total 47753
telemt_handshake_timeouts_total 12809
telemt_upstream_connect_attempt_total 14693
telemt_upstream_connect_success_total 14451
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 14693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 1938
telemt_me_reconnect_attempts_total 13250
telemt_me_reconnect_success_total 9809
telemt_me_reader_eof_total 10403
telemt_me_idle_close_by_peer_total 10402
telemt_me_route_drop_no_conn_total 225012
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534245
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10056
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9801
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 536196
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 5846792793 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 174328623092 (162.36 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 182202.7 (50h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3331924
telemt_connections_bad_total 32580
telemt_handshake_timeouts_total 222252
telemt_upstream_connect_attempt_total 40729
telemt_upstream_connect_success_total 40708
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10351
telemt_me_reconnect_attempts_total 36269
telemt_me_reconnect_success_total 31313
telemt_me_reader_eof_total 33243
telemt_me_idle_close_by_peer_total 33242
telemt_me_route_drop_no_conn_total 1143566
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2769791
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9103
telemt_desync_full_logged_total 3059
telemt_desync_suppressed_total 6044
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 3300
telemt_desync_frames_bucket_total{bucket="gt_10"} 4270
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 31767
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31272
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2769034
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 44853566208 (41.77 GB)
telemt_user_octets_to_client{user="hello"} 981975491869 (914.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 182205.2 (50h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2205420
telemt_connections_bad_total 22863
telemt_handshake_timeouts_total 236157
telemt_upstream_connect_attempt_total 56712
telemt_upstream_connect_success_total 54256
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 56438
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2318
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20376
telemt_me_reconnect_attempts_total 47181
telemt_me_reconnect_success_total 38156
telemt_me_reader_eof_total 40935
telemt_me_idle_close_by_peer_total 40928
telemt_me_route_drop_no_conn_total 764171
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1777896
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 38767
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38132
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 1783797
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 27379940423 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 662890348034 (617.36 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51638.7 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671229
telemt_connections_bad_total 7868
telemt_handshake_timeouts_total 8578
telemt_upstream_connect_attempt_total 12470
telemt_upstream_connect_success_total 12109
telemt_upstream_connect_fail_total 361
telemt_upstream_connect_attempts_per_request{bucket="1"} 12470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 361
telemt_me_keepalive_timeout_total 1459
telemt_me_reconnect_attempts_total 41662
telemt_me_reconnect_success_total 9504
telemt_me_reader_eof_total 10706
telemt_me_idle_close_by_peer_total 10705
telemt_me_route_drop_no_conn_total 253300
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624025
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 10595
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9499
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1091
telemt_user_connections_total{user="hello"} 623924
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 10188363972 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 203523241740 (189.55 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 26
```