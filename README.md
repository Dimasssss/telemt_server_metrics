# Server Metrics 2026-03-14 16:54:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 13008.5 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522090
telemt_connections_bad_total 26819
telemt_handshake_timeouts_total 7182
telemt_upstream_connect_attempt_total 2723
telemt_upstream_connect_success_total 2710
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 2791
telemt_me_reconnect_success_total 1994
telemt_me_reader_eof_total 2081
telemt_me_idle_close_by_peer_total 2081
telemt_me_route_drop_no_conn_total 201560
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464958
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1620
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1151
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2049
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 464880
telemt_user_connections_current{user="hello"} 1905
telemt_user_octets_from_client{user="hello"} 8378884212 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 143596886564 (133.74 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 13013.9 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211603
telemt_connections_bad_total 21155
telemt_handshake_timeouts_total 6385
telemt_upstream_connect_attempt_total 2815
telemt_upstream_connect_success_total 2783
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2850
telemt_me_reconnect_success_total 2068
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2153
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 65235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170511
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 613
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2144
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2053
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 170460
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 2499588756 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 67921908696 (63.26 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 12876.8 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432407
telemt_connections_bad_total 1485
telemt_handshake_timeouts_total 91323
telemt_upstream_connect_attempt_total 2719
telemt_upstream_connect_success_total 2711
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 5908
telemt_me_reconnect_success_total 2009
telemt_me_reader_eof_total 2166
telemt_me_idle_close_by_peer_total 2166
telemt_me_route_drop_no_conn_total 109717
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294728
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 738
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2140
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1976
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 294615
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 4268420788 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 107676392776 (100.28 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 12731.3 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229312
telemt_connections_bad_total 48966
telemt_handshake_timeouts_total 36230
telemt_upstream_connect_attempt_total 3241
telemt_upstream_connect_success_total 3240
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3456
telemt_me_reconnect_success_total 2544
telemt_me_reader_eof_total 2633
telemt_me_idle_close_by_peer_total 2633
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 50964
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2596
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2537
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 140967
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 2282523696 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 46836133812 (43.62 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 13026.8 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203289
telemt_connections_bad_total 721
telemt_handshake_timeouts_total 2745
telemt_upstream_connect_attempt_total 2958
telemt_upstream_connect_success_total 2898
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 2957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 2866
telemt_me_reconnect_success_total 2200
telemt_me_reader_eof_total 2309
telemt_me_idle_close_by_peer_total 2309
telemt_me_route_drop_no_conn_total 67140
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186967
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2266
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2182
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 186983
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 2995732632 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 73989287800 (68.91 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 101
```