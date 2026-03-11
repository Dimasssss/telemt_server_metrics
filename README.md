# Server Metrics 2026-03-11 06:41:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58490.0 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1157376
telemt_connections_bad_total 13235
telemt_handshake_timeouts_total 38677
telemt_upstream_connect_attempt_total 12292
telemt_upstream_connect_success_total 12283
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 21015
telemt_me_reconnect_success_total 9332
telemt_me_reader_eof_total 10145
telemt_me_idle_close_by_peer_total 10145
telemt_me_route_drop_no_conn_total 425597
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041695
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4956
telemt_desync_full_logged_total 1390
telemt_desync_suppressed_total 3566
telemt_desync_frames_bucket_total{bucket="1_2"} 1341
telemt_desync_frames_bucket_total{bucket="3_10"} 1861
telemt_desync_frames_bucket_total{bucket="gt_10"} 1754
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9787
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9326
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 1041360
telemt_user_connections_current{user="hello"} 1168
telemt_user_octets_from_client{user="hello"} 13822413152 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 305322994440 (284.35 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58546.8 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446350
telemt_connections_bad_total 5099
telemt_handshake_timeouts_total 21858
telemt_upstream_connect_attempt_total 21014
telemt_upstream_connect_success_total 18103
telemt_upstream_connect_fail_total 2911
telemt_upstream_connect_attempts_per_request{bucket="1"} 21014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2911
telemt_me_keepalive_timeout_total 2017
telemt_me_reconnect_attempts_total 13050
telemt_me_reconnect_success_total 12225
telemt_me_reader_eof_total 12921
telemt_me_idle_close_by_peer_total 12919
telemt_me_route_drop_no_conn_total 201725
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381773
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1948
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12368
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12203
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 384043
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3826205510 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 95745262996 (89.17 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58546.6 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759795
telemt_connections_bad_total 6622
telemt_handshake_timeouts_total 41327
telemt_upstream_connect_attempt_total 15655
telemt_upstream_connect_success_total 15452
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 696
telemt_me_reconnect_attempts_total 22525
telemt_me_reconnect_success_total 11452
telemt_me_reader_eof_total 12347
telemt_me_idle_close_by_peer_total 12347
telemt_me_route_drop_no_conn_total 256666
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679446
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1945
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 787
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11945
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11441
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 680277
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 8042250781 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 201573682913 (187.73 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58547.0 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578231
telemt_connections_bad_total 54904
telemt_handshake_timeouts_total 58874
telemt_upstream_connect_attempt_total 16607
telemt_upstream_connect_success_total 16607
telemt_upstream_connect_attempts_per_request{bucket="1"} 16607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 14722
telemt_me_reconnect_success_total 13675
telemt_me_reader_eof_total 14518
telemt_me_idle_close_by_peer_total 14518
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 174410
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447648
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 945
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13835
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13653
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 447188
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 5352674016 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 122743194324 (114.31 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58546.7 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604122
telemt_connections_bad_total 5965
telemt_handshake_timeouts_total 4269
telemt_upstream_connect_attempt_total 16558
telemt_upstream_connect_success_total 16490
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 17231
telemt_me_reconnect_success_total 13445
telemt_me_reader_eof_total 14204
telemt_me_idle_close_by_peer_total 14204
telemt_me_route_drop_no_conn_total 198748
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549983
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2593
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 1599
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13736
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13445
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 549716
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 9574988991 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 198924631722 (185.26 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 99
```