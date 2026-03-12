# Server Metrics 2026-03-12 10:55:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17809.7 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594825
telemt_connections_bad_total 1476
telemt_handshake_timeouts_total 3525
telemt_upstream_connect_attempt_total 3413
telemt_upstream_connect_success_total 3391
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 307
telemt_me_reconnect_attempts_total 6364
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2683
telemt_me_idle_close_by_peer_total 2683
telemt_me_route_drop_no_conn_total 204845
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2763
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1018
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2621
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2463
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 572456
telemt_user_connections_current{user="hello"} 1519
telemt_user_octets_from_client{user="hello"} 10305046800 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 155618069028 (144.93 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47430.2 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320128
telemt_connections_bad_total 3501
telemt_handshake_timeouts_total 9838
telemt_upstream_connect_attempt_total 11851
telemt_upstream_connect_success_total 11845
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 9345
telemt_me_reconnect_success_total 9294
telemt_me_reader_eof_total 9881
telemt_me_idle_close_by_peer_total 9881
telemt_me_route_drop_no_conn_total 92900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287299
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 654
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9376
telemt_me_writer_restored_same_endpoint_total 9285
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 287732
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 3967341239 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 104207026790 (97.05 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47430.2 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786582
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 57460
telemt_upstream_connect_attempt_total 11822
telemt_upstream_connect_success_total 11817
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 591
telemt_me_reconnect_attempts_total 9178
telemt_me_reconnect_success_total 9101
telemt_me_reader_eof_total 9568
telemt_me_idle_close_by_peer_total 9568
telemt_me_route_drop_no_conn_total 179762
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511119
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2316
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1632
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9118
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9060
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 511370
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 6290749344 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 163725501553 (152.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47430.7 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409749
telemt_connections_bad_total 2488
telemt_handshake_timeouts_total 32341
telemt_upstream_connect_attempt_total 12700
telemt_upstream_connect_success_total 12649
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 12700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 847
telemt_me_reconnect_attempts_total 10322
telemt_me_reconnect_success_total 10282
telemt_me_reader_eof_total 10910
telemt_me_idle_close_by_peer_total 10910
telemt_me_route_drop_no_conn_total 137603
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 707
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10352
telemt_me_writer_restored_same_endpoint_total 10261
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 345787
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 4092079572 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 132580654828 (123.48 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47430.3 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465296
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 3435
telemt_upstream_connect_attempt_total 15251
telemt_upstream_connect_success_total 15071
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 15251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 639
telemt_me_reconnect_attempts_total 14220
telemt_me_reconnect_success_total 12695
telemt_me_reader_eof_total 13210
telemt_me_idle_close_by_peer_total 13210
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 151417
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437940
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1827
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 542
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12866
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12670
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 437862
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 4932361164 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 106587262280 (99.27 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 136
```