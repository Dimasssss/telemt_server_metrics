# Server Metrics 2026-03-13 02:49:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75066.6 (20h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2104637
telemt_connections_bad_total 27845
telemt_handshake_timeouts_total 22489
telemt_upstream_connect_attempt_total 14891
telemt_upstream_connect_success_total 14807
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1267
telemt_me_reconnect_attempts_total 19912
telemt_me_reconnect_success_total 11051
telemt_me_reader_eof_total 11938
telemt_me_idle_close_by_peer_total 11937
telemt_me_route_drop_no_conn_total 810055
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1939681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8723
telemt_desync_full_logged_total 2271
telemt_desync_suppressed_total 6452
telemt_desync_frames_bucket_total{bucket="1_2"} 2298
telemt_desync_frames_bucket_total{bucket="3_10"} 3147
telemt_desync_frames_bucket_total{bucket="gt_10"} 3278
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11481
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11038
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1939137
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 28213210876 (26.28 GB)
telemt_user_octets_to_client{user="hello"} 673285431916 (627.05 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104687.0 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858318
telemt_connections_bad_total 11826
telemt_handshake_timeouts_total 33376
telemt_upstream_connect_attempt_total 26684
telemt_upstream_connect_success_total 26655
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3458
telemt_me_reconnect_attempts_total 19894
telemt_me_reconnect_success_total 19785
telemt_me_reader_eof_total 21085
telemt_me_idle_close_by_peer_total 21085
telemt_me_route_drop_no_conn_total 276048
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777762
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3100
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 19979
telemt_me_writer_restored_same_endpoint_total 19776
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 779665
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 12386852988 (11.54 GB)
telemt_user_octets_to_client{user="hello"} 294085664683 (273.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104686.8 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1780312
telemt_connections_bad_total 9228
telemt_handshake_timeouts_total 119553
telemt_upstream_connect_attempt_total 24439
telemt_upstream_connect_success_total 24429
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1608
telemt_me_reconnect_attempts_total 20113
telemt_me_reconnect_success_total 18849
telemt_me_reader_eof_total 19966
telemt_me_idle_close_by_peer_total 19965
telemt_me_route_drop_no_conn_total 580091
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402136
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5022
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3484
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 19025
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18808
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1401730
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 20245942488 (18.86 GB)
telemt_user_octets_to_client{user="hello"} 504376381729 (469.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104687.2 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110897
telemt_connections_bad_total 13138
telemt_handshake_timeouts_total 73383
telemt_upstream_connect_attempt_total 36583
telemt_upstream_connect_success_total 34307
telemt_upstream_connect_fail_total 2139
telemt_upstream_connect_attempts_per_request{bucket="1"} 36309
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2138
telemt_me_keepalive_timeout_total 11363
telemt_me_reconnect_attempts_total 32139
telemt_me_reconnect_success_total 23214
telemt_me_reader_eof_total 25074
telemt_me_idle_close_by_peer_total 25067
telemt_me_route_drop_no_conn_total 393940
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 952789
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1899
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1269
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 23645
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23190
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 957959
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 14613228917 (13.61 GB)
telemt_user_octets_to_client{user="hello"} 376189661854 (350.35 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 104687.0 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1229341
telemt_connections_bad_total 12632
telemt_handshake_timeouts_total 9554
telemt_upstream_connect_attempt_total 33107
telemt_upstream_connect_success_total 32701
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 33107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_keepalive_timeout_total 1897
telemt_me_reconnect_attempts_total 41204
telemt_me_reconnect_success_total 27474
telemt_me_reader_eof_total 28914
telemt_me_idle_close_by_peer_total 28914
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 459180
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137086
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4229
telemt_desync_full_logged_total 1501
telemt_desync_suppressed_total 2728
telemt_desync_frames_bucket_total{bucket="1_2"} 1273
telemt_desync_frames_bucket_total{bucket="3_10"} 1393
telemt_desync_frames_bucket_total{bucket="gt_10"} 1563
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 28218
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27425
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 1136941
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 14050671552 (13.09 GB)
telemt_user_octets_to_client{user="hello"} 393594603320 (366.56 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 43
```