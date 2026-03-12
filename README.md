# Server Metrics 2026-03-12 11:20:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19339.6 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653787
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 3794
telemt_upstream_connect_attempt_total 3686
telemt_upstream_connect_success_total 3660
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6546
telemt_me_reconnect_success_total 2656
telemt_me_reader_eof_total 2875
telemt_me_idle_close_by_peer_total 2875
telemt_me_route_drop_no_conn_total 226758
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629875
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3141
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 2351
telemt_desync_frames_bucket_total{bucket="1_2"} 793
telemt_desync_frames_bucket_total{bucket="3_10"} 1164
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2804
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2643
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 629735
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 11134497536 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 173705414436 (161.78 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48960.0 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345214
telemt_connections_bad_total 3847
telemt_handshake_timeouts_total 12434
telemt_upstream_connect_attempt_total 12145
telemt_upstream_connect_success_total 12139
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 804
telemt_me_reconnect_attempts_total 9552
telemt_me_reconnect_success_total 9498
telemt_me_reader_eof_total 10096
telemt_me_idle_close_by_peer_total 10096
telemt_me_route_drop_no_conn_total 99383
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308517
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 780
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9580
telemt_me_writer_restored_same_endpoint_total 9489
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 308971
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 4160012331 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 109406809710 (101.89 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48959.8 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821093
telemt_connections_bad_total 4088
telemt_handshake_timeouts_total 60370
telemt_upstream_connect_attempt_total 12137
telemt_upstream_connect_success_total 12132
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 700
telemt_me_reconnect_attempts_total 9406
telemt_me_reconnect_success_total 9328
telemt_me_reader_eof_total 9812
telemt_me_idle_close_by_peer_total 9812
telemt_me_route_drop_no_conn_total 191921
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541970
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2451
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1723
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 1285
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9346
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9287
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 542215
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 7407028472 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 172543324325 (160.69 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48960.5 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437556
telemt_connections_bad_total 2491
telemt_handshake_timeouts_total 38882
telemt_upstream_connect_attempt_total 13068
telemt_upstream_connect_success_total 13016
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 977
telemt_me_reconnect_attempts_total 10602
telemt_me_reconnect_success_total 10559
telemt_me_reader_eof_total 11198
telemt_me_idle_close_by_peer_total 11198
telemt_me_route_drop_no_conn_total 145534
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 752
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10633
telemt_me_writer_restored_same_endpoint_total 10538
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 366615
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 4249123752 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 139067477104 (129.52 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48960.2 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497569
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 3788
telemt_upstream_connect_attempt_total 15863
telemt_upstream_connect_success_total 15673
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 15863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 14735
telemt_me_reconnect_success_total 13210
telemt_me_reader_eof_total 13723
telemt_me_idle_close_by_peer_total 13723
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 162111
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466275
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1938
telemt_desync_full_logged_total 645
telemt_desync_suppressed_total 1293
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13383
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 13184
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 466209
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 5316041636 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 114778779364 (106.90 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 114
```