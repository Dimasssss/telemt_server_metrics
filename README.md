# Server Metrics 2026-03-13 01:23:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 69867.8 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2030451
telemt_connections_bad_total 26125
telemt_handshake_timeouts_total 21669
telemt_upstream_connect_attempt_total 13865
telemt_upstream_connect_success_total 13786
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1250
telemt_me_reconnect_attempts_total 19151
telemt_me_reconnect_success_total 10291
telemt_me_reader_eof_total 11127
telemt_me_idle_close_by_peer_total 11126
telemt_me_route_drop_no_conn_total 791757
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1889342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8683
telemt_desync_full_logged_total 2260
telemt_desync_suppressed_total 6423
telemt_desync_frames_bucket_total{bucket="1_2"} 2289
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10712
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10278
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 1888799
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 27667957568 (25.77 GB)
telemt_user_octets_to_client{user="hello"} 660056832956 (614.73 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99488.2 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836662
telemt_connections_bad_total 11774
telemt_handshake_timeouts_total 31971
telemt_upstream_connect_attempt_total 25335
telemt_upstream_connect_success_total 25306
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3446
telemt_me_reconnect_attempts_total 18803
telemt_me_reconnect_success_total 18699
telemt_me_reader_eof_total 19915
telemt_me_idle_close_by_peer_total 19915
telemt_me_route_drop_no_conn_total 269879
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758020
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18883
telemt_me_writer_restored_same_endpoint_total 18690
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 759924
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 12253901760 (11.41 GB)
telemt_user_octets_to_client{user="hello"} 286384396963 (266.72 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99488.1 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1738631
telemt_connections_bad_total 8965
telemt_handshake_timeouts_total 115424
telemt_upstream_connect_attempt_total 23251
telemt_upstream_connect_success_total 23241
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1588
telemt_me_reconnect_attempts_total 19185
telemt_me_reconnect_success_total 17922
telemt_me_reader_eof_total 18977
telemt_me_idle_close_by_peer_total 18976
telemt_me_route_drop_no_conn_total 570013
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1365421
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 18093
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17881
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 1365018
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 20074018536 (18.70 GB)
telemt_user_octets_to_client{user="hello"} 496176920033 (462.10 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99488.3 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090010
telemt_connections_bad_total 13094
telemt_handshake_timeouts_total 72441
telemt_upstream_connect_attempt_total 34631
telemt_upstream_connect_success_total 32364
telemt_upstream_connect_fail_total 2130
telemt_upstream_connect_attempts_per_request{bucket="1"} 34357
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2129
telemt_me_keepalive_timeout_total 11272
telemt_me_reconnect_attempts_total 29384
telemt_me_reconnect_success_total 21543
telemt_me_reader_eof_total 23312
telemt_me_idle_close_by_peer_total 23305
telemt_me_route_drop_no_conn_total 385177
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 934165
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 21922
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21521
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 939353
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 14450755609 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 369262997446 (343.90 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 99488.3 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1200585
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9379
telemt_upstream_connect_attempt_total 30310
telemt_upstream_connect_success_total 29929
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 30310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 1847
telemt_me_reconnect_attempts_total 36010
telemt_me_reconnect_success_total 24964
telemt_me_reader_eof_total 26256
telemt_me_idle_close_by_peer_total 26256
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 450391
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1109055
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4151
telemt_desync_full_logged_total 1471
telemt_desync_suppressed_total 2680
telemt_desync_frames_bucket_total{bucket="1_2"} 1239
telemt_desync_frames_bucket_total{bucket="3_10"} 1378
telemt_desync_frames_bucket_total{bucket="gt_10"} 1534
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25601
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24918
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 1108911
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 13712391720 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 382250086472 (356.00 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 50
```