# Server Metrics 2026-03-13 04:26:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 80882.4 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2197544
telemt_connections_bad_total 30094
telemt_handshake_timeouts_total 23199
telemt_upstream_connect_attempt_total 15970
telemt_upstream_connect_success_total 15882
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 15970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1303
telemt_me_reconnect_attempts_total 20729
telemt_me_reconnect_success_total 11864
telemt_me_reader_eof_total 12807
telemt_me_idle_close_by_peer_total 12806
telemt_me_route_drop_no_conn_total 839239
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2020904
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8905
telemt_desync_full_logged_total 2311
telemt_desync_suppressed_total 6594
telemt_desync_frames_bucket_total{bucket="1_2"} 2346
telemt_desync_frames_bucket_total{bucket="3_10"} 3212
telemt_desync_frames_bucket_total{bucket="gt_10"} 3347
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12307
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11851
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 2020330
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 29312387344 (27.30 GB)
telemt_user_octets_to_client{user="hello"} 696212207732 (648.40 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110502.9 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 893492
telemt_connections_bad_total 11880
telemt_handshake_timeouts_total 39400
telemt_upstream_connect_attempt_total 28067
telemt_upstream_connect_success_total 28038
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 28067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3486
telemt_me_reconnect_attempts_total 21016
telemt_me_reconnect_success_total 20904
telemt_me_reader_eof_total 22280
telemt_me_idle_close_by_peer_total 22280
telemt_me_route_drop_no_conn_total 285271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805644
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3215
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2205
telemt_desync_frames_bucket_total{bucket="1_2"} 1288
telemt_desync_frames_bucket_total{bucket="3_10"} 1049
telemt_desync_frames_bucket_total{bucket="gt_10"} 878
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21110
telemt_me_writer_restored_same_endpoint_total 20895
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 807543
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 12806634344 (11.93 GB)
telemt_user_octets_to_client{user="hello"} 311539197275 (290.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110502.9 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1845617
telemt_connections_bad_total 15285
telemt_handshake_timeouts_total 121230
telemt_upstream_connect_attempt_total 25758
telemt_upstream_connect_success_total 25748
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 21172
telemt_me_reconnect_success_total 19905
telemt_me_reader_eof_total 21082
telemt_me_idle_close_by_peer_total 21081
telemt_me_route_drop_no_conn_total 596962
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1457372
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20095
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19864
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1456969
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 25238576852 (23.51 GB)
telemt_user_octets_to_client{user="hello"} 519315295189 (483.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110503.3 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143742
telemt_connections_bad_total 13193
telemt_handshake_timeouts_total 74745
telemt_upstream_connect_attempt_total 38113
telemt_upstream_connect_success_total 35830
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 37839
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11383
telemt_me_reconnect_attempts_total 33404
telemt_me_reconnect_success_total 24473
telemt_me_reader_eof_total 26411
telemt_me_idle_close_by_peer_total 26404
telemt_me_route_drop_no_conn_total 406623
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983509
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 24913
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24449
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 988686
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 15172884137 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 390078600270 (363.29 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 110503.1 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1270395
telemt_connections_bad_total 12881
telemt_handshake_timeouts_total 10193
telemt_upstream_connect_attempt_total 34880
telemt_upstream_connect_success_total 34457
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 34880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_keepalive_timeout_total 1925
telemt_me_reconnect_attempts_total 42701
telemt_me_reconnect_success_total 28969
telemt_me_reader_eof_total 30466
telemt_me_idle_close_by_peer_total 30466
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 471483
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1175190
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4300
telemt_desync_full_logged_total 1541
telemt_desync_suppressed_total 2759
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29728
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28919
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 1175045
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 14348031964 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 401800465436 (374.21 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 60
```