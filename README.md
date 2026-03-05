# Server Metrics 2026-03-05 22:55:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 2026.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16434
telemt_connections_bad_total 4607
telemt_handshake_timeouts_total 134
telemt_upstream_connect_attempt_total 805
telemt_upstream_connect_success_total 785
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 785
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 2547
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 48
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 37
telemt_me_writer_restored_same_endpoint_total 37
telemt_user_connections_total{user="hello"} 11313
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 329099224 (313.85 MB)
telemt_user_octets_to_client{user="hello"} 5003051988 (4.66 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 2021.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5425
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 788
telemt_upstream_connect_success_total 786
telemt_upstream_connect_attempts_per_request{bucket="1"} 786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 14
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 930
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 7
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 5151
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 64741532 (61.74 MB)
telemt_user_octets_to_client{user="hello"} 614368420 (585.91 MB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 2019.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8424
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 781
telemt_upstream_connect_success_total 752
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 752
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 2273
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 8325
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 272731304 (260.10 MB)
telemt_user_octets_to_client{user="hello"} 2701578896 (2.52 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 2015.6 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7696
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 892
telemt_upstream_connect_success_total 885
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 885
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 70
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 3725
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 65
telemt_me_writer_restored_same_endpoint_total 65
telemt_user_connections_total{user="hello"} 7079
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 109216408 (104.16 MB)
telemt_user_octets_to_client{user="hello"} 7692566540 (7.16 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 2014.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8952
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 924
telemt_upstream_connect_success_total 923
telemt_upstream_connect_attempts_per_request{bucket="1"} 923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 4191
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_restored_same_endpoint_total 43
telemt_user_connections_total{user="hello"} 8794
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 749134504 (714.43 MB)
telemt_user_octets_to_client{user="hello"} 12616200420 (11.75 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```