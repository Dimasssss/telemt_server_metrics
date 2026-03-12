# Server Metrics 2026-03-12 21:48:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 57014.6 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1888097
telemt_connections_bad_total 26055
telemt_handshake_timeouts_total 20703
telemt_upstream_connect_attempt_total 11163
telemt_upstream_connect_success_total 11098
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 11163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 593
telemt_me_reconnect_attempts_total 17067
telemt_me_reconnect_success_total 8214
telemt_me_reader_eof_total 8876
telemt_me_idle_close_by_peer_total 8875
telemt_me_route_drop_no_conn_total 738955
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1757245
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8448
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 6254
telemt_desync_frames_bucket_total{bucket="1_2"} 2221
telemt_desync_frames_bucket_total{bucket="3_10"} 3041
telemt_desync_frames_bucket_total{bucket="gt_10"} 3186
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8609
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8201
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 1756725
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 26781837424 (24.94 GB)
telemt_user_octets_to_client{user="hello"} 620627655744 (578.00 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86635.1 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 785359
telemt_connections_bad_total 11689
telemt_handshake_timeouts_total 31094
telemt_upstream_connect_attempt_total 21892
telemt_upstream_connect_success_total 21862
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3399
telemt_me_reconnect_attempts_total 15965
telemt_me_reconnect_success_total 15871
telemt_me_reader_eof_total 16888
telemt_me_idle_close_by_peer_total 16888
telemt_me_route_drop_no_conn_total 254473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 708856
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2988
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 2062
telemt_desync_frames_bucket_total{bucket="1_2"} 1179
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16033
telemt_me_writer_restored_same_endpoint_total 15862
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 710734
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 12003009560 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 272231163147 (253.54 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 86634.9 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1627650
telemt_connections_bad_total 7736
telemt_handshake_timeouts_total 113010
telemt_upstream_connect_attempt_total 20266
telemt_upstream_connect_success_total 20260
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1214
telemt_me_reconnect_attempts_total 16806
telemt_me_reconnect_success_total 15558
telemt_me_reader_eof_total 16437
telemt_me_idle_close_by_peer_total 16436
telemt_me_route_drop_no_conn_total 537072
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1262158
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4954
telemt_desync_full_logged_total 1519
telemt_desync_suppressed_total 3435
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1790
telemt_desync_frames_bucket_total{bucket="gt_10"} 2374
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15704
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15517
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1261764
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 19606599696 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 468527267889 (436.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 86635.4 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003369
telemt_connections_bad_total 12988
telemt_handshake_timeouts_total 71123
telemt_upstream_connect_attempt_total 22108
telemt_upstream_connect_success_total 22017
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1678
telemt_me_reconnect_attempts_total 25406
telemt_me_reconnect_success_total 17677
telemt_me_reader_eof_total 18887
telemt_me_idle_close_by_peer_total 18887
telemt_me_route_drop_no_conn_total 359011
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 873392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1231
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18059
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17656
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 872741
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 13918862336 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 350057122560 (326.02 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86635.2 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1122499
telemt_connections_bad_total 12521
telemt_handshake_timeouts_total 9081
telemt_upstream_connect_attempt_total 26658
telemt_upstream_connect_success_total 26330
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 33015
telemt_me_reconnect_success_total 21977
telemt_me_reader_eof_total 23107
telemt_me_idle_close_by_peer_total 23107
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 420858
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032472
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3885
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2533
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1280
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22573
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21933
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1032337
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 12760755056 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 364716982432 (339.67 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 61
```