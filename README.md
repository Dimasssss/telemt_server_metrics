# Server Metrics 2026-03-12 08:42:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9858.6 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302560
telemt_connections_bad_total 1317
telemt_handshake_timeouts_total 2170
telemt_upstream_connect_attempt_total 1885
telemt_upstream_connect_success_total 1874
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 1365
telemt_me_reader_eof_total 1410
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 101101
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292257
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1403
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 292157
telemt_user_connections_current{user="hello"} 1218
telemt_user_octets_from_client{user="hello"} 4429970000 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 81563361612 (75.96 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39479.3 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216833
telemt_connections_bad_total 2783
telemt_handshake_timeouts_total 7427
telemt_upstream_connect_attempt_total 10143
telemt_upstream_connect_success_total 10137
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 610
telemt_me_reconnect_attempts_total 8032
telemt_me_reconnect_success_total 7990
telemt_me_reader_eof_total 8484
telemt_me_idle_close_by_peer_total 8484
telemt_me_route_drop_no_conn_total 62448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8052
telemt_me_writer_restored_same_endpoint_total 7981
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 190480
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 2878098591 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 73730403298 (68.67 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39479.1 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613780
telemt_connections_bad_total 2880
telemt_handshake_timeouts_total 45550
telemt_upstream_connect_attempt_total 10235
telemt_upstream_connect_success_total 10230
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 7980
telemt_me_reconnect_success_total 7910
telemt_me_reader_eof_total 8303
telemt_me_idle_close_by_peer_total 8303
telemt_me_route_drop_no_conn_total 123360
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 567
telemt_desync_frames_bucket_total{bucket="gt_10"} 864
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7905
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7869
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 356021
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 4258867364 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 121278368933 (112.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39479.5 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294444
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 19706
telemt_upstream_connect_attempt_total 10838
telemt_upstream_connect_success_total 10795
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 772
telemt_me_reconnect_attempts_total 8863
telemt_me_reconnect_success_total 8831
telemt_me_reader_eof_total 9375
telemt_me_idle_close_by_peer_total 9375
telemt_me_route_drop_no_conn_total 98631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246112
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 465
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8886
telemt_me_writer_restored_same_endpoint_total 8810
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 245937
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 2873740024 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 85427726732 (79.56 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39479.4 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326651
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 2495
telemt_upstream_connect_attempt_total 13050
telemt_upstream_connect_success_total 12898
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 13050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 563
telemt_me_reconnect_attempts_total 12439
telemt_me_reconnect_success_total 10925
telemt_me_reader_eof_total 11381
telemt_me_idle_close_by_peer_total 11381
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 104778
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308198
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1261
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 11071
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10904
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 308140
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 3276832528 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 74524765168 (69.41 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 101
```