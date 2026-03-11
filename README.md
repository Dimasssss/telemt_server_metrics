# Server Metrics 2026-03-11 07:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62457.8 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265264
telemt_connections_bad_total 13656
telemt_handshake_timeouts_total 39473
telemt_upstream_connect_attempt_total 13011
telemt_upstream_connect_success_total 13002
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 719
telemt_me_reconnect_attempts_total 21519
telemt_me_reconnect_success_total 9835
telemt_me_reader_eof_total 10686
telemt_me_idle_close_by_peer_total 10686
telemt_me_route_drop_no_conn_total 466169
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1143894
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5595
telemt_desync_full_logged_total 1564
telemt_desync_suppressed_total 4031
telemt_desync_frames_bucket_total{bucket="1_2"} 1477
telemt_desync_frames_bucket_total{bucket="3_10"} 2112
telemt_desync_frames_bucket_total{bucket="gt_10"} 2006
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10297
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9829
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1143550
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 15028986200 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 335159322960 (312.14 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62514.4 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492452
telemt_connections_bad_total 7332
telemt_handshake_timeouts_total 28086
telemt_upstream_connect_attempt_total 21923
telemt_upstream_connect_success_total 19004
telemt_upstream_connect_fail_total 2919
telemt_upstream_connect_attempts_per_request{bucket="1"} 21923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2919
telemt_me_keepalive_timeout_total 2046
telemt_me_reconnect_attempts_total 13748
telemt_me_reconnect_success_total 12921
telemt_me_reader_eof_total 13672
telemt_me_idle_close_by_peer_total 13670
telemt_me_route_drop_no_conn_total 213035
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2087
telemt_desync_full_logged_total 639
telemt_desync_suppressed_total 1448
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13069
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12899
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 419434
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 4120376758 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 110941745964 (103.32 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62514.3 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825652
telemt_connections_bad_total 6911
telemt_handshake_timeouts_total 44585
telemt_upstream_connect_attempt_total 16926
telemt_upstream_connect_success_total 16716
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 16926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 742
telemt_me_reconnect_attempts_total 24859
telemt_me_reconnect_success_total 12502
telemt_me_reader_eof_total 13466
telemt_me_idle_close_by_peer_total 13466
telemt_me_route_drop_no_conn_total 280464
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 739182
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2141
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 866
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 13047
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12491
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 739973
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 8650513493 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 218956571857 (203.92 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62514.6 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630805
telemt_connections_bad_total 58532
telemt_handshake_timeouts_total 62265
telemt_upstream_connect_attempt_total 17524
telemt_upstream_connect_success_total 17524
telemt_upstream_connect_attempts_per_request{bucket="1"} 17524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 664
telemt_me_reconnect_attempts_total 15441
telemt_me_reconnect_success_total 14390
telemt_me_reader_eof_total 15286
telemt_me_idle_close_by_peer_total 15285
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 193740
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489397
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1145
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 704
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 430
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14558
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14368
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 488795
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 5850834656 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 134096809136 (124.89 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62514.4 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659985
telemt_connections_bad_total 5975
telemt_handshake_timeouts_total 4973
telemt_upstream_connect_attempt_total 17386
telemt_upstream_connect_success_total 17314
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 17854
telemt_me_reconnect_success_total 14066
telemt_me_reader_eof_total 14869
telemt_me_idle_close_by_peer_total 14869
telemt_me_route_drop_no_conn_total 220518
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601697
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2754
telemt_desync_full_logged_total 1043
telemt_desync_suppressed_total 1711
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14363
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14066
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 601407
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 10091590591 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 219469208506 (204.40 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 86
```