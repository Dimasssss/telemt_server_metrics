# Server Metrics 2026-03-14 04:01:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 165771.1 (46h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4738200
telemt_connections_bad_total 39890
telemt_handshake_timeouts_total 109408
telemt_upstream_connect_attempt_total 35053
telemt_upstream_connect_success_total 34821
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 6741
telemt_me_reconnect_attempts_total 34360
telemt_me_reconnect_success_total 24218
telemt_me_reader_eof_total 25972
telemt_me_idle_close_by_peer_total 25971
telemt_me_route_drop_no_conn_total 1797360
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4346156
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16821
telemt_desync_full_logged_total 4541
telemt_desync_suppressed_total 12280
telemt_desync_frames_bucket_total{bucket="1_2"} 4200
telemt_desync_frames_bucket_total{bucket="3_10"} 6416
telemt_desync_frames_bucket_total{bucket="gt_10"} 6205
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24879
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24205
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4347732
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 63633897952 (59.26 GB)
telemt_user_octets_to_client{user="hello"} 1371546693477 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65434.9 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720975
telemt_connections_bad_total 52414
telemt_handshake_timeouts_total 13346
telemt_upstream_connect_attempt_total 18129
telemt_upstream_connect_success_total 17870
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 18129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 2097
telemt_me_reconnect_attempts_total 16033
telemt_me_reconnect_success_total 12583
telemt_me_reader_eof_total 13363
telemt_me_idle_close_by_peer_total 13362
telemt_me_route_drop_no_conn_total 241364
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578260
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1716
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 759
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12864
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12575
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 580215
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 6193752325 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 192942076480 (179.69 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 195391.7 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3414476
telemt_connections_bad_total 36465
telemt_handshake_timeouts_total 224300
telemt_upstream_connect_attempt_total 44186
telemt_upstream_connect_success_total 44165
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10439
telemt_me_reconnect_attempts_total 39081
telemt_me_reconnect_success_total 34114
telemt_me_reader_eof_total 36232
telemt_me_idle_close_by_peer_total 36231
telemt_me_route_drop_no_conn_total 1168104
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2844546
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9400
telemt_desync_full_logged_total 3144
telemt_desync_suppressed_total 6256
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3398
telemt_desync_frames_bucket_total{bucket="gt_10"} 4381
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 34589
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34073
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 2843768
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 45573379320 (42.44 GB)
telemt_user_octets_to_client{user="hello"} 1020287490565 (950.22 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 195394.2 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2289468
telemt_connections_bad_total 23018
telemt_handshake_timeouts_total 254670
telemt_upstream_connect_attempt_total 61195
telemt_upstream_connect_success_total 58723
telemt_upstream_connect_fail_total 2335
telemt_upstream_connect_attempts_per_request{bucket="1"} 60921
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2334
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20450
telemt_me_reconnect_attempts_total 51005
telemt_me_reconnect_success_total 41969
telemt_me_reader_eof_total 45009
telemt_me_idle_close_by_peer_total 45002
telemt_me_route_drop_no_conn_total 778394
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819144
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3848
telemt_desync_full_logged_total 1238
telemt_desync_suppressed_total 2610
telemt_desync_frames_bucket_total{bucket="1_2"} 1032
telemt_desync_frames_bucket_total{bucket="3_10"} 1597
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 42609
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41945
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 1825090
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 27701891467 (25.80 GB)
telemt_user_octets_to_client{user="hello"} 672444029698 (626.26 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64827.8 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720450
telemt_connections_bad_total 7961
telemt_handshake_timeouts_total 8716
telemt_upstream_connect_attempt_total 16794
telemt_upstream_connect_success_total 16345
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 16794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_keepalive_timeout_total 1529
telemt_me_reconnect_attempts_total 51881
telemt_me_reconnect_success_total 13123
telemt_me_reader_eof_total 14648
telemt_me_idle_close_by_peer_total 14647
telemt_me_route_drop_no_conn_total 274453
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672019
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14446
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13118
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 671891
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 12238573004 (11.40 GB)
telemt_user_octets_to_client{user="hello"} 217436115084 (202.50 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 57
```