# Server Metrics 2026-03-15 11:41:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 48440.7 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1297074
telemt_connections_bad_total 78840
telemt_handshake_timeouts_total 10729
telemt_upstream_connect_attempt_total 9741
telemt_upstream_connect_success_total 9699
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 9787
telemt_me_reconnect_success_total 7280
telemt_me_reader_eof_total 7750
telemt_me_idle_close_by_peer_total 7750
telemt_me_route_drop_no_conn_total 430748
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088382
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4147
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 2969
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 1631
telemt_desync_frames_bucket_total{bucket="gt_10"} 1515
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7465
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7269
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 1088165
telemt_user_connections_current{user="hello"} 2318
telemt_user_octets_from_client{user="hello"} 15210844208 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 438904802856 (408.76 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 48441.4 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507548
telemt_connections_bad_total 27008
telemt_handshake_timeouts_total 23379
telemt_upstream_connect_attempt_total 12645
telemt_upstream_connect_success_total 12580
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9900
telemt_me_reconnect_success_total 9834
telemt_me_reader_eof_total 10399
telemt_me_idle_close_by_peer_total 10399
telemt_me_route_drop_no_conn_total 130272
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400134
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1496
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 982
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9940
telemt_me_writer_restored_same_endpoint_total 9822
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 400404
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 5780807643 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 149637185580 (139.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 48441.4 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993339
telemt_connections_bad_total 32884
telemt_handshake_timeouts_total 100655
telemt_upstream_connect_attempt_total 10714
telemt_upstream_connect_success_total 10665
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 8289
telemt_me_reconnect_success_total 8234
telemt_me_reader_eof_total 8704
telemt_me_idle_close_by_peer_total 8704
telemt_me_route_drop_no_conn_total 282472
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 609
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 704
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8343
telemt_me_writer_restored_same_endpoint_total 8215
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 694002
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 10298615872 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 269243326884 (250.75 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 48441.3 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515769
telemt_connections_bad_total 63406
telemt_handshake_timeouts_total 27317
telemt_upstream_connect_attempt_total 14253
telemt_upstream_connect_success_total 13888
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 14253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 35447
telemt_me_reconnect_success_total 11465
telemt_me_reader_eof_total 12550
telemt_me_idle_close_by_peer_total 12550
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 145313
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386173
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1007
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12324
telemt_me_refill_failed_total 749
telemt_me_writer_restored_same_endpoint_total 11433
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 386072
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 4718321712 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 123899789480 (115.39 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 48442.6 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542328
telemt_connections_bad_total 6571
telemt_handshake_timeouts_total 11882
telemt_upstream_connect_attempt_total 10771
telemt_upstream_connect_success_total 10718
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 8350
telemt_me_reconnect_success_total 8304
telemt_me_reader_eof_total 8820
telemt_me_idle_close_by_peer_total 8820
telemt_me_route_drop_no_conn_total 139152
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446859
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1759
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8397
telemt_me_writer_restored_same_endpoint_total 8296
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 446888
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 5952706396 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 162613301428 (151.45 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 118
```