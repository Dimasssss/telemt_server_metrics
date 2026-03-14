# Server Metrics 2026-03-14 04:42:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 168225.4 (46h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4777339
telemt_connections_bad_total 39900
telemt_handshake_timeouts_total 109948
telemt_upstream_connect_attempt_total 35460
telemt_upstream_connect_success_total 35228
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7298
telemt_me_reconnect_attempts_total 34681
telemt_me_reconnect_success_total 24538
telemt_me_reader_eof_total 26335
telemt_me_idle_close_by_peer_total 26334
telemt_me_route_drop_no_conn_total 1810505
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4382521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16907
telemt_desync_full_logged_total 4567
telemt_desync_suppressed_total 12340
telemt_desync_frames_bucket_total{bucket="1_2"} 4218
telemt_desync_frames_bucket_total{bucket="3_10"} 6456
telemt_desync_frames_bucket_total{bucket="gt_10"} 6233
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 25204
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24525
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 4384091
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 64097412004 (59.70 GB)
telemt_user_octets_to_client{user="hello"} 1381806608777 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67889.2 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743258
telemt_connections_bad_total 52733
telemt_handshake_timeouts_total 13597
telemt_upstream_connect_attempt_total 18712
telemt_upstream_connect_success_total 18452
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2103
telemt_me_reconnect_attempts_total 16486
telemt_me_reconnect_success_total 13033
telemt_me_reader_eof_total 13842
telemt_me_idle_close_by_peer_total 13841
telemt_me_route_drop_no_conn_total 246501
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591750
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1772
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13318
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13025
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 593701
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 6342573485 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 198022255032 (184.42 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 197845.9 (54h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3440172
telemt_connections_bad_total 37035
telemt_handshake_timeouts_total 227382
telemt_upstream_connect_attempt_total 44727
telemt_upstream_connect_success_total 44706
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10607
telemt_me_reconnect_attempts_total 39533
telemt_me_reconnect_success_total 34564
telemt_me_reader_eof_total 36720
telemt_me_idle_close_by_peer_total 36719
telemt_me_route_drop_no_conn_total 1176029
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2866068
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9494
telemt_desync_full_logged_total 3190
telemt_desync_suppressed_total 6304
telemt_desync_frames_bucket_total{bucket="1_2"} 1643
telemt_desync_frames_bucket_total{bucket="3_10"} 3435
telemt_desync_frames_bucket_total{bucket="gt_10"} 4416
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 35045
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34523
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 2865281
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 45777979932 (42.63 GB)
telemt_user_octets_to_client{user="hello"} 1026664804017 (956.16 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 197848.5 (54h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306431
telemt_connections_bad_total 23076
telemt_handshake_timeouts_total 259805
telemt_upstream_connect_attempt_total 61851
telemt_upstream_connect_success_total 59378
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61577
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20461
telemt_me_reconnect_attempts_total 51563
telemt_me_reconnect_success_total 42524
telemt_me_reader_eof_total 45603
telemt_me_idle_close_by_peer_total 45596
telemt_me_route_drop_no_conn_total 782722
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1829924
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3882
telemt_desync_full_logged_total 1250
telemt_desync_suppressed_total 2632
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 43173
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42500
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 1835879
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 27784653483 (25.88 GB)
telemt_user_octets_to_client{user="hello"} 674424644094 (628.11 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67281.9 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734352
telemt_connections_bad_total 7978
telemt_handshake_timeouts_total 8809
telemt_upstream_connect_attempt_total 17335
telemt_upstream_connect_success_total 16876
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 17335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 52284
telemt_me_reconnect_success_total 13523
telemt_me_reader_eof_total 15078
telemt_me_idle_close_by_peer_total 15077
telemt_me_route_drop_no_conn_total 280452
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 685301
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1725
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 14848
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13518
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 685169
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 12419881116 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 221431651956 (206.22 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 47
```