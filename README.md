# Server Metrics 2026-03-11 10:15:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71322.7 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557866
telemt_connections_bad_total 24742
telemt_handshake_timeouts_total 41101
telemt_upstream_connect_attempt_total 14750
telemt_upstream_connect_success_total 14740
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 788
telemt_me_reconnect_attempts_total 22816
telemt_me_reconnect_success_total 11126
telemt_me_reader_eof_total 12045
telemt_me_idle_close_by_peer_total 12045
telemt_me_route_drop_no_conn_total 574035
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1413112
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7013
telemt_desync_full_logged_total 1941
telemt_desync_suppressed_total 5072
telemt_desync_frames_bucket_total{bucket="1_2"} 1853
telemt_desync_frames_bucket_total{bucket="3_10"} 2652
telemt_desync_frames_bucket_total{bucket="gt_10"} 2508
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11602
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11120
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 1411691
telemt_user_connections_current{user="hello"} 1387
telemt_user_octets_from_client{user="hello"} 18434870624 (17.17 GB)
telemt_user_octets_to_client{user="hello"} 403339694540 (375.64 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71379.4 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596343
telemt_connections_bad_total 10181
telemt_handshake_timeouts_total 35542
telemt_upstream_connect_attempt_total 23822
telemt_upstream_connect_success_total 20892
telemt_upstream_connect_fail_total 2930
telemt_upstream_connect_attempts_per_request{bucket="1"} 23822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2930
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 15201
telemt_me_reconnect_success_total 14359
telemt_me_reader_eof_total 15208
telemt_me_idle_close_by_peer_total 15206
telemt_me_route_drop_no_conn_total 245399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505043
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2277
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 757
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14533
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14337
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 507270
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 4948968826 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 141146605428 (131.45 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71379.2 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033864
telemt_connections_bad_total 7698
telemt_handshake_timeouts_total 100314
telemt_upstream_connect_attempt_total 19334
telemt_upstream_connect_success_total 19094
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 19334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 792
telemt_me_reconnect_attempts_total 28044
telemt_me_reconnect_success_total 14427
telemt_me_reader_eof_total 15506
telemt_me_idle_close_by_peer_total 15506
telemt_me_route_drop_no_conn_total 341202
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886177
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2517
telemt_desync_full_logged_total 744
telemt_desync_suppressed_total 1773
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15038
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14416
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 886985
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 10503601277 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 271835928353 (253.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71379.8 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753742
telemt_connections_bad_total 67185
telemt_handshake_timeouts_total 72299
telemt_upstream_connect_attempt_total 19616
telemt_upstream_connect_success_total 19616
telemt_upstream_connect_attempts_per_request{bucket="1"} 19616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 739
telemt_me_reconnect_attempts_total 17096
telemt_me_reconnect_success_total 16039
telemt_me_reader_eof_total 17033
telemt_me_idle_close_by_peer_total 17032
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 236737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591851
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1277
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 792
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16228
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16015
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 591223
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 6816863240 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 171097233904 (159.35 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71379.5 (19h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801905
telemt_connections_bad_total 6083
telemt_handshake_timeouts_total 7741
telemt_upstream_connect_attempt_total 19223
telemt_upstream_connect_success_total 19143
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 19223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 807
telemt_me_reconnect_attempts_total 19245
telemt_me_reconnect_success_total 15450
telemt_me_reader_eof_total 16341
telemt_me_idle_close_by_peer_total 16341
telemt_me_route_drop_no_conn_total 277130
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3051
telemt_desync_full_logged_total 1143
telemt_desync_suppressed_total 1908
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1235
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15763
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15450
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 727991
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 11251326603 (10.48 GB)
telemt_user_octets_to_client{user="hello"} 266904618678 (248.57 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 115
```