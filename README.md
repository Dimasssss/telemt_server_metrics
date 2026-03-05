# Server Metrics 2026-03-05 22:50:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 1718.9 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14572
telemt_connections_bad_total 4606
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 607
telemt_upstream_connect_success_total 595
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 595
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 2188
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 47
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 21
telemt_user_connections_total{user="hello"} 9531
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 316461448 (301.80 MB)
telemt_user_octets_to_client{user="hello"} 4164810188 (3.88 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 1714.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4460
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 651
telemt_upstream_connect_success_total 649
telemt_upstream_connect_attempts_per_request{bucket="1"} 649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 730
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 7
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 8
telemt_user_connections_total{user="hello"} 4258
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 62982416 (60.06 MB)
telemt_user_octets_to_client{user="hello"} 588945700 (561.66 MB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 1711.8 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7177
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 601
telemt_upstream_connect_success_total 584
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 584
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 1873
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 7085
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 262149712 (250.01 MB)
telemt_user_octets_to_client{user="hello"} 2269588008 (2.11 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 1708.5 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6548
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 682
telemt_upstream_connect_success_total 675
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 675
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 2020
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 40
telemt_user_connections_total{user="hello"} 6056
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 102035264 (97.31 MB)
telemt_user_octets_to_client{user="hello"} 6210672780 (5.78 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 1707.2 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7657
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 706
telemt_upstream_connect_success_total 704
telemt_upstream_connect_attempts_per_request{bucket="1"} 704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 23
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 3686
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 22
telemt_user_connections_total{user="hello"} 7513
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 162096584 (154.59 MB)
telemt_user_octets_to_client{user="hello"} 11432773520 (10.65 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 30
```