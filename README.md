# Server Metrics 2026-03-13 05:48:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85780.6 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306998
telemt_connections_bad_total 34645
telemt_handshake_timeouts_total 24322
telemt_upstream_connect_attempt_total 16899
telemt_upstream_connect_success_total 16806
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1316
telemt_me_reconnect_attempts_total 21392
telemt_me_reconnect_success_total 12523
telemt_me_reader_eof_total 13510
telemt_me_idle_close_by_peer_total 13509
telemt_me_route_drop_no_conn_total 876452
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2121871
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9408
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 6977
telemt_desync_frames_bucket_total{bucket="1_2"} 2442
telemt_desync_frames_bucket_total{bucket="3_10"} 3443
telemt_desync_frames_bucket_total{bucket="gt_10"} 3523
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 12972
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12510
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 2121222
telemt_user_connections_current{user="hello"} 1121
telemt_user_octets_from_client{user="hello"} 30663139560 (28.56 GB)
telemt_user_octets_to_client{user="hello"} 727853832776 (677.87 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 115401.3 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934493
telemt_connections_bad_total 12439
telemt_handshake_timeouts_total 40560
telemt_upstream_connect_attempt_total 29170
telemt_upstream_connect_success_total 29139
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3557
telemt_me_reconnect_attempts_total 21861
telemt_me_reconnect_success_total 21743
telemt_me_reader_eof_total 23188
telemt_me_idle_close_by_peer_total 23188
telemt_me_route_drop_no_conn_total 297348
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843084
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3404
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2333
telemt_desync_frames_bucket_total{bucket="1_2"} 1331
telemt_desync_frames_bucket_total{bucket="3_10"} 1114
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 21959
telemt_me_writer_restored_same_endpoint_total 21734
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 844985
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 13366594776 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 321674089539 (299.58 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 115401.0 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931297
telemt_connections_bad_total 21689
telemt_handshake_timeouts_total 126952
telemt_upstream_connect_attempt_total 26831
telemt_upstream_connect_success_total 26821
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1663
telemt_me_reconnect_attempts_total 21985
telemt_me_reconnect_success_total 20714
telemt_me_reader_eof_total 21946
telemt_me_idle_close_by_peer_total 21945
telemt_me_route_drop_no_conn_total 619475
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520643
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5288
telemt_desync_full_logged_total 1605
telemt_desync_suppressed_total 3683
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1920
telemt_desync_frames_bucket_total{bucket="gt_10"} 2495
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20914
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20673
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 1520139
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 26112311404 (24.32 GB)
telemt_user_octets_to_client{user="hello"} 541559254433 (504.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 115401.5 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179476
telemt_connections_bad_total 13986
telemt_handshake_timeouts_total 77098
telemt_upstream_connect_attempt_total 39421
telemt_upstream_connect_success_total 37133
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39147
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11404
telemt_me_reconnect_attempts_total 34447
telemt_me_reconnect_success_total 25513
telemt_me_reader_eof_total 27521
telemt_me_idle_close_by_peer_total 27514
telemt_me_route_drop_no_conn_total 420691
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015520
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1990
telemt_desync_full_logged_total 654
telemt_desync_suppressed_total 1336
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 773
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 25966
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25489
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1020633
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 15545155101 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 407314920394 (379.34 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 115401.2 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326367
telemt_connections_bad_total 15022
telemt_handshake_timeouts_total 10817
telemt_upstream_connect_attempt_total 36457
telemt_upstream_connect_success_total 36015
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 36457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 1982
telemt_me_reconnect_attempts_total 43994
telemt_me_reconnect_success_total 30260
telemt_me_reader_eof_total 31787
telemt_me_idle_close_by_peer_total 31787
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 489054
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1226526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4431
telemt_desync_full_logged_total 1592
telemt_desync_suppressed_total 2839
telemt_desync_frames_bucket_total{bucket="1_2"} 1344
telemt_desync_frames_bucket_total{bucket="3_10"} 1438
telemt_desync_frames_bucket_total{bucket="gt_10"} 1649
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31023
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30208
telemt_me_writer_restored_fallback_total 52
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1226371
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 14791412756 (13.78 GB)
telemt_user_octets_to_client{user="hello"} 415875019260 (387.31 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```