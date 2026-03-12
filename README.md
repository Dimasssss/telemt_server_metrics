# Server Metrics 2026-03-12 22:14:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 58545.1 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1907945
telemt_connections_bad_total 26060
telemt_handshake_timeouts_total 20937
telemt_upstream_connect_attempt_total 11506
telemt_upstream_connect_success_total 11440
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 11506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 599
telemt_me_reconnect_attempts_total 17355
telemt_me_reconnect_success_total 8500
telemt_me_reader_eof_total 9181
telemt_me_idle_close_by_peer_total 9180
telemt_me_route_drop_no_conn_total 745997
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1775567
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8477
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 6272
telemt_desync_frames_bucket_total{bucket="1_2"} 2235
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 3190
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8897
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8487
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 1775045
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 26879432936 (25.03 GB)
telemt_user_octets_to_client{user="hello"} 627442001156 (584.35 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88165.7 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792146
telemt_connections_bad_total 11697
telemt_handshake_timeouts_total 31236
telemt_upstream_connect_attempt_total 22249
telemt_upstream_connect_success_total 22220
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3409
telemt_me_reconnect_attempts_total 16277
telemt_me_reconnect_success_total 16182
telemt_me_reader_eof_total 17215
telemt_me_idle_close_by_peer_total 17215
telemt_me_route_drop_no_conn_total 256541
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715364
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2996
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 2065
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16347
telemt_me_writer_restored_same_endpoint_total 16173
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 717244
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 12057135448 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 278057506463 (258.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 88172.5 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645086
telemt_connections_bad_total 7766
telemt_handshake_timeouts_total 113246
telemt_upstream_connect_attempt_total 20548
telemt_upstream_connect_success_total 20542
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 20548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1217
telemt_me_reconnect_attempts_total 17045
telemt_me_reconnect_success_total 15796
telemt_me_reader_eof_total 16689
telemt_me_idle_close_by_peer_total 16688
telemt_me_route_drop_no_conn_total 541469
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278999
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4968
telemt_desync_full_logged_total 1524
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 790
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15946
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15755
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 1278605
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 19689173976 (18.34 GB)
telemt_user_octets_to_client{user="hello"} 472990446061 (440.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 88165.8 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014089
telemt_connections_bad_total 12997
telemt_handshake_timeouts_total 71246
telemt_upstream_connect_attempt_total 22497
telemt_upstream_connect_success_total 22406
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 22497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1685
telemt_me_reconnect_attempts_total 25752
telemt_me_reconnect_success_total 18022
telemt_me_reader_eof_total 19251
telemt_me_idle_close_by_peer_total 19251
telemt_me_route_drop_no_conn_total 362868
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883141
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18408
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18001
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 882490
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 14174841552 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 352915767096 (328.68 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 88166.0 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133892
telemt_connections_bad_total 12533
telemt_handshake_timeouts_total 9178
telemt_upstream_connect_attempt_total 27035
telemt_upstream_connect_success_total 26699
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 27035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 1442
telemt_me_reconnect_attempts_total 33341
telemt_me_reconnect_success_total 22300
telemt_me_reader_eof_total 23437
telemt_me_idle_close_by_peer_total 23437
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 424849
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043606
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3902
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 2543
telemt_desync_frames_bucket_total{bucket="1_2"} 1147
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 22903
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22256
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 1043467
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 12829722612 (11.95 GB)
telemt_user_octets_to_client{user="hello"} 370272398564 (344.84 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 49
```