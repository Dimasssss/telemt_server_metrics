# Server Metrics 2026-03-12 12:52:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 24849.3 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852514
telemt_connections_bad_total 3789
telemt_handshake_timeouts_total 7022
telemt_upstream_connect_attempt_total 4933
telemt_upstream_connect_success_total 4903
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 334
telemt_me_reconnect_attempts_total 7521
telemt_me_reconnect_success_total 3625
telemt_me_reader_eof_total 3890
telemt_me_idle_close_by_peer_total 3890
telemt_me_route_drop_no_conn_total 301928
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817258
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4303
telemt_desync_full_logged_total 1092
telemt_desync_suppressed_total 3211
telemt_desync_frames_bucket_total{bucket="1_2"} 1077
telemt_desync_frames_bucket_total{bucket="3_10"} 1561
telemt_desync_frames_bucket_total{bucket="gt_10"} 1665
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3786
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3612
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 817086
telemt_user_connections_current{user="hello"} 1549
telemt_user_octets_from_client{user="hello"} 13840683284 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 236701276368 (220.45 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54469.9 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426175
telemt_connections_bad_total 5255
telemt_handshake_timeouts_total 22831
telemt_upstream_connect_attempt_total 13219
telemt_upstream_connect_success_total 13212
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1056
telemt_me_reconnect_attempts_total 10365
telemt_me_reconnect_success_total 10308
telemt_me_reader_eof_total 10954
telemt_me_idle_close_by_peer_total 10954
telemt_me_route_drop_no_conn_total 122296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375753
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1260
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10403
telemt_me_writer_restored_same_endpoint_total 10299
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 376210
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 5077992011 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 134327559246 (125.10 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54469.8 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952431
telemt_connections_bad_total 5163
telemt_handshake_timeouts_total 71912
telemt_upstream_connect_attempt_total 13269
telemt_upstream_connect_success_total 13264
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10273
telemt_me_reconnect_success_total 10183
telemt_me_reader_eof_total 10726
telemt_me_idle_close_by_peer_total 10726
telemt_me_route_drop_no_conn_total 236557
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2966
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 2074
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 1487
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10213
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10142
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 658754
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 8564869324 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 207010376649 (192.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54470.2 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536438
telemt_connections_bad_total 7640
telemt_handshake_timeouts_total 50248
telemt_upstream_connect_attempt_total 14638
telemt_upstream_connect_success_total 14580
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1270
telemt_me_reconnect_attempts_total 13084
telemt_me_reconnect_success_total 11852
telemt_me_reader_eof_total 12574
telemt_me_idle_close_by_peer_total 12574
telemt_me_route_drop_no_conn_total 180333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448179
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 901
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11980
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11831
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 447691
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 5068049228 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 177942395220 (165.72 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54470.0 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603244
telemt_connections_bad_total 1710
telemt_handshake_timeouts_total 4881
telemt_upstream_connect_attempt_total 17490
telemt_upstream_connect_success_total 17278
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 17490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 21771
telemt_me_reconnect_success_total 14547
telemt_me_reader_eof_total 15258
telemt_me_idle_close_by_peer_total 15258
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 203923
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563275
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2340
telemt_desync_full_logged_total 792
telemt_desync_suppressed_total 1548
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 14913
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14520
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 563188
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 6503784308 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 144801432680 (134.86 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 119
```