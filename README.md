# Server Metrics 2026-03-13 00:47:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67726.9 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2008726
telemt_connections_bad_total 26113
telemt_handshake_timeouts_total 21465
telemt_upstream_connect_attempt_total 13472
telemt_upstream_connect_success_total 13395
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1246
telemt_me_reconnect_attempts_total 18846
telemt_me_reconnect_success_total 9987
telemt_me_reader_eof_total 10806
telemt_me_idle_close_by_peer_total 10805
telemt_me_route_drop_no_conn_total 784358
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1868632
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8668
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 3256
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10404
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9974
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 1868090
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 27533475200 (25.64 GB)
telemt_user_octets_to_client{user="hello"} 656199892024 (611.13 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97347.5 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827527
telemt_connections_bad_total 11755
telemt_handshake_timeouts_total 31859
telemt_upstream_connect_attempt_total 24776
telemt_upstream_connect_success_total 24747
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3438
telemt_me_reconnect_attempts_total 18330
telemt_me_reconnect_success_total 18229
telemt_me_reader_eof_total 19406
telemt_me_idle_close_by_peer_total 19406
telemt_me_route_drop_no_conn_total 267824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3054
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 1235
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18406
telemt_me_writer_restored_same_endpoint_total 18220
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 751332
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 12207153156 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 285497769795 (265.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97347.3 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1722206
telemt_connections_bad_total 8785
telemt_handshake_timeouts_total 113750
telemt_upstream_connect_attempt_total 22629
telemt_upstream_connect_success_total 22619
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1578
telemt_me_reconnect_attempts_total 18651
telemt_me_reconnect_success_total 17389
telemt_me_reader_eof_total 18418
telemt_me_idle_close_by_peer_total 18417
telemt_me_route_drop_no_conn_total 565967
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352057
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4989
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 3459
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1804
telemt_desync_frames_bucket_total{bucket="gt_10"} 2387
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17556
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17348
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 1351657
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 19972098688 (18.60 GB)
telemt_user_octets_to_client{user="hello"} 491810944101 (458.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97347.5 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079875
telemt_connections_bad_total 13050
telemt_handshake_timeouts_total 72218
telemt_upstream_connect_attempt_total 33975
telemt_upstream_connect_success_total 31711
telemt_upstream_connect_fail_total 2127
telemt_upstream_connect_attempts_per_request{bucket="1"} 33701
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2126
telemt_me_keepalive_timeout_total 11267
telemt_me_reconnect_attempts_total 28817
telemt_me_reconnect_success_total 20977
telemt_me_reader_eof_total 22708
telemt_me_idle_close_by_peer_total 22701
telemt_me_route_drop_no_conn_total 381022
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924809
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
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 21352
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20955
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 930000
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 14411952469 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 367453154842 (342.22 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97347.6 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188489
telemt_connections_bad_total 12579
telemt_handshake_timeouts_total 9341
telemt_upstream_connect_attempt_total 29423
telemt_upstream_connect_success_total 29050
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 29423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 1831
telemt_me_reconnect_attempts_total 35218
telemt_me_reconnect_success_total 24173
telemt_me_reader_eof_total 25453
telemt_me_idle_close_by_peer_total 25453
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 445750
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097218
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4117
telemt_desync_full_logged_total 1451
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 1216
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1529
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24798
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24127
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 1097074
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 13667026248 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 381331344180 (355.14 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 39
```