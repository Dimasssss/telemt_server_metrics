# Server Metrics 2026-03-15 02:25:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 15088.7 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183890
telemt_connections_bad_total 2319
telemt_handshake_timeouts_total 577
telemt_upstream_connect_attempt_total 3201
telemt_upstream_connect_success_total 3191
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 2439
telemt_me_reconnect_success_total 2426
telemt_me_reader_eof_total 2558
telemt_me_idle_close_by_peer_total 2558
telemt_me_route_drop_no_conn_total 56782
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162101
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2455
telemt_me_writer_restored_same_endpoint_total 2415
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 162088
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 1780224128 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 54345017272 (50.61 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 15089.2 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76624
telemt_connections_bad_total 13591
telemt_handshake_timeouts_total 3600
telemt_upstream_connect_attempt_total 4455
telemt_upstream_connect_success_total 4435
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 3378
telemt_me_reconnect_success_total 3358
telemt_me_reader_eof_total 3510
telemt_me_idle_close_by_peer_total 3510
telemt_me_route_drop_no_conn_total 14594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57447
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3336
telemt_me_writer_restored_same_endpoint_total 3350
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 57743
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 1544707351 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 16425818632 (15.30 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 15089.4 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126247
telemt_connections_bad_total 2361
telemt_handshake_timeouts_total 11784
telemt_upstream_connect_attempt_total 3522
telemt_upstream_connect_success_total 3505
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 2739
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 27146
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2768
telemt_me_writer_restored_same_endpoint_total 2720
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 109449
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1042149780 (993.87 MB)
telemt_user_octets_to_client{user="hello"} 36114557868 (33.63 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 15089.4 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106341
telemt_connections_bad_total 27590
telemt_handshake_timeouts_total 2635
telemt_upstream_connect_attempt_total 5636
telemt_upstream_connect_success_total 5516
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 5636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8296
telemt_me_reconnect_success_total 4748
telemt_me_reader_eof_total 4989
telemt_me_idle_close_by_peer_total 4989
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 20198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74465
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4899
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 4729
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 74468
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 438983056 (418.65 MB)
telemt_user_octets_to_client{user="hello"} 16070804988 (14.97 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 15090.2 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63466
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 3422
telemt_upstream_connect_success_total 3406
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2651
telemt_me_reconnect_success_total 2641
telemt_me_reader_eof_total 2796
telemt_me_idle_close_by_peer_total 2796
telemt_me_route_drop_no_conn_total 15950
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60861
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2661
telemt_me_writer_restored_same_endpoint_total 2633
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 60860
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 536491004 (511.64 MB)
telemt_user_octets_to_client{user="hello"} 20556198432 (19.14 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 29
```