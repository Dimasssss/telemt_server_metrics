# Server Metrics 2026-03-11 20:28:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 108079.1 (30h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2743297
telemt_connections_bad_total 55977
telemt_handshake_timeouts_total 62169
telemt_upstream_connect_attempt_total 22815
telemt_upstream_connect_success_total 22803
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5409
telemt_me_reconnect_attempts_total 35225
telemt_me_reconnect_success_total 17331
telemt_me_reader_eof_total 18722
telemt_me_idle_close_by_peer_total 18722
telemt_me_route_drop_no_conn_total 1032641
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2496441
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12647
telemt_desync_full_logged_total 3510
telemt_desync_suppressed_total 9137
telemt_desync_frames_bucket_total{bucket="1_2"} 3118
telemt_desync_frames_bucket_total{bucket="3_10"} 4861
telemt_desync_frames_bucket_total{bucket="gt_10"} 4668
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18091
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17325
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 760
telemt_user_connections_total{user="hello"} 2494791
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 37801274448 (35.21 GB)
telemt_user_octets_to_client{user="hello"} 716499777660 (667.29 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108135.8 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008600
telemt_connections_bad_total 16574
telemt_handshake_timeouts_total 90387
telemt_upstream_connect_attempt_total 33100
telemt_upstream_connect_success_total 30127
telemt_upstream_connect_fail_total 2973
telemt_upstream_connect_attempts_per_request{bucket="1"} 33100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2973
telemt_me_keepalive_timeout_total 2887
telemt_me_reconnect_attempts_total 23842
telemt_me_reconnect_success_total 21718
telemt_me_reader_eof_total 23004
telemt_me_idle_close_by_peer_total 23001
telemt_me_route_drop_no_conn_total 381640
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842391
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3340
telemt_desync_full_logged_total 1085
telemt_desync_suppressed_total 2255
telemt_desync_frames_bucket_total{bucket="1_2"} 1075
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 22037
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21695
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 844832
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 10225731490 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 248165668360 (231.12 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108135.7 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1752075
telemt_connections_bad_total 11106
telemt_handshake_timeouts_total 135201
telemt_upstream_connect_attempt_total 27451
telemt_upstream_connect_success_total 27103
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 27451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 2028
telemt_me_reconnect_attempts_total 57366
telemt_me_reconnect_success_total 20542
telemt_me_reader_eof_total 22552
telemt_me_idle_close_by_peer_total 22552
telemt_me_route_drop_no_conn_total 637938
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1540472
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4169
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1615
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21975
telemt_me_refill_failed_total 1145
telemt_me_writer_restored_same_endpoint_total 20530
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1433
telemt_user_connections_total{user="hello"} 1540102
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 19810005041 (18.45 GB)
telemt_user_octets_to_client{user="hello"} 472180250305 (439.75 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108136.2 (30h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252191
telemt_connections_bad_total 78228
telemt_handshake_timeouts_total 111396
telemt_upstream_connect_attempt_total 29069
telemt_upstream_connect_success_total 29069
telemt_upstream_connect_attempts_per_request{bucket="1"} 29069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1525
telemt_me_reconnect_attempts_total 28255
telemt_me_reconnect_success_total 23635
telemt_me_reader_eof_total 25102
telemt_me_idle_close_by_peer_total 25101
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 420479
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026888
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2191
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1367
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 24031
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23602
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1026014
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 12171974964 (11.34 GB)
telemt_user_octets_to_client{user="hello"} 312492513276 (291.03 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12812.1 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190654
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2194
telemt_upstream_connect_attempt_total 3676
telemt_upstream_connect_success_total 3675
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 2984
telemt_me_reconnect_success_total 2954
telemt_me_reader_eof_total 3050
telemt_me_idle_close_by_peer_total 3050
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 64471
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167544
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 418
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2990
telemt_me_writer_restored_same_endpoint_total 2929
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 167508
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 9502863768 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 56773224584 (52.87 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 53
```