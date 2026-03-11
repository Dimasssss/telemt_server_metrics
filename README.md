# Server Metrics 2026-03-11 03:28:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46904.4 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899937
telemt_connections_bad_total 10070
telemt_handshake_timeouts_total 21991
telemt_upstream_connect_attempt_total 10156
telemt_upstream_connect_success_total 10147
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 19402
telemt_me_reconnect_success_total 7731
telemt_me_reader_eof_total 8434
telemt_me_idle_close_by_peer_total 8434
telemt_me_route_drop_no_conn_total 352766
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833716
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3868
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2797
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 1455
telemt_desync_frames_bucket_total{bucket="gt_10"} 1311
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8165
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7725
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 833440
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 11154096104 (10.39 GB)
telemt_user_octets_to_client{user="hello"} 247812600836 (230.79 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46961.1 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371494
telemt_connections_bad_total 2495
telemt_handshake_timeouts_total 18454
telemt_upstream_connect_attempt_total 18171
telemt_upstream_connect_success_total 15279
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1761
telemt_me_reconnect_attempts_total 10761
telemt_me_reconnect_success_total 9944
telemt_me_reader_eof_total 10507
telemt_me_idle_close_by_peer_total 10505
telemt_me_route_drop_no_conn_total 180388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1804
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10061
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9923
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 320636
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 3058272446 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75429715992 (70.25 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46961.0 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622774
telemt_connections_bad_total 5343
telemt_handshake_timeouts_total 34836
telemt_upstream_connect_attempt_total 12716
telemt_upstream_connect_success_total 12550
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 12716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 549
telemt_me_reconnect_attempts_total 20155
telemt_me_reconnect_success_total 9085
telemt_me_reader_eof_total 9865
telemt_me_idle_close_by_peer_total 9865
telemt_me_route_drop_no_conn_total 211451
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553496
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1606
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9554
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9074
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 554390
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 7116120809 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 168786950589 (157.20 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46961.4 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469501
telemt_connections_bad_total 44347
telemt_handshake_timeouts_total 46183
telemt_upstream_connect_attempt_total 13698
telemt_upstream_connect_success_total 13697
telemt_upstream_connect_attempts_per_request{bucket="1"} 13697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 12351
telemt_me_reconnect_success_total 11312
telemt_me_reader_eof_total 12011
telemt_me_idle_close_by_peer_total 12011
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 140099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365160
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 785
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11447
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11293
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 364827
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 4427354324 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 97293800240 (90.61 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46961.1 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495856
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3090
telemt_upstream_connect_attempt_total 13762
telemt_upstream_connect_success_total 13704
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 15054
telemt_me_reconnect_success_total 11275
telemt_me_reader_eof_total 11900
telemt_me_idle_close_by_peer_total 11900
telemt_me_route_drop_no_conn_total 159067
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451421
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2337
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 1424
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 11536
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11275
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 451071
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 8608191244 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 161894587612 (150.78 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 38
```