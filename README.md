# Server Metrics 2026-03-12 16:06:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36484.4 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1318521
telemt_connections_bad_total 20237
telemt_handshake_timeouts_total 12772
telemt_upstream_connect_attempt_total 7281
telemt_upstream_connect_success_total 7242
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 454
telemt_me_reconnect_attempts_total 9291
telemt_me_reconnect_success_total 5381
telemt_me_reader_eof_total 5731
telemt_me_idle_close_by_peer_total 5730
telemt_me_route_drop_no_conn_total 471563
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1235613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6399
telemt_desync_full_logged_total 1600
telemt_desync_suppressed_total 4799
telemt_desync_frames_bucket_total{bucket="1_2"} 1650
telemt_desync_frames_bucket_total{bucket="3_10"} 2302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2447
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5571
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5368
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1235295
telemt_user_connections_current{user="hello"} 1608
telemt_user_octets_from_client{user="hello"} 19147789424 (17.83 GB)
telemt_user_octets_to_client{user="hello"} 356326204656 (331.85 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66105.0 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585354
telemt_connections_bad_total 7743
telemt_handshake_timeouts_total 27687
telemt_upstream_connect_attempt_total 15832
telemt_upstream_connect_success_total 15825
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1255
telemt_me_reconnect_attempts_total 12405
telemt_me_reconnect_success_total 12335
telemt_me_reader_eof_total 13113
telemt_me_idle_close_by_peer_total 13113
telemt_me_route_drop_no_conn_total 173946
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2037
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12456
telemt_me_writer_restored_same_endpoint_total 12326
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 524086
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 8096629875 (7.54 GB)
telemt_user_octets_to_client{user="hello"} 185181130762 (172.46 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66104.9 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1237230
telemt_connections_bad_total 6267
telemt_handshake_timeouts_total 87103
telemt_upstream_connect_attempt_total 15918
telemt_upstream_connect_success_total 15913
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1062
telemt_me_reconnect_attempts_total 13470
telemt_me_reconnect_success_total 12242
telemt_me_reader_eof_total 12910
telemt_me_idle_close_by_peer_total 12910
telemt_me_route_drop_no_conn_total 337509
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917789
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3891
telemt_desync_full_logged_total 1191
telemt_desync_suppressed_total 2700
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 1400
telemt_desync_frames_bucket_total{bucket="gt_10"} 1894
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12331
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12201
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 917964
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 12063067588 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 287143831097 (267.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66105.5 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736673
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 59115
telemt_upstream_connect_attempt_total 17390
telemt_upstream_connect_success_total 17321
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1440
telemt_me_reconnect_attempts_total 19251
telemt_me_reconnect_success_total 14007
telemt_me_reader_eof_total 14928
telemt_me_idle_close_by_peer_total 14928
telemt_me_route_drop_no_conn_total 251610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634892
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14277
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13986
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 634359
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 7984865212 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 249647417340 (232.50 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66105.2 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 834469
telemt_connections_bad_total 9516
telemt_handshake_timeouts_total 6848
telemt_upstream_connect_attempt_total 20814
telemt_upstream_connect_success_total 20560
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 20814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 1194
telemt_me_reconnect_attempts_total 24485
telemt_me_reconnect_success_total 17242
telemt_me_reader_eof_total 18061
telemt_me_idle_close_by_peer_total 18061
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 293130
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767855
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2978
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 1964
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17651
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17204
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 767751
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 9351554900 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 215860599380 (201.04 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 134
```