# Server Metrics 2026-03-12 23:46:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64057.3 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1966072
telemt_connections_bad_total 26091
telemt_handshake_timeouts_total 21288
telemt_upstream_connect_attempt_total 12711
telemt_upstream_connect_success_total 12639
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 18263
telemt_me_reconnect_success_total 9405
telemt_me_reader_eof_total 10152
telemt_me_idle_close_by_peer_total 10151
telemt_me_route_drop_no_conn_total 764831
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1827764
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8596
telemt_desync_full_logged_total 2244
telemt_desync_suppressed_total 6352
telemt_desync_frames_bucket_total{bucket="1_2"} 2267
telemt_desync_frames_bucket_total{bucket="3_10"} 3094
telemt_desync_frames_bucket_total{bucket="gt_10"} 3235
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9816
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9392
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 1827226
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 27300713756 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 646846986440 (602.42 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93677.6 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812387
telemt_connections_bad_total 11738
telemt_handshake_timeouts_total 31593
telemt_upstream_connect_attempt_total 23744
telemt_upstream_connect_success_total 23715
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3429
telemt_me_reconnect_attempts_total 17475
telemt_me_reconnect_success_total 17378
telemt_me_reader_eof_total 18491
telemt_me_idle_close_by_peer_total 18491
telemt_me_route_drop_no_conn_total 262390
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734829
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3018
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17550
telemt_me_writer_restored_same_endpoint_total 17369
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 736709
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 12143527952 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 283841913683 (264.35 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93677.5 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691362
telemt_connections_bad_total 8290
telemt_handshake_timeouts_total 113419
telemt_upstream_connect_attempt_total 21776
telemt_upstream_connect_success_total 21770
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1234
telemt_me_reconnect_attempts_total 17983
telemt_me_reconnect_success_total 16729
telemt_me_reader_eof_total 17688
telemt_me_idle_close_by_peer_total 17687
telemt_me_route_drop_no_conn_total 554804
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1323551
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16890
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16688
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 1323156
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 19823400636 (18.46 GB)
telemt_user_octets_to_client{user="hello"} 486110011701 (452.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93677.6 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1048042
telemt_connections_bad_total 13014
telemt_handshake_timeouts_total 71605
telemt_upstream_connect_attempt_total 33010
telemt_upstream_connect_success_total 30750
telemt_upstream_connect_fail_total 2123
telemt_upstream_connect_attempts_per_request{bucket="1"} 32736
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2122
telemt_me_keepalive_timeout_total 11252
telemt_me_reconnect_attempts_total 28044
telemt_me_reconnect_success_total 20206
telemt_me_reader_eof_total 21876
telemt_me_idle_close_by_peer_total 21869
telemt_me_route_drop_no_conn_total 370863
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 905796
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20571
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20184
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 911016
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 14318957889 (13.34 GB)
telemt_user_octets_to_client{user="hello"} 362610685318 (337.71 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93677.6 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164499
telemt_connections_bad_total 12546
telemt_handshake_timeouts_total 9282
telemt_upstream_connect_attempt_total 28399
telemt_upstream_connect_success_total 28048
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 28399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1462
telemt_me_reconnect_attempts_total 34406
telemt_me_reconnect_success_total 23365
telemt_me_reader_eof_total 24583
telemt_me_idle_close_by_peer_total 24583
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 434579
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073708
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4044
telemt_desync_full_logged_total 1417
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1178
telemt_desync_frames_bucket_total{bucket="3_10"} 1348
telemt_desync_frames_bucket_total{bucket="gt_10"} 1518
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 23984
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23320
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 1073566
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 13539091480 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 378055399116 (352.09 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 39
```