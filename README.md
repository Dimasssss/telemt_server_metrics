# Server Metrics 2026-03-14 20:34:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 26207.0 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999265
telemt_connections_bad_total 41650
telemt_handshake_timeouts_total 14553
telemt_upstream_connect_attempt_total 4792
telemt_upstream_connect_success_total 4769
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 4205
telemt_me_reconnect_success_total 3398
telemt_me_reader_eof_total 3579
telemt_me_idle_close_by_peer_total 3579
telemt_me_route_drop_no_conn_total 382692
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887212
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3050
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 2185
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1122
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3479
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3389
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 887164
telemt_user_connections_current{user="hello"} 1558
telemt_user_octets_from_client{user="hello"} 15869036460 (14.78 GB)
telemt_user_octets_to_client{user="hello"} 300730998008 (280.08 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 26212.2 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392401
telemt_connections_bad_total 29301
telemt_handshake_timeouts_total 11904
telemt_upstream_connect_attempt_total 5660
telemt_upstream_connect_success_total 5602
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 5660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5024
telemt_me_reconnect_success_total 4229
telemt_me_reader_eof_total 4409
telemt_me_idle_close_by_peer_total 4409
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 116387
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328627
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1597
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4343
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4206
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 328560
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 4872568608 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 115161668008 (107.25 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 26075.1 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838180
telemt_connections_bad_total 3349
telemt_handshake_timeouts_total 193323
telemt_upstream_connect_attempt_total 5021
telemt_upstream_connect_success_total 5004
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 7597
telemt_me_reconnect_success_total 3686
telemt_me_reader_eof_total 3951
telemt_me_idle_close_by_peer_total 3951
telemt_me_route_drop_no_conn_total 193415
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546247
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2045
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1252
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3848
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3653
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 546075
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 8208504848 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 198111102728 (184.51 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 25929.7 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454330
telemt_connections_bad_total 98735
telemt_handshake_timeouts_total 53020
telemt_upstream_connect_attempt_total 5991
telemt_upstream_connect_success_total 5990
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 5600
telemt_me_reconnect_success_total 4679
telemt_me_reader_eof_total 4902
telemt_me_idle_close_by_peer_total 4902
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 104199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4763
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4667
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 294896
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 4201302588 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 91682800980 (85.39 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 26225.3 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381806
telemt_connections_bad_total 1372
telemt_handshake_timeouts_total 3915
telemt_upstream_connect_attempt_total 5601
telemt_upstream_connect_success_total 5490
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 5601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 4810
telemt_me_reconnect_success_total 4135
telemt_me_reader_eof_total 4362
telemt_me_idle_close_by_peer_total 4362
telemt_me_route_drop_no_conn_total 120895
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353978
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 895
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4231
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4117
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 353945
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 5743414860 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 150607779384 (140.26 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 58
```