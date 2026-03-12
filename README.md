# Server Metrics 2026-03-12 17:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43227.4 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1555756
telemt_connections_bad_total 20345
telemt_handshake_timeouts_total 14557
telemt_upstream_connect_attempt_total 8527
telemt_upstream_connect_success_total 8475
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 530
telemt_me_reconnect_attempts_total 15135
telemt_me_reconnect_success_total 6289
telemt_me_reader_eof_total 6816
telemt_me_idle_close_by_peer_total 6815
telemt_me_route_drop_no_conn_total 605296
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1457543
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7428
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 5540
telemt_desync_frames_bucket_total{bucket="1_2"} 1919
telemt_desync_frames_bucket_total{bucket="3_10"} 2708
telemt_desync_frames_bucket_total{bucket="gt_10"} 2801
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6653
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6276
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 364
telemt_user_connections_total{user="hello"} 1457036
telemt_user_connections_current{user="hello"} 1618
telemt_user_octets_from_client{user="hello"} 22231516784 (20.70 GB)
telemt_user_octets_to_client{user="hello"} 477457125356 (444.67 GB)
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72847.8 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673837
telemt_connections_bad_total 8711
telemt_handshake_timeouts_total 29211
telemt_upstream_connect_attempt_total 18689
telemt_upstream_connect_success_total 18660
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3327
telemt_me_reconnect_attempts_total 13456
telemt_me_reconnect_success_total 13372
telemt_me_reader_eof_total 14214
telemt_me_idle_close_by_peer_total 14214
telemt_me_route_drop_no_conn_total 212803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2577
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1784
telemt_desync_frames_bucket_total{bucket="1_2"} 1064
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 668
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13511
telemt_me_writer_restored_same_endpoint_total 13363
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 607404
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 9193426872 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 228935411987 (213.21 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72847.6 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1401316
telemt_connections_bad_total 6882
telemt_handshake_timeouts_total 98821
telemt_upstream_connect_attempt_total 17268
telemt_upstream_connect_success_total 17263
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1140
telemt_me_reconnect_attempts_total 14503
telemt_me_reconnect_success_total 13264
telemt_me_reader_eof_total 13986
telemt_me_idle_close_by_peer_total 13985
telemt_me_route_drop_no_conn_total 455851
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1065290
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4497
telemt_desync_full_logged_total 1396
telemt_desync_suppressed_total 3101
telemt_desync_frames_bucket_total{bucket="1_2"} 692
telemt_desync_frames_bucket_total{bucket="3_10"} 1640
telemt_desync_frames_bucket_total{bucket="gt_10"} 2165
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13373
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13223
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 1065152
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 15980879200 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 380049079053 (353.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72848.0 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847152
telemt_connections_bad_total 10618
telemt_handshake_timeouts_total 64205
telemt_upstream_connect_attempt_total 18996
telemt_upstream_connect_success_total 18923
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1608
telemt_me_reconnect_attempts_total 21694
telemt_me_reconnect_success_total 15287
telemt_me_reader_eof_total 16287
telemt_me_idle_close_by_peer_total 16287
telemt_me_route_drop_no_conn_total 297011
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734029
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1669
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1111
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15607
telemt_me_refill_failed_total 198
telemt_me_writer_restored_same_endpoint_total 15266
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 733444
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 9018268660 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 295706463180 (275.40 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72847.8 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954488
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7763
telemt_upstream_connect_attempt_total 23141
telemt_upstream_connect_success_total 22867
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1323
telemt_me_reconnect_attempts_total 30241
telemt_me_reconnect_success_total 19212
telemt_me_reader_eof_total 20178
telemt_me_idle_close_by_peer_total 20178
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 352666
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 876638
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3396
telemt_desync_full_logged_total 1169
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 939
telemt_desync_frames_bucket_total{bucket="3_10"} 1155
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19773
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19168
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 876518
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 10722488564 (9.99 GB)
telemt_user_octets_to_client{user="hello"} 276519033404 (257.53 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 102
```