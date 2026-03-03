# Server Metrics 2026-03-03 22:08:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 3457.2 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34148
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 1670
telemt_upstream_connect_success_total 1661
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1661
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 167
telemt_me_reconnect_success_total 180
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 13182
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 59
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 32972
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 345156856 (329.17 MB)
telemt_user_octets_to_client{user="hello"} 14045917756 (13.08 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 3453.8 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13990
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2491
telemt_upstream_connect_attempt_total 2249
telemt_upstream_connect_success_total 2146
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2146
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 470
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 5245
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_me_writer_removed_unexpected_total 475
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 11266
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 61545244 (58.69 MB)
telemt_user_octets_to_client{user="hello"} 2847324776 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 3452.6 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34871
telemt_connections_bad_total 9464
telemt_handshake_timeouts_total 218
telemt_upstream_connect_attempt_total 2045
telemt_upstream_connect_success_total 2028
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2028
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 249
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 7146
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 91
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 24252
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 179132196 (170.83 MB)
telemt_user_octets_to_client{user="hello"} 9989079412 (9.30 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 3451.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15368
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 1994
telemt_upstream_connect_success_total 1981
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1981
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 6544
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 213
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 14862
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 143812808 (137.15 MB)
telemt_user_octets_to_client{user="hello"} 6215559020 (5.79 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 3450.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32722
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 7804
telemt_upstream_connect_attempt_total 1819
telemt_upstream_connect_success_total 1787
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1787
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 341
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 24492
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_restored_same_endpoint_total 335
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 24387
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 149512364 (142.59 MB)
telemt_user_octets_to_client{user="hello"} 6287941644 (5.86 GB)
telemt_user_unique_ips_current{user="hello"} 25
```