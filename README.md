# Server Metrics 2026-03-14 03:05:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 162397.0 (45h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4693793
telemt_connections_bad_total 39856
telemt_handshake_timeouts_total 108754
telemt_upstream_connect_attempt_total 34337
telemt_upstream_connect_success_total 34109
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 34337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 6729
telemt_me_reconnect_attempts_total 33821
telemt_me_reconnect_success_total 23680
telemt_me_reader_eof_total 25396
telemt_me_idle_close_by_peer_total 25395
telemt_me_route_drop_no_conn_total 1783140
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4305420
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16769
telemt_desync_full_logged_total 4523
telemt_desync_suppressed_total 12246
telemt_desync_frames_bucket_total{bucket="1_2"} 4189
telemt_desync_frames_bucket_total{bucket="3_10"} 6396
telemt_desync_frames_bucket_total{bucket="gt_10"} 6184
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 24336
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23667
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 4307018
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 63099766492 (58.77 GB)
telemt_user_octets_to_client{user="hello"} 1360698248173 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62060.8 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704580
telemt_connections_bad_total 51115
telemt_handshake_timeouts_total 13177
telemt_upstream_connect_attempt_total 17271
telemt_upstream_connect_success_total 17018
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 17271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 2087
telemt_me_reconnect_attempts_total 15353
telemt_me_reconnect_success_total 11906
telemt_me_reader_eof_total 12635
telemt_me_idle_close_by_peer_total 12634
telemt_me_route_drop_no_conn_total 236446
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564692
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1697
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12175
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11898
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 566650
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 6034482789 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 183286960604 (170.70 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 192017.5 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3389911
telemt_connections_bad_total 35663
telemt_handshake_timeouts_total 223479
telemt_upstream_connect_attempt_total 43321
telemt_upstream_connect_success_total 43300
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10427
telemt_me_reconnect_attempts_total 38387
telemt_me_reconnect_success_total 33422
telemt_me_reader_eof_total 35502
telemt_me_idle_close_by_peer_total 35501
telemt_me_route_drop_no_conn_total 1161173
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2822153
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9362
telemt_desync_full_logged_total 3129
telemt_desync_suppressed_total 6233
telemt_desync_frames_bucket_total{bucket="1_2"} 1612
telemt_desync_frames_bucket_total{bucket="3_10"} 3385
telemt_desync_frames_bucket_total{bucket="gt_10"} 4365
telemt_pool_swap_total 181
telemt_me_writer_removed_unexpected_total 33891
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33381
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2821377
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 45255292524 (42.15 GB)
telemt_user_octets_to_client{user="hello"} 1006613642437 (937.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 192020.1 (53h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2267176
telemt_connections_bad_total 22986
telemt_handshake_timeouts_total 249002
telemt_upstream_connect_attempt_total 60238
telemt_upstream_connect_success_total 57771
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 59964
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20438
telemt_me_reconnect_attempts_total 50216
telemt_me_reconnect_success_total 41182
telemt_me_reader_eof_total 44174
telemt_me_idle_close_by_peer_total 44167
telemt_me_route_drop_no_conn_total 774022
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1806374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3814
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2586
telemt_desync_frames_bucket_total{bucket="1_2"} 1017
telemt_desync_frames_bucket_total{bucket="3_10"} 1589
telemt_desync_frames_bucket_total{bucket="gt_10"} 1208
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 41817
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41158
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 635
telemt_user_connections_total{user="hello"} 1812311
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 27632729027 (25.73 GB)
telemt_user_octets_to_client{user="hello"} 668204760514 (622.31 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61453.7 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705009
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8673
telemt_upstream_connect_attempt_total 15945
telemt_upstream_connect_success_total 15512
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 15945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 47085
telemt_me_reconnect_success_total 12425
telemt_me_reader_eof_total 13818
telemt_me_idle_close_by_peer_total 13817
telemt_me_route_drop_no_conn_total 267628
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656878
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13616
telemt_me_refill_failed_total 1079
telemt_me_writer_restored_same_endpoint_total 12420
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1191
telemt_user_connections_total{user="hello"} 656757
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 11988237456 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 213495718920 (198.83 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 40
```