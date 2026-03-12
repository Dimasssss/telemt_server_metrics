# Server Metrics 2026-03-12 20:42:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53034.8 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1814896
telemt_connections_bad_total 20723
telemt_handshake_timeouts_total 19957
telemt_upstream_connect_attempt_total 10286
telemt_upstream_connect_success_total 10225
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 16409
telemt_me_reconnect_success_total 7559
telemt_me_reader_eof_total 8177
telemt_me_idle_close_by_peer_total 8176
telemt_me_route_drop_no_conn_total 713789
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1694032
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8313
telemt_desync_full_logged_total 2145
telemt_desync_suppressed_total 6168
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 2996
telemt_desync_frames_bucket_total{bucket="gt_10"} 3135
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7944
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7546
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 1693515
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 26016924824 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 592074030204 (551.41 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82655.4 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763233
telemt_connections_bad_total 11029
telemt_handshake_timeouts_total 30422
telemt_upstream_connect_attempt_total 20907
telemt_upstream_connect_success_total 20878
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3387
telemt_me_reconnect_attempts_total 15195
telemt_me_reconnect_success_total 15104
telemt_me_reader_eof_total 16058
telemt_me_idle_close_by_peer_total 16058
telemt_me_route_drop_no_conn_total 245381
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688636
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2938
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 2037
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15257
telemt_me_writer_restored_same_endpoint_total 15095
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 690508
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 11772207604 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 263108975275 (245.04 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82655.2 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1576290
telemt_connections_bad_total 7539
telemt_handshake_timeouts_total 108096
telemt_upstream_connect_attempt_total 19383
telemt_upstream_connect_success_total 19377
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1205
telemt_me_reconnect_attempts_total 16139
telemt_me_reconnect_success_total 14892
telemt_me_reader_eof_total 15716
telemt_me_idle_close_by_peer_total 15715
telemt_me_route_drop_no_conn_total 520707
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1216700
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4830
telemt_desync_full_logged_total 1485
telemt_desync_suppressed_total 3345
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 1747
telemt_desync_frames_bucket_total{bucket="gt_10"} 2314
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15031
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14851
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 1216308
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 19144327992 (17.83 GB)
telemt_user_octets_to_client{user="hello"} 453863145725 (422.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82655.7 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969188
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70719
telemt_upstream_connect_attempt_total 21080
telemt_upstream_connect_success_total 20997
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 21080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1671
telemt_me_reconnect_attempts_total 24603
telemt_me_reconnect_success_total 16877
telemt_me_reader_eof_total 18027
telemt_me_idle_close_by_peer_total 18027
telemt_me_route_drop_no_conn_total 345626
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 841763
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1800
telemt_desync_full_logged_total 596
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17253
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16856
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 841113
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 13139563800 (12.24 GB)
telemt_user_octets_to_client{user="hello"} 343984787336 (320.36 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82655.5 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087657
telemt_connections_bad_total 12434
telemt_handshake_timeouts_total 8970
telemt_upstream_connect_attempt_total 25626
telemt_upstream_connect_success_total 25315
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 25626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1422
telemt_me_reconnect_attempts_total 32215
telemt_me_reconnect_success_total 21177
telemt_me_reader_eof_total 22253
telemt_me_idle_close_by_peer_total 22253
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 406953
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998490
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3737
telemt_desync_full_logged_total 1308
telemt_desync_suppressed_total 2429
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 1240
telemt_desync_frames_bucket_total{bucket="gt_10"} 1419
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 21764
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21133
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 998354
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 12432041728 (11.58 GB)
telemt_user_octets_to_client{user="hello"} 352035948336 (327.86 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 63
```