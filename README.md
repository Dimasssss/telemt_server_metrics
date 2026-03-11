# Server Metrics 2026-03-11 03:03:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45380.6 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877778
telemt_connections_bad_total 10065
telemt_handshake_timeouts_total 18325
telemt_upstream_connect_attempt_total 9858
telemt_upstream_connect_success_total 9849
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 511
telemt_me_reconnect_attempts_total 19186
telemt_me_reconnect_success_total 7515
telemt_me_reader_eof_total 8206
telemt_me_idle_close_by_peer_total 8206
telemt_me_route_drop_no_conn_total 347191
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3792
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 2739
telemt_desync_frames_bucket_total{bucket="1_2"} 1092
telemt_desync_frames_bucket_total{bucket="3_10"} 1429
telemt_desync_frames_bucket_total{bucket="gt_10"} 1271
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7945
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7509
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 816962
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 11022104888 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 242879264936 (226.20 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45437.5 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366050
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18338
telemt_upstream_connect_attempt_total 17752
telemt_upstream_connect_success_total 14861
telemt_upstream_connect_fail_total 2891
telemt_upstream_connect_attempts_per_request{bucket="1"} 17752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2891
telemt_me_keepalive_timeout_total 1754
telemt_me_reconnect_attempts_total 10430
telemt_me_reconnect_success_total 9613
telemt_me_reader_eof_total 10148
telemt_me_idle_close_by_peer_total 10146
telemt_me_route_drop_no_conn_total 178862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313935
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1796
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 9730
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9592
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 316205
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2984696630 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 74148346464 (69.06 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45437.3 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612458
telemt_connections_bad_total 5254
telemt_handshake_timeouts_total 34736
telemt_upstream_connect_attempt_total 12369
telemt_upstream_connect_success_total 12206
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 540
telemt_me_reconnect_attempts_total 19898
telemt_me_reconnect_success_total 8830
telemt_me_reader_eof_total 9587
telemt_me_idle_close_by_peer_total 9587
telemt_me_route_drop_no_conn_total 207961
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543555
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1591
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1123
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 687
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9294
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8819
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 544450
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 7065616053 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 166298451481 (154.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45437.6 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460549
telemt_connections_bad_total 42933
telemt_handshake_timeouts_total 44828
telemt_upstream_connect_attempt_total 13237
telemt_upstream_connect_success_total 13237
telemt_upstream_connect_attempts_per_request{bucket="1"} 13237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 460
telemt_me_reconnect_attempts_total 11976
telemt_me_reconnect_success_total 10938
telemt_me_reader_eof_total 11605
telemt_me_idle_close_by_peer_total 11605
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 137754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359103
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 11068
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10919
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 358771
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 4372819124 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 95833789252 (89.25 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45437.2 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485678
telemt_connections_bad_total 5810
telemt_handshake_timeouts_total 3051
telemt_upstream_connect_attempt_total 13362
telemt_upstream_connect_success_total 13305
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 534
telemt_me_reconnect_attempts_total 14743
telemt_me_reconnect_success_total 10966
telemt_me_reader_eof_total 11569
telemt_me_idle_close_by_peer_total 11569
telemt_me_route_drop_no_conn_total 156479
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442532
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2328
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1422
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 475
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 11225
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10966
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 442192
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 8561035052 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 159914136500 (148.93 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 37
```