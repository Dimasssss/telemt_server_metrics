# Server Metrics 2026-03-15 10:40:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 44766.4 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102132
telemt_connections_bad_total 67825
telemt_handshake_timeouts_total 8746
telemt_upstream_connect_attempt_total 9012
telemt_upstream_connect_success_total 8973
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7964
telemt_me_reconnect_success_total 6740
telemt_me_reader_eof_total 7153
telemt_me_idle_close_by_peer_total 7153
telemt_me_route_drop_no_conn_total 365207
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929133
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3450
telemt_desync_full_logged_total 968
telemt_desync_suppressed_total 2482
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1343
telemt_desync_frames_bucket_total{bucket="gt_10"} 1244
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6874
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 6729
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 929128
telemt_user_connections_current{user="hello"} 2072
telemt_user_octets_from_client{user="hello"} 13237997576 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 368926265084 (343.59 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 44766.9 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432541
telemt_connections_bad_total 23738
telemt_handshake_timeouts_total 18049
telemt_upstream_connect_attempt_total 11896
telemt_upstream_connect_success_total 11833
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 11896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9331
telemt_me_reconnect_success_total 9273
telemt_me_reader_eof_total 9804
telemt_me_idle_close_by_peer_total 9804
telemt_me_route_drop_no_conn_total 110292
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342043
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9364
telemt_me_writer_restored_same_endpoint_total 9265
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 342329
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 4950802075 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 129130081248 (120.26 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 44766.9 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826315
telemt_connections_bad_total 27574
telemt_handshake_timeouts_total 81770
telemt_upstream_connect_attempt_total 9912
telemt_upstream_connect_success_total 9870
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 7672
telemt_me_reconnect_success_total 7622
telemt_me_reader_eof_total 8073
telemt_me_idle_close_by_peer_total 8073
telemt_me_route_drop_no_conn_total 227468
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601051
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1369
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7724
telemt_me_writer_restored_same_endpoint_total 7603
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 600471
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 8880984504 (8.27 GB)
telemt_user_octets_to_client{user="hello"} 237981348296 (221.64 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 44766.8 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450274
telemt_connections_bad_total 56523
telemt_handshake_timeouts_total 25744
telemt_upstream_connect_attempt_total 13412
telemt_upstream_connect_success_total 13077
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 13412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31201
telemt_me_reconnect_success_total 10838
telemt_me_reader_eof_total 11800
telemt_me_idle_close_by_peer_total 11800
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 125882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338553
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11573
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10806
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 338461
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 4052565460 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 107993494728 (100.58 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 44767.9 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457610
telemt_connections_bad_total 6151
telemt_handshake_timeouts_total 7671
telemt_upstream_connect_attempt_total 9872
telemt_upstream_connect_success_total 9827
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7636
telemt_me_reconnect_success_total 7598
telemt_me_reader_eof_total 8083
telemt_me_idle_close_by_peer_total 8083
telemt_me_route_drop_no_conn_total 119470
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378047
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1451
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 987
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7685
telemt_me_writer_restored_same_endpoint_total 7590
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 378057
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 4724566496 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 140771641440 (131.10 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 106
```