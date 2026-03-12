# Server Metrics 2026-03-12 20:57:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53954.3 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833570
telemt_connections_bad_total 22350
telemt_handshake_timeouts_total 20141
telemt_upstream_connect_attempt_total 10478
telemt_upstream_connect_success_total 10417
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 16558
telemt_me_reconnect_success_total 7707
telemt_me_reader_eof_total 8332
telemt_me_idle_close_by_peer_total 8331
telemt_me_route_drop_no_conn_total 720294
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1710066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8335
telemt_desync_full_logged_total 2153
telemt_desync_suppressed_total 6182
telemt_desync_frames_bucket_total{bucket="1_2"} 2185
telemt_desync_frames_bucket_total{bucket="3_10"} 3010
telemt_desync_frames_bucket_total{bucket="gt_10"} 3140
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8094
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7694
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 1709549
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 26237200664 (24.44 GB)
telemt_user_octets_to_client{user="hello"} 601715541884 (560.39 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83574.6 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768794
telemt_connections_bad_total 11537
telemt_handshake_timeouts_total 30507
telemt_upstream_connect_attempt_total 21122
telemt_upstream_connect_success_total 21093
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3390
telemt_me_reconnect_attempts_total 15367
telemt_me_reconnect_success_total 15275
telemt_me_reader_eof_total 16241
telemt_me_idle_close_by_peer_total 16241
telemt_me_route_drop_no_conn_total 248053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2952
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 2047
telemt_desync_frames_bucket_total{bucket="1_2"} 1151
telemt_desync_frames_bucket_total{bucket="3_10"} 975
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 15430
telemt_me_writer_restored_same_endpoint_total 15266
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 695323
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 11839835492 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 268045672131 (249.64 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83574.4 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1588745
telemt_connections_bad_total 7549
telemt_handshake_timeouts_total 109185
telemt_upstream_connect_attempt_total 19579
telemt_upstream_connect_success_total 19573
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1208
telemt_me_reconnect_attempts_total 16292
telemt_me_reconnect_success_total 15045
telemt_me_reader_eof_total 15882
telemt_me_idle_close_by_peer_total 15881
telemt_me_route_drop_no_conn_total 524708
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1227841
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4850
telemt_desync_full_logged_total 1491
telemt_desync_suppressed_total 3359
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1753
telemt_desync_frames_bucket_total{bucket="gt_10"} 2327
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15188
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15004
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1227448
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 19295962608 (17.97 GB)
telemt_user_octets_to_client{user="hello"} 457635157369 (426.21 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83574.9 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976979
telemt_connections_bad_total 12973
telemt_handshake_timeouts_total 70836
telemt_upstream_connect_attempt_total 21300
telemt_upstream_connect_success_total 21214
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 21300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1674
telemt_me_reconnect_attempts_total 24777
telemt_me_reconnect_success_total 17050
telemt_me_reader_eof_total 18212
telemt_me_idle_close_by_peer_total 18212
telemt_me_route_drop_no_conn_total 348758
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849340
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1824
telemt_desync_full_logged_total 604
telemt_desync_suppressed_total 1220
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 612
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17427
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17029
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 848690
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 13312385888 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 345961916012 (322.20 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83574.8 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096316
telemt_connections_bad_total 12503
telemt_handshake_timeouts_total 9013
telemt_upstream_connect_attempt_total 25839
telemt_upstream_connect_success_total 25524
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 25839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 1426
telemt_me_reconnect_attempts_total 32381
telemt_me_reconnect_success_total 21343
telemt_me_reader_eof_total 22428
telemt_me_idle_close_by_peer_total 22428
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 409926
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006899
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3821
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2491
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1265
telemt_desync_frames_bucket_total{bucket="gt_10"} 1448
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 21930
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21299
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 1006762
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 12489466472 (11.63 GB)
telemt_user_octets_to_client{user="hello"} 354295797080 (329.96 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 109
```