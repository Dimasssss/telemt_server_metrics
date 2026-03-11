# Server Metrics 2026-03-11 04:55:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52086.5 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008637
telemt_connections_bad_total 10610
telemt_handshake_timeouts_total 31596
telemt_upstream_connect_attempt_total 11155
telemt_upstream_connect_success_total 11146
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 20181
telemt_me_reconnect_success_total 8506
telemt_me_reader_eof_total 9264
telemt_me_idle_close_by_peer_total 9264
telemt_me_route_drop_no_conn_total 376705
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908404
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4134
telemt_desync_full_logged_total 1163
telemt_desync_suppressed_total 2971
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 1561
telemt_desync_frames_bucket_total{bucket="gt_10"} 1410
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8947
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8500
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 908117
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 11919131220 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 266480889416 (248.18 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52143.2 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395528
telemt_connections_bad_total 2598
telemt_handshake_timeouts_total 19156
telemt_upstream_connect_attempt_total 19488
telemt_upstream_connect_success_total 16587
telemt_upstream_connect_fail_total 2901
telemt_upstream_connect_attempts_per_request{bucket="1"} 19488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2901
telemt_me_keepalive_timeout_total 1779
telemt_me_reconnect_attempts_total 11851
telemt_me_reconnect_success_total 11031
telemt_me_reader_eof_total 11659
telemt_me_idle_close_by_peer_total 11657
telemt_me_route_drop_no_conn_total 187833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339901
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11163
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11010
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 342173
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 3275590646 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 81812366148 (76.19 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52143.0 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671336
telemt_connections_bad_total 5592
telemt_handshake_timeouts_total 36726
telemt_upstream_connect_attempt_total 14100
telemt_upstream_connect_success_total 13917
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 14100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 565
telemt_me_reconnect_attempts_total 21305
telemt_me_reconnect_success_total 10234
telemt_me_reader_eof_total 11067
telemt_me_idle_close_by_peer_total 11067
telemt_me_route_drop_no_conn_total 225687
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598790
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1162
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 710
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10714
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10223
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 599657
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 7414413565 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 179680518513 (167.34 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52143.4 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512590
telemt_connections_bad_total 49052
telemt_handshake_timeouts_total 53802
telemt_upstream_connect_attempt_total 15024
telemt_upstream_connect_success_total 15024
telemt_upstream_connect_attempts_per_request{bucket="1"} 15024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 13460
telemt_me_reconnect_success_total 12418
telemt_me_reader_eof_total 13183
telemt_me_idle_close_by_peer_total 13183
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 151881
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395488
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 836
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12561
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12398
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 395146
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 4808523124 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 108399176208 (100.95 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52143.1 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534819
telemt_connections_bad_total 5829
telemt_handshake_timeouts_total 3467
telemt_upstream_connect_attempt_total 15024
telemt_upstream_connect_success_total 14962
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 16096
telemt_me_reconnect_success_total 12314
telemt_me_reader_eof_total 12997
telemt_me_idle_close_by_peer_total 12997
telemt_me_route_drop_no_conn_total 173169
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487595
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2412
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 1468
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1022
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12589
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12314
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 487213
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 8898891588 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 172388771936 (160.55 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 59
```