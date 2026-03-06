# Server Metrics 2026-03-06 02:25:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 14618.5 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97691
telemt_connections_bad_total 15902
telemt_handshake_timeouts_total 946
telemt_upstream_connect_attempt_total 12608
telemt_upstream_connect_success_total 12492
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 12492
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 3496
telemt_me_reconnect_success_total 3480
telemt_me_reader_eof_total 3605
telemt_me_idle_close_by_peer_total 3605
telemt_me_route_drop_no_conn_total 25010
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3605
telemt_me_writer_restored_same_endpoint_total 3474
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 76817
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 905803844 (863.84 MB)
telemt_user_octets_to_client{user="hello"} 27640528572 (25.74 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 14614.0 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32586
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 419
telemt_upstream_connect_attempt_total 10438
telemt_upstream_connect_success_total 10436
telemt_upstream_connect_attempts_per_request{bucket="1"} 10436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1702
telemt_me_idle_close_by_peer_total 1702
telemt_me_route_drop_no_conn_total 9532
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1703
telemt_me_writer_restored_same_endpoint_total 1679
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 31603
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 199300764 (190.07 MB)
telemt_user_octets_to_client{user="hello"} 6819938900 (6.35 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 14611.5 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59060
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 13513
telemt_upstream_connect_success_total 13394
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13394
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 4024
telemt_me_reconnect_success_total 4011
telemt_me_reader_eof_total 4202
telemt_me_idle_close_by_peer_total 4202
telemt_me_route_drop_no_conn_total 16624
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4203
telemt_me_writer_restored_same_endpoint_total 4004
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 55571
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 593967428 (566.45 MB)
telemt_user_octets_to_client{user="hello"} 20139005752 (18.76 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 14608.3 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46703
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 2896
telemt_upstream_connect_attempt_total 9875
telemt_upstream_connect_success_total 9846
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9846
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 2077
telemt_me_reconnect_success_total 2064
telemt_me_reader_eof_total 2158
telemt_me_idle_close_by_peer_total 2158
telemt_me_route_drop_no_conn_total 18927
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2158
telemt_me_writer_restored_same_endpoint_total 2057
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 41099
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 367165136 (350.16 MB)
telemt_user_octets_to_client{user="hello"} 20444958640 (19.04 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 14606.9 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58554
telemt_connections_bad_total 580
telemt_handshake_timeouts_total 397
telemt_upstream_connect_attempt_total 8764
telemt_upstream_connect_success_total 8745
telemt_upstream_connect_attempts_per_request{bucket="1"} 8745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 1017
telemt_me_reader_eof_total 1038
telemt_me_idle_close_by_peer_total 1038
telemt_me_route_drop_no_conn_total 18105
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1038
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 56730
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 11097038212 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 22713115656 (21.15 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 45
```