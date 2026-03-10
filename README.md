# Server Metrics 2026-03-10 22:03:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27395.0 (7h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719952
telemt_connections_bad_total 8313
telemt_handshake_timeouts_total 8253
telemt_upstream_connect_attempt_total 5916
telemt_upstream_connect_success_total 5907
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 16109
telemt_me_reconnect_success_total 4450
telemt_me_reader_eof_total 4918
telemt_me_idle_close_by_peer_total 4918
telemt_me_route_drop_no_conn_total 300041
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680777
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3382
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2431
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1270
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4849
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4444
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 680583
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 9900477480 (9.22 GB)
telemt_user_octets_to_client{user="hello"} 206065851312 (191.91 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27451.6 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313745
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 17512
telemt_upstream_connect_attempt_total 12392
telemt_upstream_connect_success_total 9529
telemt_upstream_connect_fail_total 2863
telemt_upstream_connect_attempts_per_request{bucket="1"} 12392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2863
telemt_me_keepalive_timeout_total 1373
telemt_me_reconnect_attempts_total 5965
telemt_me_reconnect_success_total 5159
telemt_me_reader_eof_total 5417
telemt_me_idle_close_by_peer_total 5415
telemt_me_route_drop_no_conn_total 164939
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264009
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1554
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1120
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5244
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5138
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 266282
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2635526462 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62575891768 (58.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27451.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515793
telemt_connections_bad_total 3006
telemt_handshake_timeouts_total 33611
telemt_upstream_connect_attempt_total 7678
telemt_upstream_connect_success_total 7562
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 16119
telemt_me_reconnect_success_total 5067
telemt_me_reader_eof_total 5580
telemt_me_idle_close_by_peer_total 5580
telemt_me_route_drop_no_conn_total 179259
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450940
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1442
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5491
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5056
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 451873
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 6562349533 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 145746596553 (135.74 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27452.0 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358379
telemt_connections_bad_total 26532
telemt_handshake_timeouts_total 31466
telemt_upstream_connect_attempt_total 7631
telemt_upstream_connect_success_total 7631
telemt_upstream_connect_attempts_per_request{bucket="1"} 7631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 7232
telemt_me_reconnect_success_total 6208
telemt_me_reader_eof_total 6521
telemt_me_idle_close_by_peer_total 6521
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 116123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287598
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6307
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6194
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 287276
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 4014785172 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 85751924996 (79.86 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27451.7 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377651
telemt_connections_bad_total 1192
telemt_handshake_timeouts_total 2431
telemt_upstream_connect_attempt_total 8504
telemt_upstream_connect_success_total 8470
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 10773
telemt_me_reconnect_success_total 7016
telemt_me_reader_eof_total 7338
telemt_me_idle_close_by_peer_total 7338
telemt_me_route_drop_no_conn_total 133434
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353483
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2103
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7235
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7016
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 353331
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 6390251532 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 133800421212 (124.61 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 55
```