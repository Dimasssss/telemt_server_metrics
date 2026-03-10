# Server Metrics 2026-03-10 18:54:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16069.4 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519844
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2763
telemt_upstream_connect_attempt_total 3202
telemt_upstream_connect_success_total 3193
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 12791
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2655
telemt_me_idle_close_by_peer_total 2655
telemt_me_route_drop_no_conn_total 217454
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490564
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2565
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1862
telemt_desync_frames_bucket_total{bucket="1_2"} 679
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2670
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2327
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 490477
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 7211490872 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 142034563204 (132.28 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16126.2 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227462
telemt_connections_bad_total 1814
telemt_handshake_timeouts_total 16372
telemt_upstream_connect_attempt_total 8428
telemt_upstream_connect_success_total 5685
telemt_upstream_connect_fail_total 2743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1873
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2743
telemt_me_keepalive_timeout_total 701
telemt_me_reconnect_attempts_total 2941
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 2965
telemt_me_idle_close_by_peer_total 2963
telemt_me_route_drop_no_conn_total 127190
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 730
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2892
telemt_me_writer_restored_same_endpoint_total 2841
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 193281
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 2104186242 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 46296734254 (43.12 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 16126.0 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377072
telemt_connections_bad_total 1076
telemt_handshake_timeouts_total 31855
telemt_upstream_connect_attempt_total 5043
telemt_upstream_connect_success_total 4964
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 5043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 6517
telemt_me_reconnect_success_total 3071
telemt_me_reader_eof_total 3275
telemt_me_idle_close_by_peer_total 3275
telemt_me_route_drop_no_conn_total 126051
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319621
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1011
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3232
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3060
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 320575
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 4392927397 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 102078630569 (95.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 16126.4 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245237
telemt_connections_bad_total 15857
telemt_handshake_timeouts_total 22134
telemt_upstream_connect_attempt_total 4328
telemt_upstream_connect_success_total 4328
telemt_upstream_connect_attempts_per_request{bucket="1"} 4328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 3509
telemt_me_reconnect_success_total 3489
telemt_me_reader_eof_total 3608
telemt_me_idle_close_by_peer_total 3608
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 81014
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196916
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 542
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3520
telemt_me_writer_restored_same_endpoint_total 3477
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 196708
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 2923156384 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 56364669296 (52.49 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16126.1 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259612
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 1794
telemt_upstream_connect_attempt_total 4819
telemt_upstream_connect_success_total 4802
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3977
telemt_me_reconnect_success_total 3946
telemt_me_reader_eof_total 4066
telemt_me_idle_close_by_peer_total 4066
telemt_me_route_drop_no_conn_total 96209
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245032
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1370
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3999
telemt_me_writer_restored_same_endpoint_total 3946
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 244964
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 5123810924 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 77105595028 (71.81 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 74
```