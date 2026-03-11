# Server Metrics 2026-03-11 21:04:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110222.6 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2790616
telemt_connections_bad_total 61927
telemt_handshake_timeouts_total 62547
telemt_upstream_connect_attempt_total 23539
telemt_upstream_connect_success_total 23527
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5438
telemt_me_reconnect_attempts_total 35834
telemt_me_reconnect_success_total 17938
telemt_me_reader_eof_total 19357
telemt_me_idle_close_by_peer_total 19357
telemt_me_route_drop_no_conn_total 1047361
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2533050
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12706
telemt_desync_full_logged_total 3531
telemt_desync_suppressed_total 9175
telemt_desync_frames_bucket_total{bucket="1_2"} 3134
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4691
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 18704
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17932
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 766
telemt_user_connections_total{user="hello"} 2531383
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 38522105368 (35.88 GB)
telemt_user_octets_to_client{user="hello"} 729970229796 (679.84 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110279.3 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019371
telemt_connections_bad_total 17055
telemt_handshake_timeouts_total 90442
telemt_upstream_connect_attempt_total 33619
telemt_upstream_connect_success_total 30642
telemt_upstream_connect_fail_total 2977
telemt_upstream_connect_attempts_per_request{bucket="1"} 33619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2977
telemt_me_keepalive_timeout_total 2911
telemt_me_reconnect_attempts_total 24271
telemt_me_reconnect_success_total 22140
telemt_me_reader_eof_total 23463
telemt_me_idle_close_by_peer_total 23460
telemt_me_route_drop_no_conn_total 385872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 852215
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3377
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 22468
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22117
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 854651
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 10319507026 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 255337243252 (237.80 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110279.2 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1777188
telemt_connections_bad_total 11326
telemt_handshake_timeouts_total 136516
telemt_upstream_connect_attempt_total 31685
telemt_upstream_connect_success_total 31330
telemt_upstream_connect_fail_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 31685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 355
telemt_me_keepalive_timeout_total 2048
telemt_me_reconnect_attempts_total 61155
telemt_me_reconnect_success_total 20649
telemt_me_reader_eof_total 22774
telemt_me_idle_close_by_peer_total 22774
telemt_me_route_drop_no_conn_total 644989
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1559254
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4209
telemt_desync_full_logged_total 1242
telemt_desync_suppressed_total 2967
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1601
telemt_desync_frames_bucket_total{bucket="gt_10"} 1624
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22197
telemt_me_refill_failed_total 1260
telemt_me_writer_restored_same_endpoint_total 20637
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 1562897
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 19962036543 (18.59 GB)
telemt_user_octets_to_client{user="hello"} 478419252167 (445.56 GB)
telemt_user_msgs_from_client{user="hello"} 57401
telemt_user_msgs_to_client{user="hello"} 301652
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110279.7 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271832
telemt_connections_bad_total 78273
telemt_handshake_timeouts_total 111669
telemt_upstream_connect_attempt_total 29618
telemt_upstream_connect_success_total 29618
telemt_upstream_connect_attempts_per_request{bucket="1"} 29618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1552
telemt_me_reconnect_attempts_total 28717
telemt_me_reconnect_success_total 24097
telemt_me_reader_eof_total 25593
telemt_me_idle_close_by_peer_total 25592
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 427000
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045989
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 24499
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24064
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1045110
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 12301181772 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 316387425764 (294.66 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14955.8 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209558
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 2375
telemt_upstream_connect_attempt_total 4311
telemt_upstream_connect_success_total 4310
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 3532
telemt_me_reconnect_success_total 3498
telemt_me_reader_eof_total 3619
telemt_me_idle_close_by_peer_total 3619
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 71370
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185227
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 475
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3541
telemt_me_writer_restored_same_endpoint_total 3472
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 185189
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 9653652276 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 64487712228 (60.06 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 68
```