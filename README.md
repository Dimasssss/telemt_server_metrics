# Server Metrics 2026-03-13 02:19:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73231.1 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2075839
telemt_connections_bad_total 27693
telemt_handshake_timeouts_total 22105
telemt_upstream_connect_attempt_total 14522
telemt_upstream_connect_success_total 14439
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1263
telemt_me_reconnect_attempts_total 19631
telemt_me_reconnect_success_total 10770
telemt_me_reader_eof_total 11639
telemt_me_idle_close_by_peer_total 11638
telemt_me_route_drop_no_conn_total 804189
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1921454
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8702
telemt_desync_full_logged_total 2266
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2294
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11198
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10757
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 1920912
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 28058125124 (26.13 GB)
telemt_user_octets_to_client{user="hello"} 669339005688 (623.37 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102851.5 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851022
telemt_connections_bad_total 11794
telemt_handshake_timeouts_total 32319
telemt_upstream_connect_attempt_total 26202
telemt_upstream_connect_success_total 26173
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3451
telemt_me_reconnect_attempts_total 19498
telemt_me_reconnect_success_total 19391
telemt_me_reader_eof_total 20659
telemt_me_idle_close_by_peer_total 20659
telemt_me_route_drop_no_conn_total 273767
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771760
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 19580
telemt_me_writer_restored_same_endpoint_total 19382
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 773663
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 12329307464 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 292028350347 (271.97 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102851.3 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1765506
telemt_connections_bad_total 9165
telemt_handshake_timeouts_total 118469
telemt_upstream_connect_attempt_total 23993
telemt_upstream_connect_success_total 23983
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1598
telemt_me_reconnect_attempts_total 19754
telemt_me_reconnect_success_total 18491
telemt_me_reader_eof_total 19584
telemt_me_idle_close_by_peer_total 19583
telemt_me_route_drop_no_conn_total 576467
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1388683
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5005
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 3470
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1812
telemt_desync_frames_bucket_total{bucket="gt_10"} 2395
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 18665
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18450
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1388278
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 20176432308 (18.79 GB)
telemt_user_octets_to_client{user="hello"} 501309859397 (466.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102851.4 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1103653
telemt_connections_bad_total 13134
telemt_handshake_timeouts_total 73145
telemt_upstream_connect_attempt_total 36046
telemt_upstream_connect_success_total 33773
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 35772
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11281
telemt_me_reconnect_attempts_total 31691
telemt_me_reconnect_success_total 22768
telemt_me_reader_eof_total 24610
telemt_me_idle_close_by_peer_total 24603
telemt_me_route_drop_no_conn_total 391328
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23198
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22745
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 951436
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 14519600029 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 373247871982 (347.61 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 102851.4 (28h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219031
telemt_connections_bad_total 12607
telemt_handshake_timeouts_total 9544
telemt_upstream_connect_attempt_total 32483
telemt_upstream_connect_success_total 32082
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 32483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 1884
telemt_me_reconnect_attempts_total 40671
telemt_me_reconnect_success_total 26942
telemt_me_reader_eof_total 28332
telemt_me_idle_close_by_peer_total 28332
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 456071
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1126917
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4198
telemt_desync_full_logged_total 1490
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1258
telemt_desync_frames_bucket_total{bucket="3_10"} 1387
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27679
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 26893
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 1126772
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 13805229968 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 388985757808 (362.27 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 41
```