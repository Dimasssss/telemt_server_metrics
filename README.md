# Server Metrics 2026-03-06 15:55:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 20034.4 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603455
telemt_connections_bad_total 6722
telemt_handshake_timeouts_total 2959
telemt_upstream_connect_attempt_total 9895
telemt_upstream_connect_success_total 9834
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 9860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 1972
telemt_me_reconnect_success_total 1958
telemt_me_reader_eof_total 2056
telemt_me_idle_close_by_peer_total 2056
telemt_me_route_drop_no_conn_total 243739
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3152
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 2387
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2058
telemt_me_writer_restored_same_endpoint_total 1952
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 516280
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 12289678056 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 195613382760 (182.18 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 20034.2 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225479
telemt_connections_bad_total 865
telemt_handshake_timeouts_total 6751
telemt_upstream_connect_attempt_total 9364
telemt_upstream_connect_success_total 9342
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 924
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 114674
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 781
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 958
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 208336
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 2374183456 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 85422234648 (79.56 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 20034.1 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451405
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 41843
telemt_upstream_connect_attempt_total 16350
telemt_upstream_connect_success_total 16273
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 5398
telemt_me_reconnect_success_total 5376
telemt_me_reader_eof_total 5692
telemt_me_idle_close_by_peer_total 5692
telemt_me_route_drop_no_conn_total 221556
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 916
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5696
telemt_me_writer_restored_same_endpoint_total 5371
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 389778
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 5797286716 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 123921159064 (115.41 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 19350.1 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377941
telemt_connections_bad_total 105772
telemt_handshake_timeouts_total 10419
telemt_upstream_connect_attempt_total 10298
telemt_upstream_connect_success_total 10297
telemt_upstream_connect_attempts_per_request{bucket="1"} 10297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4151
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 1967
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1990
telemt_me_idle_close_by_peer_total 1990
telemt_me_route_drop_no_conn_total 117824
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 316
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1990
telemt_me_writer_restored_same_endpoint_total 1951
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 226719
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 2625045500 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 81240259424 (75.66 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 20034.4 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352296
telemt_connections_bad_total 11041
telemt_handshake_timeouts_total 2823
telemt_upstream_connect_attempt_total 9519
telemt_upstream_connect_success_total 9507
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 1764
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1844
telemt_me_idle_close_by_peer_total 1843
telemt_me_route_drop_no_conn_total 179603
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 638
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 6
telemt_pool_force_close_total 240
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 323340
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 15044417492 (14.01 GB)
telemt_user_octets_to_client{user="hello"} 172449414532 (160.61 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 95
```