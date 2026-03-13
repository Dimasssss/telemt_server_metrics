# Server Metrics 2026-03-13 03:10:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76290.4 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2122231
telemt_connections_bad_total 27999
telemt_handshake_timeouts_total 22823
telemt_upstream_connect_attempt_total 15115
telemt_upstream_connect_success_total 15031
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1289
telemt_me_reconnect_attempts_total 20093
telemt_me_reconnect_success_total 11231
telemt_me_reader_eof_total 12128
telemt_me_idle_close_by_peer_total 12127
telemt_me_route_drop_no_conn_total 815373
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1953078
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8752
telemt_desync_full_logged_total 2277
telemt_desync_suppressed_total 6475
telemt_desync_frames_bucket_total{bucket="1_2"} 2305
telemt_desync_frames_bucket_total{bucket="3_10"} 3157
telemt_desync_frames_bucket_total{bucket="gt_10"} 3290
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11663
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11218
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 1952536
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 28431410248 (26.48 GB)
telemt_user_octets_to_client{user="hello"} 676723444664 (630.25 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 105911.0 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864643
telemt_connections_bad_total 11842
telemt_handshake_timeouts_total 35390
telemt_upstream_connect_attempt_total 27002
telemt_upstream_connect_success_total 26973
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3458
telemt_me_reconnect_attempts_total 20167
telemt_me_reconnect_success_total 20057
telemt_me_reader_eof_total 21372
telemt_me_idle_close_by_peer_total 21372
telemt_me_route_drop_no_conn_total 277718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3102
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 2127
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20252
telemt_me_writer_restored_same_endpoint_total 20048
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 783838
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 12498803880 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 298955874847 (278.42 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 105910.9 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1791438
telemt_connections_bad_total 9693
telemt_handshake_timeouts_total 119862
telemt_upstream_connect_attempt_total 24706
telemt_upstream_connect_success_total 24696
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1619
telemt_me_reconnect_attempts_total 20337
telemt_me_reconnect_success_total 19072
telemt_me_reader_eof_total 20201
telemt_me_idle_close_by_peer_total 20200
telemt_me_route_drop_no_conn_total 582989
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1411821
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5034
telemt_desync_full_logged_total 1541
telemt_desync_suppressed_total 3493
telemt_desync_frames_bucket_total{bucket="1_2"} 805
telemt_desync_frames_bucket_total{bucket="3_10"} 1824
telemt_desync_frames_bucket_total{bucket="gt_10"} 2405
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19251
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19031
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1411415
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 20415013784 (19.01 GB)
telemt_user_octets_to_client{user="hello"} 507212674261 (472.38 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 105911.2 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117275
telemt_connections_bad_total 13144
telemt_handshake_timeouts_total 74015
telemt_upstream_connect_attempt_total 36928
telemt_upstream_connect_success_total 34651
telemt_upstream_connect_fail_total 2140
telemt_upstream_connect_attempts_per_request{bucket="1"} 36654
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2139
telemt_me_keepalive_timeout_total 11371
telemt_me_reconnect_attempts_total 32440
telemt_me_reconnect_success_total 23514
telemt_me_reader_eof_total 25388
telemt_me_idle_close_by_peer_total 25381
telemt_me_route_drop_no_conn_total 395832
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 958415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 23946
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23490
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 963585
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 14641817957 (13.64 GB)
telemt_user_octets_to_client{user="hello"} 378327836258 (352.35 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 105911.0 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1236312
telemt_connections_bad_total 12634
telemt_handshake_timeouts_total 9619
telemt_upstream_connect_attempt_total 33376
telemt_upstream_connect_success_total 32969
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 33376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 1903
telemt_me_reconnect_attempts_total 41429
telemt_me_reconnect_success_total 27699
telemt_me_reader_eof_total 29149
telemt_me_idle_close_by_peer_total 29149
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 461434
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1143811
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4246
telemt_desync_full_logged_total 1512
telemt_desync_suppressed_total 2734
telemt_desync_frames_bucket_total{bucket="1_2"} 1281
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1570
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 28446
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27650
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 1143666
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 14144748612 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 395375293208 (368.22 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 47
```