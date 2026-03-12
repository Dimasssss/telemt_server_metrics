# Server Metrics 2026-03-12 17:08:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 40161.3 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1450381
telemt_connections_bad_total 20276
telemt_handshake_timeouts_total 13733
telemt_upstream_connect_attempt_total 8023
telemt_upstream_connect_success_total 7977
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 13593
telemt_me_reconnect_success_total 5934
telemt_me_reader_eof_total 6408
telemt_me_idle_close_by_peer_total 6407
telemt_me_route_drop_no_conn_total 536382
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1359369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6901
telemt_desync_full_logged_total 1737
telemt_desync_suppressed_total 5164
telemt_desync_frames_bucket_total{bucket="1_2"} 1796
telemt_desync_frames_bucket_total{bucket="3_10"} 2497
telemt_desync_frames_bucket_total{bucket="gt_10"} 2608
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6250
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 5921
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 1359042
telemt_user_connections_current{user="hello"} 1850
telemt_user_octets_from_client{user="hello"} 20567123920 (19.15 GB)
telemt_user_octets_to_client{user="hello"} 408867907692 (380.79 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69781.9 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634043
telemt_connections_bad_total 8500
telemt_handshake_timeouts_total 28863
telemt_upstream_connect_attempt_total 16658
telemt_upstream_connect_success_total 16651
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 13053
telemt_me_reconnect_success_total 12977
telemt_me_reader_eof_total 13795
telemt_me_idle_close_by_peer_total 13795
telemt_me_route_drop_no_conn_total 195356
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568891
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2374
telemt_desync_full_logged_total 736
telemt_desync_suppressed_total 1638
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 13107
telemt_me_writer_restored_same_endpoint_total 12968
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 569428
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 8750969227 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 208030286566 (193.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 69781.8 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1325906
telemt_connections_bad_total 6581
telemt_handshake_timeouts_total 95244
telemt_upstream_connect_attempt_total 16676
telemt_upstream_connect_success_total 16671
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1123
telemt_me_reconnect_attempts_total 14050
telemt_me_reconnect_success_total 12815
telemt_me_reader_eof_total 13504
telemt_me_idle_close_by_peer_total 13503
telemt_me_route_drop_no_conn_total 427115
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 996191
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4277
telemt_desync_full_logged_total 1319
telemt_desync_suppressed_total 2958
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1553
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12915
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12774
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 996038
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 14942082704 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 336110245477 (313.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 69782.3 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798493
telemt_connections_bad_total 8329
telemt_handshake_timeouts_total 62022
telemt_upstream_connect_attempt_total 18246
telemt_upstream_connect_success_total 18175
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1568
telemt_me_reconnect_attempts_total 19929
telemt_me_reconnect_success_total 14676
telemt_me_reader_eof_total 15636
telemt_me_idle_close_by_peer_total 15636
telemt_me_route_drop_no_conn_total 276945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691572
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1487
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14954
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14655
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 690999
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 8493733856 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 274089810456 (255.27 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69782.0 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901548
telemt_connections_bad_total 11392
telemt_handshake_timeouts_total 7374
telemt_upstream_connect_attempt_total 22214
telemt_upstream_connect_success_total 21948
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 22214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 1276
telemt_me_reconnect_attempts_total 25908
telemt_me_reconnect_success_total 18434
telemt_me_reader_eof_total 19271
telemt_me_idle_close_by_peer_total 19271
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 326340
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3268
telemt_desync_full_logged_total 1114
telemt_desync_suppressed_total 2154
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1114
telemt_desync_frames_bucket_total{bucket="gt_10"} 1271
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18866
telemt_me_refill_failed_total 231
telemt_me_writer_restored_same_endpoint_total 18390
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 827831
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 10163100868 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 246527805908 (229.60 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 111
```