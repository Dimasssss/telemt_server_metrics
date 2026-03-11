# Server Metrics 2026-03-11 03:44:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47819.1 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918855
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 24298
telemt_upstream_connect_attempt_total 10345
telemt_upstream_connect_success_total 10336
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 19544
telemt_me_reconnect_success_total 7873
telemt_me_reader_eof_total 8588
telemt_me_idle_close_by_peer_total 8588
telemt_me_route_drop_no_conn_total 356001
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844529
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3900
telemt_desync_full_logged_total 1083
telemt_desync_suppressed_total 2817
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1465
telemt_desync_frames_bucket_total{bucket="gt_10"} 1327
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8308
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7867
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 844252
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 11230895364 (10.46 GB)
telemt_user_octets_to_client{user="hello"} 251054303180 (233.81 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47875.7 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375578
telemt_connections_bad_total 2530
telemt_handshake_timeouts_total 18575
telemt_upstream_connect_attempt_total 18409
telemt_upstream_connect_success_total 15517
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1763
telemt_me_reconnect_attempts_total 10955
telemt_me_reconnect_success_total 10137
telemt_me_reader_eof_total 10712
telemt_me_idle_close_by_peer_total 10710
telemt_me_route_drop_no_conn_total 181239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321965
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1812
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 10256
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10116
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 324231
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 3085968154 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 76127814132 (70.90 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47875.5 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629846
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 35179
telemt_upstream_connect_attempt_total 12944
telemt_upstream_connect_success_total 12774
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 12944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 552
telemt_me_reconnect_attempts_total 20336
telemt_me_reconnect_success_total 9267
telemt_me_reader_eof_total 10059
telemt_me_idle_close_by_peer_total 10059
telemt_me_route_drop_no_conn_total 213273
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560135
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1626
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9737
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9256
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 561029
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 7146157389 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 170247451521 (158.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47876.0 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475695
telemt_connections_bad_total 45175
telemt_handshake_timeouts_total 47517
telemt_upstream_connect_attempt_total 13981
telemt_upstream_connect_success_total 13981
telemt_upstream_connect_attempts_per_request{bucket="1"} 13981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 12591
telemt_me_reconnect_success_total 11552
telemt_me_reader_eof_total 12270
telemt_me_idle_close_by_peer_total 12270
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 141631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369140
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11688
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11533
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 368807
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 4495778564 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 98096502748 (91.36 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47875.6 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502463
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3124
telemt_upstream_connect_attempt_total 14010
telemt_upstream_connect_success_total 13952
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 15259
telemt_me_reconnect_success_total 11479
telemt_me_reader_eof_total 12119
telemt_me_idle_close_by_peer_total 12119
telemt_me_route_drop_no_conn_total 160916
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457160
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2360
telemt_desync_full_logged_total 920
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 11742
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11479
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 456803
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 8640859492 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 162870482856 (151.68 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```