# Server Metrics 2026-03-12 08:17:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8331.2 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253391
telemt_connections_bad_total 1314
telemt_handshake_timeouts_total 1831
telemt_upstream_connect_attempt_total 1660
telemt_upstream_connect_success_total 1649
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 734
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1192
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 85607
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244729
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1199
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 900
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 432
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_restored_same_endpoint_total 1171
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 244648
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 3920088032 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 70645035044 (65.79 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37951.7 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200434
telemt_connections_bad_total 2619
telemt_handshake_timeouts_total 7271
telemt_upstream_connect_attempt_total 9871
telemt_upstream_connect_success_total 9865
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 7803
telemt_me_reconnect_success_total 7763
telemt_me_reader_eof_total 8244
telemt_me_idle_close_by_peer_total 8244
telemt_me_route_drop_no_conn_total 57782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174548
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 427
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7825
telemt_me_writer_restored_same_endpoint_total 7754
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 174844
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2604808159 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 68732145654 (64.01 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37951.6 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584592
telemt_connections_bad_total 2700
telemt_handshake_timeouts_total 43455
telemt_upstream_connect_attempt_total 9969
telemt_upstream_connect_success_total 9964
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7757
telemt_me_reconnect_success_total 7687
telemt_me_reader_eof_total 8069
telemt_me_idle_close_by_peer_total 8069
telemt_me_route_drop_no_conn_total 113614
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329220
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1554
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7682
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7646
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 329498
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 3635433264 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 115563750337 (107.63 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37952.0 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275207
telemt_connections_bad_total 1795
telemt_handshake_timeouts_total 18650
telemt_upstream_connect_attempt_total 10556
telemt_upstream_connect_success_total 10514
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 10556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 8625
telemt_me_reconnect_success_total 8594
telemt_me_reader_eof_total 9127
telemt_me_idle_close_by_peer_total 9127
telemt_me_route_drop_no_conn_total 91303
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228352
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8649
telemt_me_writer_restored_same_endpoint_total 8573
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 228175
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 2599369680 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 78707995920 (73.30 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37951.8 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302033
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 2339
telemt_upstream_connect_attempt_total 12655
telemt_upstream_connect_success_total 12503
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 12087
telemt_me_reconnect_success_total 10573
telemt_me_reader_eof_total 11010
telemt_me_idle_close_by_peer_total 11010
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 96103
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284404
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1149
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 763
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10717
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10552
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 284347
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 2879478364 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 68614682772 (63.90 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 131
```