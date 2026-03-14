# Server Metrics 2026-03-14 04:06:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 166077.8 (46h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4742992
telemt_connections_bad_total 39894
telemt_handshake_timeouts_total 109503
telemt_upstream_connect_attempt_total 35104
telemt_upstream_connect_success_total 34872
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 6743
telemt_me_reconnect_attempts_total 34411
telemt_me_reconnect_success_total 24269
telemt_me_reader_eof_total 26025
telemt_me_idle_close_by_peer_total 26024
telemt_me_route_drop_no_conn_total 1799171
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4350656
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16823
telemt_desync_full_logged_total 4543
telemt_desync_suppressed_total 12280
telemt_desync_frames_bucket_total{bucket="1_2"} 4200
telemt_desync_frames_bucket_total{bucket="3_10"} 6416
telemt_desync_frames_bucket_total{bucket="gt_10"} 6207
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24930
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24256
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4352230
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 63698317444 (59.32 GB)
telemt_user_octets_to_client{user="hello"} 1372669687953 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65741.5 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723178
telemt_connections_bad_total 52498
telemt_handshake_timeouts_total 13371
telemt_upstream_connect_attempt_total 18174
telemt_upstream_connect_success_total 17915
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 18174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 2097
telemt_me_reconnect_attempts_total 16064
telemt_me_reconnect_success_total 12613
telemt_me_reader_eof_total 13395
telemt_me_idle_close_by_peer_total 13394
telemt_me_route_drop_no_conn_total 242143
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579955
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1718
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12896
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12605
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 581910
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 6224206745 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 193604707180 (180.31 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 195698.2 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3417267
telemt_connections_bad_total 36470
telemt_handshake_timeouts_total 224530
telemt_upstream_connect_attempt_total 44266
telemt_upstream_connect_success_total 44245
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10441
telemt_me_reconnect_attempts_total 39160
telemt_me_reconnect_success_total 34192
telemt_me_reader_eof_total 36320
telemt_me_idle_close_by_peer_total 36319
telemt_me_route_drop_no_conn_total 1169015
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2847028
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9403
telemt_desync_full_logged_total 3146
telemt_desync_suppressed_total 6257
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3400
telemt_desync_frames_bucket_total{bucket="gt_10"} 4382
telemt_pool_swap_total 185
telemt_me_writer_removed_unexpected_total 34668
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34151
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 2846246
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 45586293708 (42.46 GB)
telemt_user_octets_to_client{user="hello"} 1020680960937 (950.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 195701.0 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2291775
telemt_connections_bad_total 23024
telemt_handshake_timeouts_total 255318
telemt_upstream_connect_attempt_total 61303
telemt_upstream_connect_success_total 58831
telemt_upstream_connect_fail_total 2335
telemt_upstream_connect_attempts_per_request{bucket="1"} 61029
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2334
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20452
telemt_me_reconnect_attempts_total 51102
telemt_me_reconnect_success_total 42066
telemt_me_reader_eof_total 45115
telemt_me_idle_close_by_peer_total 45108
telemt_me_route_drop_no_conn_total 779025
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1820634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3850
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 2610
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 1598
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 42706
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42042
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 1826580
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 27713255711 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 672711291406 (626.51 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65134.4 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722364
telemt_connections_bad_total 7965
telemt_handshake_timeouts_total 8718
telemt_upstream_connect_attempt_total 16918
telemt_upstream_connect_success_total 16466
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_timeout_total 1531
telemt_me_reconnect_attempts_total 51960
telemt_me_reconnect_success_total 13201
telemt_me_reader_eof_total 14739
telemt_me_idle_close_by_peer_total 14738
telemt_me_route_drop_no_conn_total 275738
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673843
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 535
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14525
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13196
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1324
telemt_user_connections_total{user="hello"} 673715
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 12252372460 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 218009223132 (203.04 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 58
```