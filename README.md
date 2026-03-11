# Server Metrics 2026-03-11 17:29:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97363.3 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2453067
telemt_connections_bad_total 46086
telemt_handshake_timeouts_total 54701
telemt_upstream_connect_attempt_total 20474
telemt_upstream_connect_success_total 20462
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5204
telemt_me_reconnect_attempts_total 33393
telemt_me_reconnect_success_total 15516
telemt_me_reader_eof_total 16811
telemt_me_idle_close_by_peer_total 16811
telemt_me_route_drop_no_conn_total 913098
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2243080
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11529
telemt_desync_full_logged_total 3166
telemt_desync_suppressed_total 8363
telemt_desync_frames_bucket_total{bucket="1_2"} 2840
telemt_desync_frames_bucket_total{bucket="3_10"} 4456
telemt_desync_frames_bucket_total{bucket="gt_10"} 4233
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16248
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15510
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 2241527
telemt_user_connections_current{user="hello"} 1260
telemt_user_octets_from_client{user="hello"} 30640880540 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 632506928048 (589.07 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97420.1 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 919958
telemt_connections_bad_total 16330
telemt_handshake_timeouts_total 77552
telemt_upstream_connect_attempt_total 30680
telemt_upstream_connect_success_total 27718
telemt_upstream_connect_fail_total 2962
telemt_upstream_connect_attempts_per_request{bucket="1"} 30680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2962
telemt_me_keepalive_timeout_total 2757
telemt_me_reconnect_attempts_total 21958
telemt_me_reconnect_success_total 19852
telemt_me_reader_eof_total 21009
telemt_me_idle_close_by_peer_total 21006
telemt_me_route_drop_no_conn_total 349582
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 769887
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3044
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2075
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1092
telemt_desync_frames_bucket_total{bucket="gt_10"} 1029
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20128
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19829
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 772348
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 9276720198 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 218894540060 (203.86 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97420.0 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1573499
telemt_connections_bad_total 9538
telemt_handshake_timeouts_total 127107
telemt_upstream_connect_attempt_total 25303
telemt_upstream_connect_success_total 24982
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1885
telemt_me_reconnect_attempts_total 44971
telemt_me_reconnect_success_total 18969
telemt_me_reader_eof_total 20608
telemt_me_idle_close_by_peer_total 20608
telemt_me_route_drop_no_conn_total 573970
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1376048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3676
telemt_desync_full_logged_total 1072
telemt_desync_suppressed_total 2604
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1398
telemt_desync_frames_bucket_total{bucket="gt_10"} 1383
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 20043
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 18957
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 1375740
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 16980393701 (15.81 GB)
telemt_user_octets_to_client{user="hello"} 418163514689 (389.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97420.5 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127313
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 106776
telemt_upstream_connect_attempt_total 26267
telemt_upstream_connect_success_total 26267
telemt_upstream_connect_attempts_per_request{bucket="1"} 26267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1253
telemt_me_reconnect_attempts_total 23518
telemt_me_reconnect_success_total 21378
telemt_me_reader_eof_total 22661
telemt_me_idle_close_by_peer_total 22660
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 372555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908924
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1910
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21673
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21346
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 908201
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 10931453496 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 276893598236 (257.88 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2096.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39486
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 558
telemt_upstream_connect_success_total 558
telemt_upstream_connect_attempts_per_request{bucket="1"} 558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 400
telemt_me_reconnect_success_total 396
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 12004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36896
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 94
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_me_writer_removed_unexpected_total 384
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 36896
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 4953310032 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 10091665268 (9.40 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 97
```