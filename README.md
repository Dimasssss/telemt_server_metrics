# Server Metrics 2026-03-04 13:45:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 59707.0 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074353
telemt_connections_bad_total 13902
telemt_handshake_timeouts_total 17966
telemt_upstream_connect_attempt_total 35435
telemt_upstream_connect_success_total 35274
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 35274
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 397
telemt_me_reconnect_attempts_total 7474
telemt_me_reconnect_success_total 7418
telemt_me_reader_eof_total 7646
telemt_me_idle_close_by_peer_total 7645
telemt_me_route_drop_no_conn_total 387173
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1808
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7646
telemt_me_writer_restored_same_endpoint_total 7396
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 849571
telemt_user_connections_current{user="hello"} 1115
telemt_user_octets_from_client{user="hello"} 9633525064 (8.97 GB)
telemt_user_octets_to_client{user="hello"} 285895987800 (266.26 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 59703.5 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415533
telemt_connections_bad_total 3562
telemt_handshake_timeouts_total 29164
telemt_upstream_connect_attempt_total 107075
telemt_upstream_connect_success_total 105461
telemt_upstream_connect_fail_total 769
telemt_upstream_connect_attempts_per_request{bucket="1"} 105455
telemt_upstream_connect_attempts_per_request{bucket="2"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 769
telemt_me_keepalive_timeout_total 1455
telemt_me_reconnect_attempts_total 58798
telemt_me_reconnect_success_total 58703
telemt_me_reader_eof_total 60208
telemt_me_idle_close_by_peer_total 60207
telemt_me_route_drop_no_conn_total 168165
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 251
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 60288
telemt_me_writer_restored_same_endpoint_total 58678
telemt_me_writer_removed_unexpected_minus_restored_total 1610
telemt_user_connections_total{user="hello"} 320816
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 4131724100 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 101905621500 (94.91 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 59702.4 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812824
telemt_connections_bad_total 177533
telemt_handshake_timeouts_total 28872
telemt_upstream_connect_attempt_total 83056
telemt_upstream_connect_success_total 82539
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 82538
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1082
telemt_me_reconnect_attempts_total 37949
telemt_me_reconnect_success_total 37851
telemt_me_reader_eof_total 39845
telemt_me_idle_close_by_peer_total 39841
telemt_me_route_drop_no_conn_total 298293
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1626
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1078
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39857
telemt_me_writer_restored_same_endpoint_total 37829
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 569153
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 12153302140 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 193239688456 (179.97 GB)
telemt_user_unique_ips_current{user="hello"} 98
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 6379.6 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78485
telemt_connections_bad_total 7525
telemt_handshake_timeouts_total 1172
telemt_upstream_connect_attempt_total 2706
telemt_upstream_connect_success_total 2706
telemt_upstream_connect_attempts_per_request{bucket="1"} 2706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1034
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 310
telemt_me_reader_eof_total 299
telemt_me_idle_close_by_peer_total 299
telemt_me_route_drop_no_conn_total 27801
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 299
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 68635
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 1185072476 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 43722481808 (40.72 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 6739.0 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119630
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1986
telemt_upstream_connect_attempt_total 4730
telemt_upstream_connect_success_total 4713
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4713
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1201
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1235
telemt_me_idle_close_by_peer_total 1235
telemt_me_route_drop_no_conn_total 41320
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 316
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 103079
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 1123249868 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 28448002784 (26.49 GB)
telemt_user_unique_ips_current{user="hello"} 77
```