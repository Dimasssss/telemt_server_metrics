# Server Metrics 2026-03-13 08:52:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96804.7 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2729882
telemt_connections_bad_total 36351
telemt_handshake_timeouts_total 36289
telemt_upstream_connect_attempt_total 18934
telemt_upstream_connect_success_total 18830
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 22897
telemt_me_reconnect_success_total 14021
telemt_me_reader_eof_total 15088
telemt_me_idle_close_by_peer_total 15087
telemt_me_route_drop_no_conn_total 1013952
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2494607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11168
telemt_desync_full_logged_total 2884
telemt_desync_suppressed_total 8284
telemt_desync_frames_bucket_total{bucket="1_2"} 2865
telemt_desync_frames_bucket_total{bucket="3_10"} 4175
telemt_desync_frames_bucket_total{bucket="gt_10"} 4128
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14492
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 14008
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2494175
telemt_user_connections_current{user="hello"} 1571
telemt_user_octets_from_client{user="hello"} 35186391268 (32.77 GB)
telemt_user_octets_to_client{user="hello"} 824154471072 (767.55 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 126425.2 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113607
telemt_connections_bad_total 13898
telemt_handshake_timeouts_total 95097
telemt_upstream_connect_attempt_total 31495
telemt_upstream_connect_success_total 31464
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23661
telemt_me_reconnect_success_total 23538
telemt_me_reader_eof_total 25089
telemt_me_idle_close_by_peer_total 25089
telemt_me_route_drop_no_conn_total 341755
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4254
telemt_desync_full_logged_total 1297
telemt_desync_suppressed_total 2957
telemt_desync_frames_bucket_total{bucket="1_2"} 1558
telemt_desync_frames_bucket_total{bucket="3_10"} 1402
telemt_desync_frames_bucket_total{bucket="gt_10"} 1294
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 23768
telemt_me_writer_restored_same_endpoint_total 23529
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 965522
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 14748916348 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 356756701827 (332.26 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 126425.1 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2160407
telemt_connections_bad_total 23766
telemt_handshake_timeouts_total 144160
telemt_upstream_connect_attempt_total 29033
telemt_upstream_connect_success_total 29023
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1763
telemt_me_reconnect_attempts_total 23662
telemt_me_reconnect_success_total 22379
telemt_me_reader_eof_total 23702
telemt_me_idle_close_by_peer_total 23701
telemt_me_route_drop_no_conn_total 701191
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1724617
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5772
telemt_desync_full_logged_total 1827
telemt_desync_suppressed_total 3945
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 2104
telemt_desync_frames_bucket_total{bucket="gt_10"} 2722
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22598
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22338
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 1724061
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 30234430412 (28.16 GB)
telemt_user_octets_to_client{user="hello"} 625670206733 (582.70 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 126425.5 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1373012
telemt_connections_bad_total 14223
telemt_handshake_timeouts_total 84457
telemt_upstream_connect_attempt_total 42043
telemt_upstream_connect_success_total 39742
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41769
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11453
telemt_me_reconnect_attempts_total 36532
telemt_me_reconnect_success_total 27592
telemt_me_reader_eof_total 29714
telemt_me_idle_close_by_peer_total 29707
telemt_me_route_drop_no_conn_total 482017
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1142746
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2195
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 28065
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27568
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 1147508
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 17279832485 (16.09 GB)
telemt_user_octets_to_client{user="hello"} 456308932310 (424.97 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 126425.3 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1519676
telemt_connections_bad_total 32142
telemt_handshake_timeouts_total 12533
telemt_upstream_connect_attempt_total 40150
telemt_upstream_connect_success_total 39666
telemt_upstream_connect_fail_total 484
telemt_upstream_connect_attempts_per_request{bucket="1"} 40150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 484
telemt_me_keepalive_timeout_total 2159
telemt_me_reconnect_attempts_total 47121
telemt_me_reconnect_success_total 33375
telemt_me_reader_eof_total 34986
telemt_me_idle_close_by_peer_total 34986
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 555984
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390945
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4868
telemt_desync_full_logged_total 1742
telemt_desync_suppressed_total 3126
telemt_desync_frames_bucket_total{bucket="1_2"} 1489
telemt_desync_frames_bucket_total{bucket="3_10"} 1568
telemt_desync_frames_bucket_total{bucket="gt_10"} 1811
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34170
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 33314
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 795
telemt_user_connections_total{user="hello"} 1390749
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 18064199500 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 483674867428 (450.46 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 100
```