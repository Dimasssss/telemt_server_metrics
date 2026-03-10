# Server Metrics 2026-03-10 22:18:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28311.5 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728783
telemt_connections_bad_total 8313
telemt_handshake_timeouts_total 8308
telemt_upstream_connect_attempt_total 6107
telemt_upstream_connect_success_total 6098
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 16257
telemt_me_reconnect_success_total 4598
telemt_me_reader_eof_total 5079
telemt_me_idle_close_by_peer_total 5079
telemt_me_route_drop_no_conn_total 303886
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689458
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3434
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2475
telemt_desync_frames_bucket_total{bucket="1_2"} 992
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1160
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 5000
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4592
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 689263
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 9947906632 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 208989906304 (194.64 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28368.3 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316824
telemt_connections_bad_total 2342
telemt_handshake_timeouts_total 17555
telemt_upstream_connect_attempt_total 12617
telemt_upstream_connect_success_total 9752
telemt_upstream_connect_fail_total 2865
telemt_upstream_connect_attempts_per_request{bucket="1"} 12617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2865
telemt_me_keepalive_timeout_total 1375
telemt_me_reconnect_attempts_total 6144
telemt_me_reconnect_success_total 5338
telemt_me_reader_eof_total 5605
telemt_me_idle_close_by_peer_total 5603
telemt_me_route_drop_no_conn_total 166026
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5424
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5317
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 269255
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2652492046 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 63394494336 (59.04 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 28368.0 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522579
telemt_connections_bad_total 3291
telemt_handshake_timeouts_total 33686
telemt_upstream_connect_attempt_total 7884
telemt_upstream_connect_success_total 7768
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 16282
telemt_me_reconnect_success_total 5228
telemt_me_reader_eof_total 5754
telemt_me_idle_close_by_peer_total 5754
telemt_me_route_drop_no_conn_total 181299
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457319
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1457
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5654
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5217
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 458252
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 6597796973 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 147663988373 (137.52 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 28368.4 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364801
telemt_connections_bad_total 27364
telemt_handshake_timeouts_total 32532
telemt_upstream_connect_attempt_total 7873
telemt_upstream_connect_success_total 7873
telemt_upstream_connect_attempts_per_request{bucket="1"} 7873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 7431
telemt_me_reconnect_success_total 6407
telemt_me_reader_eof_total 6732
telemt_me_idle_close_by_peer_total 6732
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 117485
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292091
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 6507
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6393
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 291769
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 4033686440 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 86243699144 (80.32 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28368.2 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385153
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 2538
telemt_upstream_connect_attempt_total 8850
telemt_upstream_connect_success_total 8815
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 11074
telemt_me_reconnect_success_total 7316
telemt_me_reader_eof_total 7670
telemt_me_idle_close_by_peer_total 7670
telemt_me_route_drop_no_conn_total 135308
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358979
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2119
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1317
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 904
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 7536
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7316
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 358816
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 6412961472 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 136395466484 (127.03 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 46
```