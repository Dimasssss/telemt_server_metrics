# Server Metrics 2026-03-14 09:18:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 184813.5 (51h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5262022
telemt_connections_bad_total 49226
telemt_handshake_timeouts_total 118338
telemt_upstream_connect_attempt_total 38824
telemt_upstream_connect_success_total 38573
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 38824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 7504
telemt_me_reconnect_attempts_total 38256
telemt_me_reconnect_success_total 27042
telemt_me_reader_eof_total 29020
telemt_me_idle_close_by_peer_total 29019
telemt_me_route_drop_no_conn_total 1989798
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4820774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18427
telemt_desync_full_logged_total 5034
telemt_desync_suppressed_total 13393
telemt_desync_frames_bucket_total{bucket="1_2"} 4552
telemt_desync_frames_bucket_total{bucket="3_10"} 7012
telemt_desync_frames_bucket_total{bucket="gt_10"} 6863
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 27788
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27029
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 4822259
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 73953528704 (68.87 GB)
telemt_user_octets_to_client{user="hello"} 1541189957449 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84477.3 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938963
telemt_connections_bad_total 54255
telemt_handshake_timeouts_total 18941
telemt_upstream_connect_attempt_total 22438
telemt_upstream_connect_success_total 22150
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 22438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 2213
telemt_me_reconnect_attempts_total 24488
telemt_me_reconnect_success_total 15929
telemt_me_reader_eof_total 17046
telemt_me_idle_close_by_peer_total 17045
telemt_me_route_drop_no_conn_total 313703
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763382
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 935
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16425
telemt_me_refill_failed_total 261
telemt_me_writer_restored_same_endpoint_total 15921
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 765280
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 8146645453 (7.59 GB)
telemt_user_octets_to_client{user="hello"} 264281090112 (246.13 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 214433.9 (59h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3750330
telemt_connections_bad_total 44506
telemt_handshake_timeouts_total 247986
telemt_upstream_connect_attempt_total 48434
telemt_upstream_connect_success_total 48413
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10878
telemt_me_reconnect_attempts_total 42407
telemt_me_reconnect_success_total 37415
telemt_me_reader_eof_total 39730
telemt_me_idle_close_by_peer_total 39729
telemt_me_route_drop_no_conn_total 1287595
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3131434
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10129
telemt_desync_full_logged_total 3442
telemt_desync_suppressed_total 6687
telemt_desync_frames_bucket_total{bucket="1_2"} 1799
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 201
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 37937
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37374
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 3130587
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 52817483780 (49.19 GB)
telemt_user_octets_to_client{user="hello"} 1118301775041 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 214436.5 (59h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2480527
telemt_connections_bad_total 23368
telemt_handshake_timeouts_total 306166
telemt_upstream_connect_attempt_total 66521
telemt_upstream_connect_success_total 64023
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 66247
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20621
telemt_me_reconnect_attempts_total 57965
telemt_me_reconnect_success_total 46318
telemt_me_reader_eof_total 49663
telemt_me_idle_close_by_peer_total 49656
telemt_me_route_drop_no_conn_total 830669
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1948296
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4004
telemt_desync_full_logged_total 1308
telemt_desync_suppressed_total 2696
telemt_desync_frames_bucket_total{bucket="1_2"} 1124
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 1244
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 47079
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46294
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1954456
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 29283308443 (27.27 GB)
telemt_user_octets_to_client{user="hello"} 707877310630 (659.26 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83870.1 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 923108
telemt_connections_bad_total 12985
telemt_handshake_timeouts_total 11836
telemt_upstream_connect_attempt_total 21263
telemt_upstream_connect_success_total 20693
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 21263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 1674
telemt_me_reconnect_attempts_total 67161
telemt_me_reconnect_success_total 16495
telemt_me_reader_eof_total 18487
telemt_me_idle_close_by_peer_total 18486
telemt_me_route_drop_no_conn_total 353152
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857623
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2276
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1566
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18233
telemt_me_refill_failed_total 1578
telemt_me_writer_restored_same_endpoint_total 16490
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1738
telemt_user_connections_total{user="hello"} 857563
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 15349251372 (14.30 GB)
telemt_user_octets_to_client{user="hello"} 290831404776 (270.86 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 86
```