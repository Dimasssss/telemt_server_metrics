# Server Metrics 2026-03-15 12:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 49667.7 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361095
telemt_connections_bad_total 81370
telemt_handshake_timeouts_total 11252
telemt_upstream_connect_attempt_total 10004
telemt_upstream_connect_success_total 9957
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 10004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 11619
telemt_me_reconnect_success_total 7448
telemt_me_reader_eof_total 7975
telemt_me_idle_close_by_peer_total 7975
telemt_me_route_drop_no_conn_total 452413
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1139361
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4348
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 3114
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 1705
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7690
telemt_me_refill_failed_total 129
telemt_me_writer_restored_same_endpoint_total 7437
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 1139060
telemt_user_connections_current{user="hello"} 2195
telemt_user_octets_from_client{user="hello"} 15801950464 (14.72 GB)
telemt_user_octets_to_client{user="hello"} 457942614136 (426.49 GB)
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 49668.3 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535476
telemt_connections_bad_total 27991
telemt_handshake_timeouts_total 28347
telemt_upstream_connect_attempt_total 13025
telemt_upstream_connect_success_total 12960
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10192
telemt_me_reconnect_success_total 10121
telemt_me_reader_eof_total 10709
telemt_me_idle_close_by_peer_total 10709
telemt_me_route_drop_no_conn_total 136795
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419716
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1612
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 599
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10233
telemt_me_writer_restored_same_endpoint_total 10109
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 419986
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 5985907523 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 156697231124 (145.94 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 49668.1 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056413
telemt_connections_bad_total 34843
telemt_handshake_timeouts_total 106234
telemt_upstream_connect_attempt_total 11013
telemt_upstream_connect_success_total 10960
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 11013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 9681
telemt_me_reconnect_success_total 8440
telemt_me_reader_eof_total 8956
telemt_me_idle_close_by_peer_total 8956
telemt_me_route_drop_no_conn_total 293490
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728163
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1875
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1222
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8588
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8421
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 726692
telemt_user_connections_current{user="hello"} 1271
telemt_user_octets_from_client{user="hello"} 10710101960 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 277953625052 (258.86 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 49668.2 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538647
telemt_connections_bad_total 64712
telemt_handshake_timeouts_total 28478
telemt_upstream_connect_attempt_total 14461
telemt_upstream_connect_success_total 14084
telemt_upstream_connect_fail_total 377
telemt_upstream_connect_attempts_per_request{bucket="1"} 14461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 377
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 37653
telemt_me_reconnect_success_total 11575
telemt_me_reader_eof_total 12725
telemt_me_idle_close_by_peer_total 12725
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 152409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403649
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1082
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12500
telemt_me_refill_failed_total 815
telemt_me_writer_restored_same_endpoint_total 11543
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 925
telemt_user_connections_total{user="hello"} 403544
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 5148089404 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 130594609316 (121.63 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 49669.2 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571075
telemt_connections_bad_total 6579
telemt_handshake_timeouts_total 12574
telemt_upstream_connect_attempt_total 11031
telemt_upstream_connect_success_total 10974
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 11031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 8517
telemt_me_reconnect_success_total 8471
telemt_me_reader_eof_total 8996
telemt_me_idle_close_by_peer_total 8996
telemt_me_route_drop_no_conn_total 145315
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470402
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1834
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1227
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 739
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8567
telemt_me_writer_restored_same_endpoint_total 8463
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 470439
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 6169359164 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 170787223996 (159.06 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 134
```