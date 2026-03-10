# Server Metrics 2026-03-10 21:33:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25562.2 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698810
telemt_connections_bad_total 8152
telemt_handshake_timeouts_total 8127
telemt_upstream_connect_attempt_total 5563
telemt_upstream_connect_success_total 5554
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 351
telemt_me_reconnect_attempts_total 15843
telemt_me_reconnect_success_total 4185
telemt_me_reader_eof_total 4632
telemt_me_idle_close_by_peer_total 4632
telemt_me_route_drop_no_conn_total 291383
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660378
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3325
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1254
telemt_desync_frames_bucket_total{bucket="gt_10"} 1128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4579
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4179
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 660183
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 9568929660 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 200079231056 (186.34 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25618.9 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306044
telemt_connections_bad_total 1934
telemt_handshake_timeouts_total 17247
telemt_upstream_connect_attempt_total 11935
telemt_upstream_connect_success_total 9073
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 5596
telemt_me_reconnect_success_total 4792
telemt_me_reader_eof_total 5024
telemt_me_idle_close_by_peer_total 5022
telemt_me_route_drop_no_conn_total 162572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257161
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1499
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4874
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4771
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 259434
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 2607736398 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 61366184908 (57.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25618.7 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499769
telemt_connections_bad_total 2871
telemt_handshake_timeouts_total 33554
telemt_upstream_connect_attempt_total 7256
telemt_upstream_connect_success_total 7142
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 15785
telemt_me_reconnect_success_total 4738
telemt_me_reader_eof_total 5227
telemt_me_idle_close_by_peer_total 5227
telemt_me_route_drop_no_conn_total 173327
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435334
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1416
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 609
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5159
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4727
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 436267
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 6364420433 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 141693098437 (131.96 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25619.1 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344847
telemt_connections_bad_total 24872
telemt_handshake_timeouts_total 30108
telemt_upstream_connect_attempt_total 6906
telemt_upstream_connect_success_total 6906
telemt_upstream_connect_attempts_per_request{bucket="1"} 6906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 6597
telemt_me_reconnect_success_total 5575
telemt_me_reader_eof_total 5853
telemt_me_idle_close_by_peer_total 5853
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 112768
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277289
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5671
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5562
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 276967
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 3968272140 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 84402549300 (78.61 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25618.9 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364301
telemt_connections_bad_total 1116
telemt_handshake_timeouts_total 2315
telemt_upstream_connect_attempt_total 7923
telemt_upstream_connect_success_total 7893
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 10287
telemt_me_reconnect_success_total 6533
telemt_me_reader_eof_total 6847
telemt_me_idle_close_by_peer_total 6847
telemt_me_route_drop_no_conn_total 129685
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341595
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2045
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1286
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6743
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6533
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 341463
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 6320270328 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 118721767616 (110.57 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 53
```