# Server Metrics 2026-03-06 20:07:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 7171.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166640
telemt_connections_bad_total 1708
telemt_handshake_timeouts_total 6788
telemt_upstream_connect_attempt_total 10601
telemt_upstream_connect_success_total 10499
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 322
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 3316
telemt_me_reader_eof_total 4334
telemt_me_idle_close_by_peer_total 4334
telemt_me_route_drop_no_conn_total 65561
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 601
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4358
telemt_me_writer_restored_same_endpoint_total 3310
telemt_me_writer_removed_unexpected_minus_restored_total 1048
telemt_user_connections_total{user="hello"} 145885
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 2285865160 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 50877461092 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 7171.4 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59690
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 2463
telemt_upstream_connect_attempt_total 14025
telemt_upstream_connect_success_total 14023
telemt_upstream_connect_attempts_per_request{bucket="1"} 14023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 5141
telemt_me_reconnect_success_total 5135
telemt_me_reader_eof_total 7078
telemt_me_idle_close_by_peer_total 7076
telemt_me_route_drop_no_conn_total 21847
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 253
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 7078
telemt_me_writer_restored_same_endpoint_total 5133
telemt_me_writer_removed_unexpected_minus_restored_total 1945
telemt_user_connections_total{user="hello"} 53023
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1028936540 (981.27 MB)
telemt_user_octets_to_client{user="hello"} 16843028804 (15.69 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 7171.3 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116783
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 1236
telemt_upstream_connect_attempt_total 9001
telemt_upstream_connect_success_total 8942
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 537
telemt_me_reconnect_attempts_total 1920
telemt_me_reconnect_success_total 1910
telemt_me_reader_eof_total 2573
telemt_me_idle_close_by_peer_total 2572
telemt_me_route_drop_no_conn_total 46433
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 531
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2629
telemt_me_writer_restored_same_endpoint_total 1903
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 107304
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 5175185092 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 29058967644 (27.06 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 7172.0 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130210
telemt_connections_bad_total 46313
telemt_handshake_timeouts_total 8563
telemt_upstream_connect_attempt_total 10549
telemt_upstream_connect_success_total 10516
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 10531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 3270
telemt_me_reconnect_success_total 3261
telemt_me_reader_eof_total 4152
telemt_me_idle_close_by_peer_total 4152
telemt_me_route_drop_no_conn_total 26291
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4154
telemt_me_writer_restored_same_endpoint_total 3257
telemt_me_writer_removed_unexpected_minus_restored_total 897
telemt_user_connections_total{user="hello"} 72898
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 1031370292 (983.59 MB)
telemt_user_octets_to_client{user="hello"} 24662675476 (22.97 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 7170.1 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100169
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 560
telemt_upstream_connect_attempt_total 10013
telemt_upstream_connect_success_total 9961
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 9973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 2844
telemt_me_reconnect_success_total 2832
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3842
telemt_me_route_drop_no_conn_total 36660
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 507
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3879
telemt_me_writer_restored_same_endpoint_total 2830
telemt_me_writer_removed_unexpected_minus_restored_total 1049
telemt_user_connections_total{user="hello"} 94817
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 8567223808 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 34558923104 (32.19 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 52
```