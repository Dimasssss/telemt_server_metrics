# Server Metrics 2026-03-15 11:21:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 47215.6 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227685
telemt_connections_bad_total 77299
telemt_handshake_timeouts_total 10262
telemt_upstream_connect_attempt_total 9466
telemt_upstream_connect_success_total 9424
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9558
telemt_me_reconnect_success_total 7052
telemt_me_reader_eof_total 7516
telemt_me_idle_close_by_peer_total 7516
telemt_me_route_drop_no_conn_total 409193
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3933
telemt_desync_full_logged_total 1113
telemt_desync_suppressed_total 2820
telemt_desync_frames_bucket_total{bucket="1_2"} 949
telemt_desync_frames_bucket_total{bucket="3_10"} 1553
telemt_desync_frames_bucket_total{bucket="gt_10"} 1431
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7230
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7041
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1034919
telemt_user_connections_current{user="hello"} 2298
telemt_user_octets_from_client{user="hello"} 14570370368 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 416457654092 (387.86 GB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 47216.2 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481492
telemt_connections_bad_total 25979
telemt_handshake_timeouts_total 21555
telemt_upstream_connect_attempt_total 12404
telemt_upstream_connect_success_total 12340
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9707
telemt_me_reconnect_success_total 9644
telemt_me_reader_eof_total 10205
telemt_me_idle_close_by_peer_total 10205
telemt_me_route_drop_no_conn_total 123247
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379734
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1356
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 489
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9746
telemt_me_writer_restored_same_endpoint_total 9632
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 380005
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 5497247547 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 144109059232 (134.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 47216.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939335
telemt_connections_bad_total 30727
telemt_handshake_timeouts_total 92412
telemt_upstream_connect_attempt_total 10399
telemt_upstream_connect_success_total 10350
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 8021
telemt_me_reconnect_success_total 7967
telemt_me_reader_eof_total 8435
telemt_me_idle_close_by_peer_total 8435
telemt_me_route_drop_no_conn_total 260383
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1602
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1034
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 661
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8075
telemt_me_writer_restored_same_endpoint_total 7948
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 662985
telemt_user_connections_current{user="hello"} 1248
telemt_user_octets_from_client{user="hello"} 9948607484 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 259677688832 (241.84 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 47216.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492186
telemt_connections_bad_total 60501
telemt_handshake_timeouts_total 26694
telemt_upstream_connect_attempt_total 14067
telemt_upstream_connect_success_total 13705
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 14067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 34060
telemt_me_reconnect_success_total 11326
telemt_me_reader_eof_total 12369
telemt_me_idle_close_by_peer_total 12369
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 138488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369168
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 880
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12142
telemt_me_refill_failed_total 710
telemt_me_writer_restored_same_endpoint_total 11294
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 369069
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 4577062296 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 115501043312 (107.57 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 47217.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513533
telemt_connections_bad_total 6229
telemt_handshake_timeouts_total 10769
telemt_upstream_connect_attempt_total 10572
telemt_upstream_connect_success_total 10521
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 8196
telemt_me_reconnect_success_total 8152
telemt_me_reader_eof_total 8659
telemt_me_idle_close_by_peer_total 8659
telemt_me_route_drop_no_conn_total 132466
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1648
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1111
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8244
telemt_me_writer_restored_same_endpoint_total 8144
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 424148
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 5448300388 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 157635958212 (146.81 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 136
```