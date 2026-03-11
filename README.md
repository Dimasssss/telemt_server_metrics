# Server Metrics 2026-03-11 03:49:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48123.8 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 923064
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 24803
telemt_upstream_connect_attempt_total 10416
telemt_upstream_connect_success_total 10407
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 19615
telemt_me_reconnect_success_total 7943
telemt_me_reader_eof_total 8666
telemt_me_idle_close_by_peer_total 8666
telemt_me_route_drop_no_conn_total 357170
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848090
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3903
telemt_desync_full_logged_total 1085
telemt_desync_suppressed_total 2818
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1466
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8378
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7937
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 847813
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 11277274012 (10.50 GB)
telemt_user_octets_to_client{user="hello"} 251894093872 (234.59 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48180.7 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376716
telemt_connections_bad_total 2530
telemt_handshake_timeouts_total 18640
telemt_upstream_connect_attempt_total 18490
telemt_upstream_connect_success_total 15598
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1765
telemt_me_reconnect_attempts_total 11036
telemt_me_reconnect_success_total 10218
telemt_me_reader_eof_total 10795
telemt_me_idle_close_by_peer_total 10793
telemt_me_route_drop_no_conn_total 181577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1816
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1282
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 10337
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10197
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 325127
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 3091683926 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 76537014252 (71.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 48180.4 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632165
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 35269
telemt_upstream_connect_attempt_total 13012
telemt_upstream_connect_success_total 12842
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 13012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 20404
telemt_me_reconnect_success_total 9335
telemt_me_reader_eof_total 10129
telemt_me_idle_close_by_peer_total 10129
telemt_me_route_drop_no_conn_total 213924
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562349
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1628
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9807
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9324
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 563243
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 7157479881 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 170554953025 (158.84 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 48180.8 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477800
telemt_connections_bad_total 45451
telemt_handshake_timeouts_total 47719
telemt_upstream_connect_attempt_total 14055
telemt_upstream_connect_success_total 14055
telemt_upstream_connect_attempts_per_request{bucket="1"} 14055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 12665
telemt_me_reconnect_success_total 11626
telemt_me_reader_eof_total 12346
telemt_me_idle_close_by_peer_total 12346
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 142394
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370712
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11763
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11607
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 370378
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 4501455908 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 98544858408 (91.78 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48180.4 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504787
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3130
telemt_upstream_connect_attempt_total 14087
telemt_upstream_connect_success_total 14029
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 543
telemt_me_reconnect_attempts_total 15336
telemt_me_reconnect_success_total 11556
telemt_me_reader_eof_total 12198
telemt_me_idle_close_by_peer_total 12198
telemt_me_route_drop_no_conn_total 161478
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459225
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2367
telemt_desync_full_logged_total 922
telemt_desync_suppressed_total 1445
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 11819
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11556
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 458864
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 8656378920 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 163210956748 (152.00 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 44
```