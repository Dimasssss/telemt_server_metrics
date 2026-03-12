# Server Metrics 2026-03-12 16:57:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39548.6 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1428419
telemt_connections_bad_total 20252
telemt_handshake_timeouts_total 13584
telemt_upstream_connect_attempt_total 7916
telemt_upstream_connect_success_total 7871
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 12221
telemt_me_reconnect_success_total 5874
telemt_me_reader_eof_total 6307
telemt_me_idle_close_by_peer_total 6306
telemt_me_route_drop_no_conn_total 525471
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1338853
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6804
telemt_desync_full_logged_total 1712
telemt_desync_suppressed_total 5092
telemt_desync_frames_bucket_total{bucket="1_2"} 1760
telemt_desync_frames_bucket_total{bucket="3_10"} 2457
telemt_desync_frames_bucket_total{bucket="gt_10"} 2587
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6148
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 5861
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 1338524
telemt_user_connections_current{user="hello"} 1920
telemt_user_octets_from_client{user="hello"} 20294646172 (18.90 GB)
telemt_user_octets_to_client{user="hello"} 395462978792 (368.30 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69168.9 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625397
telemt_connections_bad_total 8221
telemt_handshake_timeouts_total 28773
telemt_upstream_connect_attempt_total 16518
telemt_upstream_connect_success_total 16511
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 12956
telemt_me_reconnect_success_total 12882
telemt_me_reader_eof_total 13694
telemt_me_idle_close_by_peer_total 13694
telemt_me_route_drop_no_conn_total 192048
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560906
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2305
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1585
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 13012
telemt_me_writer_restored_same_endpoint_total 12873
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 561434
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 8646027031 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 200971958118 (187.17 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69168.9 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1311602
telemt_connections_bad_total 6573
telemt_handshake_timeouts_total 94871
telemt_upstream_connect_attempt_total 16490
telemt_upstream_connect_success_total 16485
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1083
telemt_me_reconnect_attempts_total 13908
telemt_me_reconnect_success_total 12674
telemt_me_reader_eof_total 13361
telemt_me_idle_close_by_peer_total 13360
telemt_me_route_drop_no_conn_total 368821
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982413
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4214
telemt_desync_full_logged_total 1300
telemt_desync_suppressed_total 2914
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 1529
telemt_desync_frames_bucket_total{bucket="gt_10"} 2033
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12770
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12633
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 982565
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 14807614212 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 322375495101 (300.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69169.4 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788536
telemt_connections_bad_total 7927
telemt_handshake_timeouts_total 61626
telemt_upstream_connect_attempt_total 18078
telemt_upstream_connect_success_total 18007
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1546
telemt_me_reconnect_attempts_total 19804
telemt_me_reconnect_success_total 14554
telemt_me_reader_eof_total 15499
telemt_me_idle_close_by_peer_total 15499
telemt_me_route_drop_no_conn_total 273271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682707
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1441
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 952
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14829
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14533
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 682135
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 8422525988 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 267601238000 (249.22 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69169.0 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890651
telemt_connections_bad_total 11390
telemt_handshake_timeouts_total 7269
telemt_upstream_connect_attempt_total 21909
telemt_upstream_connect_success_total 21645
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 21909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 1244
telemt_me_reconnect_attempts_total 25430
telemt_me_reconnect_success_total 18185
telemt_me_reader_eof_total 19014
telemt_me_idle_close_by_peer_total 19014
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 320520
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818119
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3225
telemt_desync_full_logged_total 1101
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1251
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18608
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 18141
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 818005
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 10068197588 (9.38 GB)
telemt_user_octets_to_client{user="hello"} 238619251268 (222.23 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 95
```