# Server Metrics 2026-03-13 20:31:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 138790.7 (38h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4410089
telemt_connections_bad_total 37959
telemt_handshake_timeouts_total 106068
telemt_upstream_connect_attempt_total 29046
telemt_upstream_connect_success_total 28847
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6553
telemt_me_reconnect_attempts_total 29688
telemt_me_reconnect_success_total 19571
telemt_me_reader_eof_total 21003
telemt_me_idle_close_by_peer_total 21002
telemt_me_route_drop_no_conn_total 1660693
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4036989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16029
telemt_desync_full_logged_total 4278
telemt_desync_suppressed_total 11751
telemt_desync_frames_bucket_total{bucket="1_2"} 4003
telemt_desync_frames_bucket_total{bucket="3_10"} 6107
telemt_desync_frames_bucket_total{bucket="gt_10"} 5919
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20168
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19558
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 4039128
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 59475866392 (55.39 GB)
telemt_user_octets_to_client{user="hello"} 1274497850769 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 38454.4 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545025
telemt_connections_bad_total 41376
telemt_handshake_timeouts_total 12126
telemt_upstream_connect_attempt_total 11008
telemt_upstream_connect_success_total 10792
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 11008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 1881
telemt_me_reconnect_attempts_total 10253
telemt_me_reconnect_success_total 6833
telemt_me_reader_eof_total 7230
telemt_me_idle_close_by_peer_total 7229
telemt_me_route_drop_no_conn_total 201860
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472709
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1594
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 1168
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7039
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6825
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 474638
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 5104163117 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 150057706484 (139.75 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 168411.1 (46h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3211515
telemt_connections_bad_total 29697
telemt_handshake_timeouts_total 214435
telemt_upstream_connect_attempt_total 37465
telemt_upstream_connect_success_total 37446
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 37465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 10221
telemt_me_reconnect_attempts_total 31297
telemt_me_reconnect_success_total 28724
telemt_me_reader_eof_total 30417
telemt_me_idle_close_by_peer_total 30416
telemt_me_route_drop_no_conn_total 1100061
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2661785
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8810
telemt_desync_full_logged_total 2944
telemt_desync_suppressed_total 5866
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 3219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4130
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29071
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28683
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 2661067
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 43827876432 (40.82 GB)
telemt_user_octets_to_client{user="hello"} 935945836785 (871.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 168411.6 (46h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2084162
telemt_connections_bad_total 22697
telemt_handshake_timeouts_total 199083
telemt_upstream_connect_attempt_total 52563
telemt_upstream_connect_success_total 50124
telemt_upstream_connect_fail_total 2302
telemt_upstream_connect_attempts_per_request{bucket="1"} 52289
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2301
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20213
telemt_me_reconnect_attempts_total 43704
telemt_me_reconnect_success_total 34693
telemt_me_reader_eof_total 37242
telemt_me_idle_close_by_peer_total 37235
telemt_me_route_drop_no_conn_total 735767
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1716028
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3686
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 973
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 35270
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34669
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 1721900
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 26742917899 (24.91 GB)
telemt_user_octets_to_client{user="hello"} 644976160098 (600.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37846.9 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583335
telemt_connections_bad_total 5784
telemt_handshake_timeouts_total 5534
telemt_upstream_connect_attempt_total 8387
telemt_upstream_connect_success_total 8116
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 8387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 28087
telemt_me_reconnect_success_total 6219
telemt_me_reader_eof_total 7023
telemt_me_idle_close_by_peer_total 7022
telemt_me_route_drop_no_conn_total 220904
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547389
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1480
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6959
telemt_me_refill_failed_total 681
telemt_me_writer_restored_same_endpoint_total 6215
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 547331
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 6916348940 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 174342936336 (162.37 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 64
```