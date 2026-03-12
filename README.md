# Server Metrics 2026-03-12 19:36:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49051.4 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1725723
telemt_connections_bad_total 20544
telemt_handshake_timeouts_total 17419
telemt_upstream_connect_attempt_total 9649
telemt_upstream_connect_success_total 9594
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 574
telemt_me_reconnect_attempts_total 15950
telemt_me_reconnect_success_total 7104
telemt_me_reader_eof_total 7691
telemt_me_idle_close_by_peer_total 7690
telemt_me_route_drop_no_conn_total 677937
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612051
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8101
telemt_desync_full_logged_total 2080
telemt_desync_suppressed_total 6021
telemt_desync_frames_bucket_total{bucket="1_2"} 2114
telemt_desync_frames_bucket_total{bucket="3_10"} 2922
telemt_desync_frames_bucket_total{bucket="gt_10"} 3065
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7482
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7091
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 1611545
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 25019612924 (23.30 GB)
telemt_user_octets_to_client{user="hello"} 552044177276 (514.13 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78671.8 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734399
telemt_connections_bad_total 10181
telemt_handshake_timeouts_total 29959
telemt_upstream_connect_attempt_total 19992
telemt_upstream_connect_success_total 19963
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3374
telemt_me_reconnect_attempts_total 14453
telemt_me_reconnect_success_total 14366
telemt_me_reader_eof_total 15276
telemt_me_idle_close_by_peer_total 15276
telemt_me_route_drop_no_conn_total 235393
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661854
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2862
telemt_desync_full_logged_total 877
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 14516
telemt_me_writer_restored_same_endpoint_total 14357
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 663730
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 11250345744 (10.48 GB)
telemt_user_octets_to_client{user="hello"} 250055873555 (232.88 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78671.7 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1518439
telemt_connections_bad_total 7273
telemt_handshake_timeouts_total 103875
telemt_upstream_connect_attempt_total 18592
telemt_upstream_connect_success_total 18587
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1187
telemt_me_reconnect_attempts_total 15520
telemt_me_reconnect_success_total 14275
telemt_me_reader_eof_total 15061
telemt_me_idle_close_by_peer_total 15060
telemt_me_route_drop_no_conn_total 499851
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1164270
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4778
telemt_desync_full_logged_total 1473
telemt_desync_suppressed_total 3305
telemt_desync_frames_bucket_total{bucket="1_2"} 755
telemt_desync_frames_bucket_total{bucket="3_10"} 1734
telemt_desync_frames_bucket_total{bucket="gt_10"} 2289
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14406
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14234
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 1164122
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 18159262536 (16.91 GB)
telemt_user_octets_to_client{user="hello"} 431582302953 (401.94 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78672.2 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 927158
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 67784
telemt_upstream_connect_attempt_total 20208
telemt_upstream_connect_success_total 20127
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1643
telemt_me_reconnect_attempts_total 23907
telemt_me_reconnect_success_total 16182
telemt_me_reader_eof_total 17287
telemt_me_idle_close_by_peer_total 17287
telemt_me_route_drop_no_conn_total 328936
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 803579
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16555
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16161
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 802936
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 12453333608 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 328507445348 (305.95 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78672.0 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1042644
telemt_connections_bad_total 12323
telemt_handshake_timeouts_total 8595
telemt_upstream_connect_attempt_total 24419
telemt_upstream_connect_success_total 24122
telemt_upstream_connect_fail_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 24419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 297
telemt_me_keepalive_timeout_total 1394
telemt_me_reconnect_attempts_total 31195
telemt_me_reconnect_success_total 20160
telemt_me_reader_eof_total 21185
telemt_me_idle_close_by_peer_total 21185
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 389942
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956093
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3570
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2319
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1189
telemt_desync_frames_bucket_total{bucket="gt_10"} 1363
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20731
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20116
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 955963
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 11835897712 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 325067430976 (302.74 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 78
```