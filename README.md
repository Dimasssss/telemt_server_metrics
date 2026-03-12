# Server Metrics 2026-03-12 16:16:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37097.2 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1340564
telemt_connections_bad_total 20239
telemt_handshake_timeouts_total 12902
telemt_upstream_connect_attempt_total 7432
telemt_upstream_connect_success_total 7392
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 7432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 9397
telemt_me_reconnect_success_total 5486
telemt_me_reader_eof_total 5838
telemt_me_idle_close_by_peer_total 5837
telemt_me_route_drop_no_conn_total 481373
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1256411
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6516
telemt_desync_full_logged_total 1633
telemt_desync_suppressed_total 4883
telemt_desync_frames_bucket_total{bucket="1_2"} 1681
telemt_desync_frames_bucket_total{bucket="3_10"} 2350
telemt_desync_frames_bucket_total{bucket="gt_10"} 2485
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5678
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5473
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 1256090
telemt_user_connections_current{user="hello"} 1507
telemt_user_octets_from_client{user="hello"} 19348716424 (18.02 GB)
telemt_user_octets_to_client{user="hello"} 363824565536 (338.84 GB)
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66717.9 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593236
telemt_connections_bad_total 7798
telemt_handshake_timeouts_total 27758
telemt_upstream_connect_attempt_total 15938
telemt_upstream_connect_success_total 15931
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1256
telemt_me_reconnect_attempts_total 12467
telemt_me_reconnect_success_total 12396
telemt_me_reader_eof_total 13177
telemt_me_idle_close_by_peer_total 13177
telemt_me_route_drop_no_conn_total 177455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531129
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2082
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 922
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12519
telemt_me_writer_restored_same_endpoint_total 12387
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 531627
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 8214928255 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 187857683314 (174.96 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66717.7 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252301
telemt_connections_bad_total 6364
telemt_handshake_timeouts_total 88980
telemt_upstream_connect_attempt_total 16036
telemt_upstream_connect_success_total 16031
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1062
telemt_me_reconnect_attempts_total 13544
telemt_me_reconnect_success_total 12315
telemt_me_reader_eof_total 12985
telemt_me_idle_close_by_peer_total 12984
telemt_me_route_drop_no_conn_total 343443
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930790
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3983
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2765
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1436
telemt_desync_frames_bucket_total{bucket="gt_10"} 1930
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12405
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12274
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 930963
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 12156602328 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 292236409025 (272.17 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66718.1 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747882
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 59708
telemt_upstream_connect_attempt_total 17566
telemt_upstream_connect_success_total 17496
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1479
telemt_me_reconnect_attempts_total 19382
telemt_me_reconnect_success_total 14138
telemt_me_reader_eof_total 15059
telemt_me_idle_close_by_peer_total 15059
telemt_me_route_drop_no_conn_total 255468
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645218
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1261
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14408
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14117
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 644676
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 8052241376 (7.50 GB)
telemt_user_octets_to_client{user="hello"} 251913149068 (234.61 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66718.1 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845783
telemt_connections_bad_total 10013
telemt_handshake_timeouts_total 6966
telemt_upstream_connect_attempt_total 20932
telemt_upstream_connect_success_total 20678
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 20932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 1197
telemt_me_reconnect_attempts_total 24577
telemt_me_reconnect_success_total 17334
telemt_me_reader_eof_total 18153
telemt_me_idle_close_by_peer_total 18153
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 297839
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777761
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3026
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 1144
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17744
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17295
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 777656
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 9493871748 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 218985052928 (203.95 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 123
```