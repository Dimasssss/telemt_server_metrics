# Server Metrics 2026-03-13 12:52:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111246.4 (30h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3327850
telemt_connections_bad_total 37359
telemt_handshake_timeouts_total 57684
telemt_upstream_connect_attempt_total 21917
telemt_upstream_connect_success_total 21796
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2104
telemt_me_reconnect_attempts_total 26340
telemt_me_reconnect_success_total 16257
telemt_me_reader_eof_total 17477
telemt_me_idle_close_by_peer_total 17476
telemt_me_route_drop_no_conn_total 1233338
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3051318
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12833
telemt_desync_full_logged_total 3335
telemt_desync_suppressed_total 9498
telemt_desync_frames_bucket_total{bucket="1_2"} 3262
telemt_desync_frames_bucket_total{bucket="3_10"} 4850
telemt_desync_frames_bucket_total{bucket="gt_10"} 4721
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16798
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16244
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 3051223
telemt_user_connections_current{user="hello"} 1918
telemt_user_octets_from_client{user="hello"} 42305211620 (39.40 GB)
telemt_user_octets_to_client{user="hello"} 983877872900 (916.31 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10910.2 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149056
telemt_connections_bad_total 8935
telemt_handshake_timeouts_total 3546
telemt_upstream_connect_attempt_total 2674
telemt_upstream_connect_success_total 2600
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 3211
telemt_me_reconnect_success_total 1984
telemt_me_reader_eof_total 2082
telemt_me_idle_close_by_peer_total 2082
telemt_me_route_drop_no_conn_total 52942
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132927
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2037
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1977
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 132952
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 1336924476 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 35935854476 (33.47 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 140867.0 (39h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2517276
telemt_connections_bad_total 26334
telemt_handshake_timeouts_total 165634
telemt_upstream_connect_attempt_total 32041
telemt_upstream_connect_success_total 32031
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3180
telemt_me_reconnect_attempts_total 27216
telemt_me_reconnect_success_total 24670
telemt_me_reader_eof_total 26153
telemt_me_idle_close_by_peer_total 26152
telemt_me_route_drop_no_conn_total 842425
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2046769
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6905
telemt_desync_full_logged_total 2232
telemt_desync_suppressed_total 4673
telemt_desync_frames_bucket_total{bucket="1_2"} 1086
telemt_desync_frames_bucket_total{bucket="3_10"} 2534
telemt_desync_frames_bucket_total{bucket="gt_10"} 3285
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 24954
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24629
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 2046180
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 34472882984 (32.11 GB)
telemt_user_octets_to_client{user="hello"} 737854555493 (687.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 140867.5 (39h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1605864
telemt_connections_bad_total 17872
telemt_handshake_timeouts_total 113272
telemt_upstream_connect_attempt_total 45386
telemt_upstream_connect_success_total 43066
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45112
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11827
telemt_me_reconnect_attempts_total 39158
telemt_me_reconnect_success_total 30193
telemt_me_reader_eof_total 32470
telemt_me_idle_close_by_peer_total 32463
telemt_me_route_drop_no_conn_total 570617
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1339510
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2632
telemt_desync_full_logged_total 860
telemt_desync_suppressed_total 1772
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1063
telemt_desync_frames_bucket_total{bucket="gt_10"} 863
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 30697
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30169
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1344232
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 20460489897 (19.06 GB)
telemt_user_octets_to_client{user="hello"} 524811678138 (488.77 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10303.0 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155912
telemt_connections_bad_total 3291
telemt_handshake_timeouts_total 1385
telemt_upstream_connect_attempt_total 2125
telemt_upstream_connect_success_total 2051
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9559
telemt_me_reconnect_success_total 1487
telemt_me_reader_eof_total 1731
telemt_me_idle_close_by_peer_total 1731
telemt_me_route_drop_no_conn_total 59959
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145590
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1733
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1483
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 145574
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 1645978380 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 46536103468 (43.34 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 126
```