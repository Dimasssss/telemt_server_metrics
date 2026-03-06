# Server Metrics 2026-03-06 00:53:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 9090.0 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63915
telemt_connections_bad_total 15337
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 6497
telemt_upstream_connect_success_total 6443
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6443
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 1295
telemt_me_reconnect_success_total 1288
telemt_me_reader_eof_total 1326
telemt_me_idle_close_by_peer_total 1326
telemt_me_route_drop_no_conn_total 12573
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 112
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 1326
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 46734
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 570079228 (543.67 MB)
telemt_user_octets_to_client{user="hello"} 16057886000 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 9085.5 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20130
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 7758
telemt_upstream_connect_success_total 7756
telemt_upstream_connect_attempts_per_request{bucket="1"} 7756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1593
telemt_me_reconnect_success_total 1588
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1604
telemt_me_route_drop_no_conn_total 6124
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 3
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1605
telemt_me_writer_restored_same_endpoint_total 1584
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 19420
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 139563948 (133.10 MB)
telemt_user_octets_to_client{user="hello"} 5293047036 (4.93 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 9082.9 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36136
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 9368
telemt_upstream_connect_success_total 9299
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 9299
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3188
telemt_me_reconnect_success_total 3180
telemt_me_reader_eof_total 3343
telemt_me_idle_close_by_peer_total 3343
telemt_me_route_drop_no_conn_total 9262
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3344
telemt_me_writer_restored_same_endpoint_total 3174
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 34582
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 463563480 (442.09 MB)
telemt_user_octets_to_client{user="hello"} 15817772032 (14.73 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 9079.4 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27661
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 889
telemt_upstream_connect_attempt_total 4976
telemt_upstream_connect_success_total 4955
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 611
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 620
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 12212
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 620
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 25290
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 264056636 (251.82 MB)
telemt_user_octets_to_client{user="hello"} 17023741580 (15.85 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 9078.4 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36775
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 5230
telemt_upstream_connect_success_total 5221
telemt_upstream_connect_attempts_per_request{bucket="1"} 5221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 12677
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 50
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 36102
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 11002306080 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 18457987096 (17.19 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```