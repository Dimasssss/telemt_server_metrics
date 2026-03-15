# Server Metrics 2026-03-15 11:16:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 46909.2 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211414
telemt_connections_bad_total 77117
telemt_handshake_timeouts_total 10114
telemt_upstream_connect_attempt_total 9363
telemt_upstream_connect_success_total 9321
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9461
telemt_me_reconnect_success_total 6955
telemt_me_reader_eof_total 7419
telemt_me_idle_close_by_peer_total 7419
telemt_me_route_drop_no_conn_total 403566
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1021200
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3896
telemt_desync_full_logged_total 1095
telemt_desync_suppressed_total 2801
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1541
telemt_desync_frames_bucket_total{bucket="gt_10"} 1413
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7133
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6944
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1021197
telemt_user_connections_current{user="hello"} 2199
telemt_user_octets_from_client{user="hello"} 14390479304 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 409364725112 (381.25 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 46909.8 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475488
telemt_connections_bad_total 25738
telemt_handshake_timeouts_total 21427
telemt_upstream_connect_attempt_total 12326
telemt_upstream_connect_success_total 12262
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9629
telemt_me_reconnect_success_total 9567
telemt_me_reader_eof_total 10120
telemt_me_idle_close_by_peer_total 10120
telemt_me_route_drop_no_conn_total 121717
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374631
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9667
telemt_me_writer_restored_same_endpoint_total 9555
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 374902
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 5443285999 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 142791829196 (132.99 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 46909.7 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928983
telemt_connections_bad_total 30482
telemt_handshake_timeouts_total 91779
telemt_upstream_connect_attempt_total 10292
telemt_upstream_connect_success_total 10245
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 10292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 7927
telemt_me_reconnect_success_total 7875
telemt_me_reader_eof_total 8339
telemt_me_idle_close_by_peer_total 8339
telemt_me_route_drop_no_conn_total 256500
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7979
telemt_me_writer_restored_same_endpoint_total 7856
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 655422
telemt_user_connections_current{user="hello"} 1217
telemt_user_octets_from_client{user="hello"} 9891196044 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 257683855748 (239.99 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 46909.7 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486398
telemt_connections_bad_total 59914
telemt_handshake_timeouts_total 26552
telemt_upstream_connect_attempt_total 14011
telemt_upstream_connect_success_total 13649
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 14011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 32736
telemt_me_reconnect_success_total 11282
telemt_me_reader_eof_total 12284
telemt_me_idle_close_by_peer_total 12284
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 136923
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364944
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 855
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12057
telemt_me_refill_failed_total 670
telemt_me_writer_restored_same_endpoint_total 11250
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 775
telemt_user_connections_total{user="hello"} 364845
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 4540305784 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 114150769804 (106.31 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 46910.6 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507287
telemt_connections_bad_total 6229
telemt_handshake_timeouts_total 10645
telemt_upstream_connect_attempt_total 10500
telemt_upstream_connect_success_total 10449
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 8124
telemt_me_reconnect_success_total 8080
telemt_me_reader_eof_total 8570
telemt_me_idle_close_by_peer_total 8570
telemt_me_route_drop_no_conn_total 130793
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418230
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1626
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8173
telemt_me_writer_restored_same_endpoint_total 8072
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 418252
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 5370968772 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 156546988572 (145.80 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 106
```