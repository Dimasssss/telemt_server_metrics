# Server Metrics 2026-03-11 04:19:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49951.8 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 965438
telemt_connections_bad_total 10073
telemt_handshake_timeouts_total 27602
telemt_upstream_connect_attempt_total 10781
telemt_upstream_connect_success_total 10772
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 531
telemt_me_reconnect_attempts_total 19893
telemt_me_reconnect_success_total 8219
telemt_me_reader_eof_total 8962
telemt_me_idle_close_by_peer_total 8962
telemt_me_route_drop_no_conn_total 365416
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874327
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3985
telemt_desync_full_logged_total 1114
telemt_desync_suppressed_total 2871
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1358
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8659
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8213
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 874047
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 11462865160 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 258230188548 (240.50 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50008.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385684
telemt_connections_bad_total 2531
telemt_handshake_timeouts_total 18852
telemt_upstream_connect_attempt_total 18989
telemt_upstream_connect_success_total 16092
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 18989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1775
telemt_me_reconnect_attempts_total 11442
telemt_me_reconnect_success_total 10624
telemt_me_reader_eof_total 11217
telemt_me_idle_close_by_peer_total 11215
telemt_me_route_drop_no_conn_total 184598
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330826
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1841
telemt_desync_full_logged_total 545
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10749
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10603
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 333097
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 3188847670 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 78192853932 (72.82 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50008.3 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648341
telemt_connections_bad_total 5546
telemt_handshake_timeouts_total 35950
telemt_upstream_connect_attempt_total 13537
telemt_upstream_connect_success_total 13362
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 557
telemt_me_reconnect_attempts_total 20837
telemt_me_reconnect_success_total 9767
telemt_me_reader_eof_total 10581
telemt_me_idle_close_by_peer_total 10581
telemt_me_route_drop_no_conn_total 219027
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577373
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10242
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9756
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 578264
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 7260671581 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 175772556473 (163.70 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50008.8 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493503
telemt_connections_bad_total 47112
telemt_handshake_timeouts_total 51601
telemt_upstream_connect_attempt_total 14529
telemt_upstream_connect_success_total 14529
telemt_upstream_connect_attempts_per_request{bucket="1"} 14529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 483
telemt_me_reconnect_attempts_total 13053
telemt_me_reconnect_success_total 12013
telemt_me_reader_eof_total 12759
telemt_me_idle_close_by_peer_total 12759
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 146870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380658
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 12154
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11993
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 380329
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 4590454156 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 103193201200 (96.11 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50008.4 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518424
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 3224
telemt_upstream_connect_attempt_total 14560
telemt_upstream_connect_success_total 14499
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 552
telemt_me_reconnect_attempts_total 15720
telemt_me_reconnect_success_total 11939
telemt_me_reader_eof_total 12595
telemt_me_idle_close_by_peer_total 12595
telemt_me_route_drop_no_conn_total 167739
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471943
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2389
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 1457
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1013
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 12207
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11939
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 471568
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 8740326992 (8.14 GB)
telemt_user_octets_to_client{user="hello"} 167161250932 (155.68 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 58
```