# Server Metrics 2026-03-13 07:50:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93130.0 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2573974
telemt_connections_bad_total 36171
telemt_handshake_timeouts_total 26906
telemt_upstream_connect_attempt_total 18144
telemt_upstream_connect_success_total 18043
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 22285
telemt_me_reconnect_success_total 13412
telemt_me_reader_eof_total 14460
telemt_me_idle_close_by_peer_total 14459
telemt_me_route_drop_no_conn_total 963288
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2355120
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10608
telemt_desync_full_logged_total 2735
telemt_desync_suppressed_total 7873
telemt_desync_frames_bucket_total{bucket="1_2"} 2703
telemt_desync_frames_bucket_total{bucket="3_10"} 3932
telemt_desync_frames_bucket_total{bucket="gt_10"} 3973
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13876
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13399
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2354612
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 33570429588 (31.26 GB)
telemt_user_octets_to_client{user="hello"} 789827650468 (735.58 GB)
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 122750.4 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038293
telemt_connections_bad_total 13320
telemt_handshake_timeouts_total 66229
telemt_upstream_connect_attempt_total 30771
telemt_upstream_connect_success_total 30740
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3624
telemt_me_reconnect_attempts_total 23114
telemt_me_reconnect_success_total 22994
telemt_me_reader_eof_total 24508
telemt_me_idle_close_by_peer_total 24508
telemt_me_route_drop_no_conn_total 325118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 918624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4045
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 2806
telemt_desync_frames_bucket_total{bucket="1_2"} 1524
telemt_desync_frames_bucket_total{bucket="3_10"} 1307
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23219
telemt_me_writer_restored_same_endpoint_total 22985
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 920554
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 14136714852 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 344505917323 (320.85 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 122750.1 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2077783
telemt_connections_bad_total 23395
telemt_handshake_timeouts_total 139428
telemt_upstream_connect_attempt_total 28230
telemt_upstream_connect_success_total 28220
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1740
telemt_me_reconnect_attempts_total 23037
telemt_me_reconnect_success_total 21758
telemt_me_reader_eof_total 23052
telemt_me_idle_close_by_peer_total 23051
telemt_me_route_drop_no_conn_total 669223
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1648668
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5575
telemt_desync_full_logged_total 1736
telemt_desync_suppressed_total 3839
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 2028
telemt_desync_frames_bucket_total{bucket="gt_10"} 2628
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 21970
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21717
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 1648146
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 27434575944 (25.55 GB)
telemt_user_octets_to_client{user="hello"} 599437149401 (558.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 122750.8 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287861
telemt_connections_bad_total 14147
telemt_handshake_timeouts_total 81878
telemt_upstream_connect_attempt_total 41277
telemt_upstream_connect_success_total 38979
telemt_upstream_connect_fail_total 2161
telemt_upstream_connect_attempts_per_request{bucket="1"} 41003
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2160
telemt_me_keepalive_timeout_total 11439
telemt_me_reconnect_attempts_total 35944
telemt_me_reconnect_success_total 27006
telemt_me_reader_eof_total 29084
telemt_me_idle_close_by_peer_total 29077
telemt_me_route_drop_no_conn_total 461796
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1098033
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2167
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1463
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27471
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26982
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1102776
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 16743228321 (15.59 GB)
telemt_user_octets_to_client{user="hello"} 437069256162 (407.05 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 122750.4 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1448174
telemt_connections_bad_total 26502
telemt_handshake_timeouts_total 12118
telemt_upstream_connect_attempt_total 38771
telemt_upstream_connect_success_total 38300
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2124
telemt_me_reconnect_attempts_total 45934
telemt_me_reconnect_success_total 32195
telemt_me_reader_eof_total 33798
telemt_me_idle_close_by_peer_total 33798
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 531581
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1331307
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4708
telemt_desync_full_logged_total 1678
telemt_desync_suppressed_total 3030
telemt_desync_frames_bucket_total{bucket="1_2"} 1437
telemt_desync_frames_bucket_total{bucket="3_10"} 1516
telemt_desync_frames_bucket_total{bucket="gt_10"} 1755
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 32977
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32139
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1331115
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 16884261588 (15.72 GB)
telemt_user_octets_to_client{user="hello"} 455822692904 (424.52 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 126
```