# Server Metrics 2026-03-11 04:04:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49038.1 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939478
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 26279
telemt_upstream_connect_attempt_total 10583
telemt_upstream_connect_success_total 10574
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 19739
telemt_me_reconnect_success_total 8067
telemt_me_reader_eof_total 8799
telemt_me_idle_close_by_peer_total 8799
telemt_me_route_drop_no_conn_total 360880
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861376
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3926
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 2830
telemt_desync_frames_bucket_total{bucket="1_2"} 1116
telemt_desync_frames_bucket_total{bucket="3_10"} 1472
telemt_desync_frames_bucket_total{bucket="gt_10"} 1338
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8504
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8061
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 861097
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 11365809636 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 254579856700 (237.10 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49095.0 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380859
telemt_connections_bad_total 2531
telemt_handshake_timeouts_total 18797
telemt_upstream_connect_attempt_total 18712
telemt_upstream_connect_success_total 15817
telemt_upstream_connect_fail_total 2895
telemt_upstream_connect_attempts_per_request{bucket="1"} 18712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2895
telemt_me_keepalive_timeout_total 1772
telemt_me_reconnect_attempts_total 11212
telemt_me_reconnect_success_total 10394
telemt_me_reader_eof_total 10985
telemt_me_idle_close_by_peer_total 10983
telemt_me_route_drop_no_conn_total 183018
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326511
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1835
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10517
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10373
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 328781
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 3123421786 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 77316210524 (72.01 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49094.6 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639852
telemt_connections_bad_total 5365
telemt_handshake_timeouts_total 35648
telemt_upstream_connect_attempt_total 13279
telemt_upstream_connect_success_total 13107
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 13279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 554
telemt_me_reconnect_attempts_total 20625
telemt_me_reconnect_success_total 9556
telemt_me_reader_eof_total 10350
telemt_me_idle_close_by_peer_total 10350
telemt_me_route_drop_no_conn_total 216530
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569509
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 10028
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9545
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 570400
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 7214729009 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 171947247185 (160.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49095.1 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485494
telemt_connections_bad_total 46279
telemt_handshake_timeouts_total 49646
telemt_upstream_connect_attempt_total 14292
telemt_upstream_connect_success_total 14292
telemt_upstream_connect_attempts_per_request{bucket="1"} 14292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 479
telemt_me_reconnect_attempts_total 12859
telemt_me_reconnect_success_total 11820
telemt_me_reader_eof_total 12554
telemt_me_idle_close_by_peer_total 12554
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 144537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11958
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11801
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 375192
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 4549082292 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 100362042988 (93.47 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49094.9 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511412
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 3183
telemt_upstream_connect_attempt_total 14303
telemt_upstream_connect_success_total 14245
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6814
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 15509
telemt_me_reconnect_success_total 11728
telemt_me_reader_eof_total 12385
telemt_me_idle_close_by_peer_total 12385
telemt_me_route_drop_no_conn_total 164664
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465269
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2375
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11996
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11728
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 464901
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 8695474028 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 165198216456 (153.85 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 60
```