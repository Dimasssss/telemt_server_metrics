# Server Metrics 2026-03-12 22:04:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57933.3 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1900619
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20869
telemt_upstream_connect_attempt_total 11412
telemt_upstream_connect_success_total 11346
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 11412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 17272
telemt_me_reconnect_success_total 8418
telemt_me_reader_eof_total 9098
telemt_me_idle_close_by_peer_total 9097
telemt_me_route_drop_no_conn_total 743326
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768870
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8477
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 6272
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 3190
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8814
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8405
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1768350
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 26826864560 (24.98 GB)
telemt_user_octets_to_client{user="hello"} 625639733832 (582.67 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87553.8 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790029
telemt_connections_bad_total 11690
telemt_handshake_timeouts_total 31188
telemt_upstream_connect_attempt_total 22135
telemt_upstream_connect_success_total 22106
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3407
telemt_me_reconnect_attempts_total 16163
telemt_me_reconnect_success_total 16069
telemt_me_reader_eof_total 17100
telemt_me_idle_close_by_peer_total 17100
telemt_me_route_drop_no_conn_total 255866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713340
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2996
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16232
telemt_me_writer_restored_same_endpoint_total 16060
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 715220
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 12026141340 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 274226611367 (255.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87553.7 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1638571
telemt_connections_bad_total 7742
telemt_handshake_timeouts_total 113198
telemt_upstream_connect_attempt_total 20467
telemt_upstream_connect_success_total 20461
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1217
telemt_me_reconnect_attempts_total 16964
telemt_me_reconnect_success_total 15716
telemt_me_reader_eof_total 16607
telemt_me_idle_close_by_peer_total 16606
telemt_me_route_drop_no_conn_total 540113
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272670
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4958
telemt_desync_full_logged_total 1522
telemt_desync_suppressed_total 3436
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1793
telemt_desync_frames_bucket_total{bucket="gt_10"} 2375
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15864
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15675
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 1272276
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 19661202088 (18.31 GB)
telemt_user_octets_to_client{user="hello"} 471422422625 (439.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87554.0 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1010283
telemt_connections_bad_total 12997
telemt_handshake_timeouts_total 71185
telemt_upstream_connect_attempt_total 22369
telemt_upstream_connect_success_total 22278
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1682
telemt_me_reconnect_attempts_total 25624
telemt_me_reconnect_success_total 17895
telemt_me_reader_eof_total 19122
telemt_me_idle_close_by_peer_total 19122
telemt_me_route_drop_no_conn_total 361576
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18279
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17874
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 384
telemt_user_connections_total{user="hello"} 878851
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 14164776612 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 352285417088 (328.09 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87554.1 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129528
telemt_connections_bad_total 12533
telemt_handshake_timeouts_total 9109
telemt_upstream_connect_attempt_total 26872
telemt_upstream_connect_success_total 26536
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 26872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1439
telemt_me_reconnect_attempts_total 33178
telemt_me_reconnect_success_total 22139
telemt_me_reader_eof_total 23273
telemt_me_idle_close_by_peer_total 23273
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 423161
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1039385
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3901
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 2543
telemt_desync_frames_bucket_total{bucket="1_2"} 1146
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22739
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22095
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 1039247
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 12807759356 (11.93 GB)
telemt_user_octets_to_client{user="hello"} 368512242192 (343.20 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 54
```