# Server Metrics 2026-03-13 13:33:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 113693.1 (31h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3438425
telemt_connections_bad_total 37373
telemt_handshake_timeouts_total 58988
telemt_upstream_connect_attempt_total 22323
telemt_upstream_connect_success_total 22199
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2119
telemt_me_reconnect_attempts_total 26614
telemt_me_reconnect_success_total 16530
telemt_me_reader_eof_total 17770
telemt_me_idle_close_by_peer_total 17769
telemt_me_route_drop_no_conn_total 1275693
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3154461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13117
telemt_desync_full_logged_total 3425
telemt_desync_suppressed_total 9692
telemt_desync_frames_bucket_total{bucket="1_2"} 3325
telemt_desync_frames_bucket_total{bucket="3_10"} 4970
telemt_desync_frames_bucket_total{bucket="gt_10"} 4822
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17075
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16517
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3154340
telemt_user_connections_current{user="hello"} 1870
telemt_user_octets_from_client{user="hello"} 43506964704 (40.52 GB)
telemt_user_octets_to_client{user="hello"} 1008263073160 (939.02 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13357.1 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186268
telemt_connections_bad_total 10511
telemt_handshake_timeouts_total 4853
telemt_upstream_connect_attempt_total 3160
telemt_upstream_connect_success_total 3084
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 3611
telemt_me_reconnect_success_total 2381
telemt_me_reader_eof_total 2510
telemt_me_idle_close_by_peer_total 2510
telemt_me_route_drop_no_conn_total 67630
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166195
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2441
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2374
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 166219
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1661751768 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 46336004976 (43.15 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 143313.6 (39h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2587196
telemt_connections_bad_total 26836
telemt_handshake_timeouts_total 172267
telemt_upstream_connect_attempt_total 32491
telemt_upstream_connect_success_total 32481
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3203
telemt_me_reconnect_attempts_total 27537
telemt_me_reconnect_success_total 24991
telemt_me_reader_eof_total 26498
telemt_me_idle_close_by_peer_total 26497
telemt_me_route_drop_no_conn_total 868697
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2108144
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7337
telemt_desync_full_logged_total 2394
telemt_desync_suppressed_total 4943
telemt_desync_frames_bucket_total{bucket="1_2"} 1158
telemt_desync_frames_bucket_total{bucket="3_10"} 2673
telemt_desync_frames_bucket_total{bucket="gt_10"} 3506
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 25281
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24950
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 2107568
telemt_user_connections_current{user="hello"} 1110
telemt_user_octets_from_client{user="hello"} 35246102572 (32.83 GB)
telemt_user_octets_to_client{user="hello"} 753908519417 (702.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 143314.0 (39h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1649463
telemt_connections_bad_total 17894
telemt_handshake_timeouts_total 117114
telemt_upstream_connect_attempt_total 45864
telemt_upstream_connect_success_total 43544
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45590
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11834
telemt_me_reconnect_attempts_total 39507
telemt_me_reconnect_success_total 30541
telemt_me_reader_eof_total 32841
telemt_me_idle_close_by_peer_total 32834
telemt_me_route_drop_no_conn_total 587658
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1378602
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2754
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 1855
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 31047
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30517
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 1383325
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 21178886605 (19.72 GB)
telemt_user_octets_to_client{user="hello"} 538452414110 (501.47 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12749.5 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200662
telemt_connections_bad_total 3847
telemt_handshake_timeouts_total 1781
telemt_upstream_connect_attempt_total 2598
telemt_upstream_connect_success_total 2512
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 2598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 9891
telemt_me_reconnect_success_total 1816
telemt_me_reader_eof_total 2076
telemt_me_idle_close_by_peer_total 2076
telemt_me_route_drop_no_conn_total 77746
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187764
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 448
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2068
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1812
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 187748
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 1980100060 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 57015924536 (53.10 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 122
```