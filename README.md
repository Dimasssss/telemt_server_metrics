# Server Metrics 2026-03-12 17:28:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41388.7 (11h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1496406
telemt_connections_bad_total 20278
telemt_handshake_timeouts_total 14028
telemt_upstream_connect_attempt_total 8160
telemt_upstream_connect_success_total 8112
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 14865
telemt_me_reconnect_success_total 6022
telemt_me_reader_eof_total 6538
telemt_me_idle_close_by_peer_total 6537
telemt_me_route_drop_no_conn_total 580300
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7083
telemt_desync_full_logged_total 1792
telemt_desync_suppressed_total 5291
telemt_desync_frames_bucket_total{bucket="1_2"} 1845
telemt_desync_frames_bucket_total{bucket="3_10"} 2556
telemt_desync_frames_bucket_total{bucket="gt_10"} 2682
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6381
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6009
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1402194
telemt_user_connections_current{user="hello"} 1795
telemt_user_octets_from_client{user="hello"} 21465860064 (19.99 GB)
telemt_user_octets_to_client{user="hello"} 432343959616 (402.65 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71007.9 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650405
telemt_connections_bad_total 8603
telemt_handshake_timeouts_total 28961
telemt_upstream_connect_attempt_total 16856
telemt_upstream_connect_success_total 16849
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1353
telemt_me_reconnect_attempts_total 13208
telemt_me_reconnect_success_total 13131
telemt_me_reader_eof_total 13959
telemt_me_idle_close_by_peer_total 13959
telemt_me_route_drop_no_conn_total 202344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584529
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2409
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1666
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 13264
telemt_me_writer_restored_same_endpoint_total 13122
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 585074
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 8967496323 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 215982416022 (201.15 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71007.8 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357112
telemt_connections_bad_total 6673
telemt_handshake_timeouts_total 97029
telemt_upstream_connect_attempt_total 16899
telemt_upstream_connect_success_total 16894
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 14229
telemt_me_reconnect_success_total 12992
telemt_me_reader_eof_total 13699
telemt_me_idle_close_by_peer_total 13698
telemt_me_route_drop_no_conn_total 439779
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1024411
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4359
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 3009
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 2102
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13095
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12951
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 1024254
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 15257738724 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 352604473293 (328.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71008.3 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819069
telemt_connections_bad_total 9201
telemt_handshake_timeouts_total 63024
telemt_upstream_connect_attempt_total 18499
telemt_upstream_connect_success_total 18428
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 20136
telemt_me_reconnect_success_total 14883
telemt_me_reader_eof_total 15844
telemt_me_idle_close_by_peer_total 15844
telemt_me_route_drop_no_conn_total 286157
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709579
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1055
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15163
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14862
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 708996
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 8746096236 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 285193786172 (265.61 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71008.1 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924549
telemt_connections_bad_total 11398
telemt_handshake_timeouts_total 7564
telemt_upstream_connect_attempt_total 22643
telemt_upstream_connect_success_total 22373
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 22643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1291
telemt_me_reconnect_attempts_total 27499
telemt_me_reconnect_success_total 18809
telemt_me_reader_eof_total 19693
telemt_me_idle_close_by_peer_total 19693
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 338882
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848804
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3332
telemt_desync_full_logged_total 1140
telemt_desync_suppressed_total 2192
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1140
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19287
telemt_me_refill_failed_total 269
telemt_me_writer_restored_same_endpoint_total 18765
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 848686
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 10399232420 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 259761734360 (241.92 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 110
```