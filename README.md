# Server Metrics 2026-03-13 06:08:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87005.1 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2342305
telemt_connections_bad_total 35784
telemt_handshake_timeouts_total 24707
telemt_upstream_connect_attempt_total 17101
telemt_upstream_connect_success_total 17006
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 1318
telemt_me_reconnect_attempts_total 21549
telemt_me_reconnect_success_total 12680
telemt_me_reader_eof_total 13678
telemt_me_idle_close_by_peer_total 13677
telemt_me_route_drop_no_conn_total 889498
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2154873
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9632
telemt_desync_full_logged_total 2480
telemt_desync_suppressed_total 7152
telemt_desync_frames_bucket_total{bucket="1_2"} 2498
telemt_desync_frames_bucket_total{bucket="3_10"} 3532
telemt_desync_frames_bucket_total{bucket="gt_10"} 3602
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13132
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12667
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 2154270
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 31094587948 (28.96 GB)
telemt_user_octets_to_client{user="hello"} 735681959280 (685.16 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 116625.6 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946665
telemt_connections_bad_total 12466
telemt_handshake_timeouts_total 40938
telemt_upstream_connect_attempt_total 29432
telemt_upstream_connect_success_total 29401
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3573
telemt_me_reconnect_attempts_total 22079
telemt_me_reconnect_success_total 21961
telemt_me_reader_eof_total 23416
telemt_me_idle_close_by_peer_total 23416
telemt_me_route_drop_no_conn_total 301347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3492
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2394
telemt_desync_frames_bucket_total{bucket="1_2"} 1361
telemt_desync_frames_bucket_total{bucket="3_10"} 1129
telemt_desync_frames_bucket_total{bucket="gt_10"} 1002
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22179
telemt_me_writer_restored_same_endpoint_total 21952
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 856523
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 13503693424 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 325654699111 (303.29 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 116625.5 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1957250
telemt_connections_bad_total 22771
telemt_handshake_timeouts_total 130343
telemt_upstream_connect_attempt_total 27061
telemt_upstream_connect_success_total 27051
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1682
telemt_me_reconnect_attempts_total 22172
telemt_me_reconnect_success_total 20900
telemt_me_reader_eof_total 22142
telemt_me_idle_close_by_peer_total 22141
telemt_me_route_drop_no_conn_total 626876
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1540179
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5338
telemt_desync_full_logged_total 1619
telemt_desync_suppressed_total 3719
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1940
telemt_desync_frames_bucket_total{bucket="gt_10"} 2515
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 21102
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20859
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1539677
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 26381058908 (24.57 GB)
telemt_user_octets_to_client{user="hello"} 546689612605 (509.14 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 116625.8 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1191157
telemt_connections_bad_total 13996
telemt_handshake_timeouts_total 77796
telemt_upstream_connect_attempt_total 39749
telemt_upstream_connect_success_total 37461
telemt_upstream_connect_fail_total 2151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39475
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2150
telemt_me_keepalive_timeout_total 11407
telemt_me_reconnect_attempts_total 34730
telemt_me_reconnect_success_total 25795
telemt_me_reader_eof_total 27804
telemt_me_idle_close_by_peer_total 27797
telemt_me_route_drop_no_conn_total 427505
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026535
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2028
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1367
telemt_desync_frames_bucket_total{bucket="1_2"} 558
telemt_desync_frames_bucket_total{bucket="3_10"} 785
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 26249
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25771
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 1031457
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 15658291401 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 412125887134 (383.82 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 116625.6 (32h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344632
telemt_connections_bad_total 17021
telemt_handshake_timeouts_total 11028
telemt_upstream_connect_attempt_total 36953
telemt_upstream_connect_success_total 36506
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 36953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 2025
telemt_me_reconnect_attempts_total 44442
telemt_me_reconnect_success_total 30705
telemt_me_reader_eof_total 32232
telemt_me_idle_close_by_peer_total 32232
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 495194
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241667
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4454
telemt_desync_full_logged_total 1605
telemt_desync_suppressed_total 2849
telemt_desync_frames_bucket_total{bucket="1_2"} 1357
telemt_desync_frames_bucket_total{bucket="3_10"} 1445
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 31471
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30651
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 766
telemt_user_connections_total{user="hello"} 1241509
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 14947957736 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 423091669848 (394.03 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 91
```