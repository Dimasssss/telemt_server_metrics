# Server Metrics 2026-03-12 10:14:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15361.3 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498306
telemt_connections_bad_total 1464
telemt_handshake_timeouts_total 2788
telemt_upstream_connect_attempt_total 3025
telemt_upstream_connect_success_total 3007
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 4841
telemt_me_reconnect_success_total 2204
telemt_me_reader_eof_total 2353
telemt_me_idle_close_by_peer_total 2353
telemt_me_route_drop_no_conn_total 172106
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482512
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1721
telemt_desync_frames_bucket_total{bucket="1_2"} 583
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 863
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2303
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 2191
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 482381
telemt_user_connections_current{user="hello"} 1488
telemt_user_octets_from_client{user="hello"} 7771421468 (7.24 GB)
telemt_user_octets_to_client{user="hello"} 131340641156 (122.32 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44982.0 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286198
telemt_connections_bad_total 3035
telemt_handshake_timeouts_total 8496
telemt_upstream_connect_attempt_total 11341
telemt_upstream_connect_success_total 11335
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 672
telemt_me_reconnect_attempts_total 8967
telemt_me_reconnect_success_total 8923
telemt_me_reader_eof_total 9475
telemt_me_idle_close_by_peer_total 9475
telemt_me_route_drop_no_conn_total 83121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255922
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 524
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8996
telemt_me_writer_restored_same_endpoint_total 8914
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 256361
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 3583969703 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 94731327894 (88.23 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44981.9 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731261
telemt_connections_bad_total 3690
telemt_handshake_timeouts_total 53402
telemt_upstream_connect_attempt_total 11351
telemt_upstream_connect_success_total 11346
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 8836
telemt_me_reconnect_success_total 8763
telemt_me_reader_eof_total 9200
telemt_me_idle_close_by_peer_total 9200
telemt_me_route_drop_no_conn_total 162135
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461483
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2101
telemt_desync_full_logged_total 623
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8772
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8722
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 461737
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 5517187304 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 151194673541 (140.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44982.2 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371103
telemt_connections_bad_total 2185
telemt_handshake_timeouts_total 27709
telemt_upstream_connect_attempt_total 12198
telemt_upstream_connect_success_total 12149
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 12198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 828
telemt_me_reconnect_attempts_total 9952
telemt_me_reconnect_success_total 9915
telemt_me_reader_eof_total 10517
telemt_me_idle_close_by_peer_total 10517
telemt_me_route_drop_no_conn_total 126248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312872
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9980
telemt_me_writer_restored_same_endpoint_total 9894
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 312694
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 3805941864 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 122530977544 (114.12 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44982.1 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419982
telemt_connections_bad_total 468
telemt_handshake_timeouts_total 3244
telemt_upstream_connect_attempt_total 14646
telemt_upstream_connect_success_total 14473
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 626
telemt_me_reconnect_attempts_total 13753
telemt_me_reconnect_success_total 12229
telemt_me_reader_eof_total 12723
telemt_me_idle_close_by_peer_total 12723
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 135870
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396563
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1679
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1130
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 12394
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12207
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 396491
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 4407267760 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 95118098592 (88.59 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 86
```