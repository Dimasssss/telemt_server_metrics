# Server Metrics 2026-03-13 23:51:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 150741.6 (41h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4582357
telemt_connections_bad_total 38389
telemt_handshake_timeouts_total 107780
telemt_upstream_connect_attempt_total 31699
telemt_upstream_connect_success_total 31482
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6655
telemt_me_reconnect_attempts_total 31759
telemt_me_reconnect_success_total 21628
telemt_me_reader_eof_total 23197
telemt_me_idle_close_by_peer_total 23196
telemt_me_route_drop_no_conn_total 1732382
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4199538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16610
telemt_desync_full_logged_total 4473
telemt_desync_suppressed_total 12137
telemt_desync_frames_bucket_total{bucket="1_2"} 4134
telemt_desync_frames_bucket_total{bucket="3_10"} 6355
telemt_desync_frames_bucket_total{bucket="gt_10"} 6121
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 22256
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21615
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 4201460
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 61829178744 (57.58 GB)
telemt_user_octets_to_client{user="hello"} 1327449242281 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50405.3 (14h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622681
telemt_connections_bad_total 46250
telemt_handshake_timeouts_total 12733
telemt_upstream_connect_attempt_total 14194
telemt_upstream_connect_success_total 13955
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 14194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 1927
telemt_me_reconnect_attempts_total 12853
telemt_me_reconnect_success_total 9414
telemt_me_reader_eof_total 9979
telemt_me_idle_close_by_peer_total 9978
telemt_me_route_drop_no_conn_total 222395
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529129
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
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9657
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9406
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 531080
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 5823251197 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 173533089844 (161.62 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 180362.0 (50h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3322150
telemt_connections_bad_total 32323
telemt_handshake_timeouts_total 222180
telemt_upstream_connect_attempt_total 40180
telemt_upstream_connect_success_total 40159
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10342
telemt_me_reconnect_attempts_total 35808
telemt_me_reconnect_success_total 30852
telemt_me_reader_eof_total 32750
telemt_me_idle_close_by_peer_total 32749
telemt_me_route_drop_no_conn_total 1140071
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2760535
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9045
telemt_desync_full_logged_total 3043
telemt_desync_suppressed_total 6002
telemt_desync_frames_bucket_total{bucket="1_2"} 1523
telemt_desync_frames_bucket_total{bucket="3_10"} 3278
telemt_desync_frames_bucket_total{bucket="gt_10"} 4244
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 31302
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30811
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 2759783
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 44780671996 (41.71 GB)
telemt_user_octets_to_client{user="hello"} 977270501749 (910.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 180364.5 (50h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2191710
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 232987
telemt_upstream_connect_attempt_total 56166
telemt_upstream_connect_success_total 53713
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 55892
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20352
telemt_me_reconnect_attempts_total 46724
telemt_me_reconnect_success_total 37700
telemt_me_reader_eof_total 40444
telemt_me_idle_close_by_peer_total 40437
telemt_me_route_drop_no_conn_total 762266
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1772415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3796
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 38309
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37676
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 1778310
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 27357886491 (25.48 GB)
telemt_user_octets_to_client{user="hello"} 661712597814 (616.27 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49798.0 (13h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662676
telemt_connections_bad_total 7858
telemt_handshake_timeouts_total 8013
telemt_upstream_connect_attempt_total 11933
telemt_upstream_connect_success_total 11574
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 11933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 41213
telemt_me_reconnect_success_total 9058
telemt_me_reader_eof_total 10220
telemt_me_idle_close_by_peer_total 10219
telemt_me_route_drop_no_conn_total 250761
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616889
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1611
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 10146
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9053
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1088
telemt_user_connections_total{user="hello"} 616788
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 9915333404 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 201105444744 (187.29 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 21
```