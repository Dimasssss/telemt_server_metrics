# Server Metrics 2026-03-12 12:17:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22706.6 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772578
telemt_connections_bad_total 1583
telemt_handshake_timeouts_total 4985
telemt_upstream_connect_attempt_total 4519
telemt_upstream_connect_success_total 4490
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 7198
telemt_me_reconnect_success_total 3304
telemt_me_reader_eof_total 3547
telemt_me_idle_close_by_peer_total 3547
telemt_me_route_drop_no_conn_total 273549
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3856
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2882
telemt_desync_frames_bucket_total{bucket="1_2"} 975
telemt_desync_frames_bucket_total{bucket="3_10"} 1399
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3460
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3291
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 744311
telemt_user_connections_current{user="hello"} 1524
telemt_user_octets_from_client{user="hello"} 12859114104 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 207670714732 (193.41 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52327.1 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395253
telemt_connections_bad_total 4780
telemt_handshake_timeouts_total 20849
telemt_upstream_connect_attempt_total 12748
telemt_upstream_connect_success_total 12740
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1054
telemt_me_reconnect_attempts_total 9982
telemt_me_reconnect_success_total 9924
telemt_me_reader_eof_total 10553
telemt_me_idle_close_by_peer_total 10553
telemt_me_route_drop_no_conn_total 112882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348098
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1127
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 389
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10017
telemt_me_writer_restored_same_endpoint_total 9915
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 348562
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 4733806627 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 123871155450 (115.36 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52326.9 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897870
telemt_connections_bad_total 5042
telemt_handshake_timeouts_total 67175
telemt_upstream_connect_attempt_total 12853
telemt_upstream_connect_success_total 12848
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 9944
telemt_me_reconnect_success_total 9861
telemt_me_reader_eof_total 10374
telemt_me_idle_close_by_peer_total 10374
telemt_me_route_drop_no_conn_total 217931
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609717
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2821
telemt_desync_full_logged_total 840
telemt_desync_suppressed_total 1981
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 1429
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9884
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9820
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 609951
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 7973782744 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 193167262853 (179.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52327.5 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500854
telemt_connections_bad_total 7628
telemt_handshake_timeouts_total 46717
telemt_upstream_connect_attempt_total 14082
telemt_upstream_connect_success_total 14026
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 14082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 11435
telemt_me_reconnect_success_total 11389
telemt_me_reader_eof_total 12046
telemt_me_idle_close_by_peer_total 12046
telemt_me_route_drop_no_conn_total 163871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416437
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 844
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 551
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11473
telemt_me_writer_restored_same_endpoint_total 11368
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 416260
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 4748383828 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 160808248680 (149.76 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52327.1 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561488
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 17061
telemt_upstream_connect_success_total 16857
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 17061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 962
telemt_me_reconnect_attempts_total 18879
telemt_me_reconnect_success_total 14216
telemt_me_reader_eof_total 14835
telemt_me_idle_close_by_peer_total 14835
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 187156
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524661
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2203
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 637
telemt_desync_frames_bucket_total{bucket="3_10"} 772
telemt_desync_frames_bucket_total{bucket="gt_10"} 794
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14499
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 14189
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 524576
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 6101355192 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 131801167368 (122.75 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 122
```