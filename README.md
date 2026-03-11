# Server Metrics 2026-03-11 03:13:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45990.1 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886852
telemt_connections_bad_total 10066
telemt_handshake_timeouts_total 19879
telemt_upstream_connect_attempt_total 9950
telemt_upstream_connect_success_total 9941
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 515
telemt_me_reconnect_attempts_total 19248
telemt_me_reconnect_success_total 7577
telemt_me_reader_eof_total 8269
telemt_me_idle_close_by_peer_total 8269
telemt_me_route_drop_no_conn_total 349643
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823583
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3824
telemt_desync_full_logged_total 1061
telemt_desync_suppressed_total 2763
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 1436
telemt_desync_frames_bucket_total{bucket="gt_10"} 1290
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 8008
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7571
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 823314
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 11069654768 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 245788715884 (228.91 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46046.7 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367856
telemt_connections_bad_total 2434
telemt_handshake_timeouts_total 18387
telemt_upstream_connect_attempt_total 17920
telemt_upstream_connect_success_total 15028
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 17920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1756
telemt_me_reconnect_attempts_total 10553
telemt_me_reconnect_success_total 9736
telemt_me_reader_eof_total 10277
telemt_me_idle_close_by_peer_total 10275
telemt_me_route_drop_no_conn_total 179433
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315637
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1799
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 9853
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9715
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 317907
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2999493726 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 74885753128 (69.74 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46046.4 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616713
telemt_connections_bad_total 5337
telemt_handshake_timeouts_total 34765
telemt_upstream_connect_attempt_total 12493
telemt_upstream_connect_success_total 12329
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 19978
telemt_me_reconnect_success_total 8910
telemt_me_reader_eof_total 9673
telemt_me_idle_close_by_peer_total 9673
telemt_me_route_drop_no_conn_total 209048
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547616
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1600
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1129
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9375
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8899
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 548510
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 7086354373 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 167370203929 (155.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46046.8 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464005
telemt_connections_bad_total 43488
telemt_handshake_timeouts_total 45249
telemt_upstream_connect_attempt_total 13410
telemt_upstream_connect_success_total 13410
telemt_upstream_connect_attempts_per_request{bucket="1"} 13410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 464
telemt_me_reconnect_attempts_total 12106
telemt_me_reconnect_success_total 11068
telemt_me_reader_eof_total 11751
telemt_me_idle_close_by_peer_total 11751
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 138599
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361542
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11200
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11049
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 361210
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 4402661168 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 96315114452 (89.70 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46046.5 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489511
telemt_connections_bad_total 5810
telemt_handshake_timeouts_total 3057
telemt_upstream_connect_attempt_total 13521
telemt_upstream_connect_success_total 13463
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 537
telemt_me_reconnect_attempts_total 14856
telemt_me_reconnect_success_total 11078
telemt_me_reader_eof_total 11688
telemt_me_idle_close_by_peer_total 11688
telemt_me_route_drop_no_conn_total 157329
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445870
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2331
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 1423
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 11338
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11078
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 445525
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 8588312932 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 161320874392 (150.24 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 46
```