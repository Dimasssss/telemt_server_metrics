# Server Metrics 2026-03-10 21:12:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24341.6 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683716
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 8036
telemt_upstream_connect_attempt_total 5294
telemt_upstream_connect_success_total 5285
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 349
telemt_me_reconnect_attempts_total 15656
telemt_me_reconnect_success_total 3999
telemt_me_reader_eof_total 4413
telemt_me_idle_close_by_peer_total 4413
telemt_me_route_drop_no_conn_total 285807
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645669
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3286
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 2381
telemt_desync_frames_bucket_total{bucket="1_2"} 925
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 4390
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3993
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 645478
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 9178396652 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 196340315532 (182.86 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24398.3 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300077
telemt_connections_bad_total 1888
telemt_handshake_timeouts_total 17188
telemt_upstream_connect_attempt_total 11613
telemt_upstream_connect_success_total 8751
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 11613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2030
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1342
telemt_me_reconnect_attempts_total 5321
telemt_me_reconnect_success_total 4518
telemt_me_reader_eof_total 4719
telemt_me_idle_close_by_peer_total 4717
telemt_me_route_drop_no_conn_total 160577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4599
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4497
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 253845
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2579548434 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 59995841328 (55.88 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 24398.3 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486876
telemt_connections_bad_total 2744
telemt_handshake_timeouts_total 33394
telemt_upstream_connect_attempt_total 6959
telemt_upstream_connect_success_total 6849
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 6959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 15540
telemt_me_reconnect_success_total 4497
telemt_me_reader_eof_total 4966
telemt_me_idle_close_by_peer_total 4966
telemt_me_route_drop_no_conn_total 169052
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424414
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1387
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 1002
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 477
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4918
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4486
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 425351
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 6207474273 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 136169832089 (126.82 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 24398.7 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333587
telemt_connections_bad_total 23749
telemt_handshake_timeouts_total 28655
telemt_upstream_connect_attempt_total 6546
telemt_upstream_connect_success_total 6546
telemt_upstream_connect_attempts_per_request{bucket="1"} 6546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 6282
telemt_me_reconnect_success_total 5261
telemt_me_reader_eof_total 5521
telemt_me_idle_close_by_peer_total 5521
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 108215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268784
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5349
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5248
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 268462
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 3916495772 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 82918344880 (77.22 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24398.5 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353664
telemt_connections_bad_total 1051
telemt_handshake_timeouts_total 2248
telemt_upstream_connect_attempt_total 7527
telemt_upstream_connect_success_total 7497
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 9944
telemt_me_reconnect_success_total 6191
telemt_me_reader_eof_total 6485
telemt_me_idle_close_by_peer_total 6485
telemt_me_route_drop_no_conn_total 126998
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332046
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1943
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6398
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6191
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 331930
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 6243193680 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 115071074144 (107.17 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```