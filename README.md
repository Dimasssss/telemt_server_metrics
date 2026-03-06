# Server Metrics 2026-03-06 00:47:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 8783.0 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62033
telemt_connections_bad_total 15040
telemt_handshake_timeouts_total 519
telemt_upstream_connect_attempt_total 6151
telemt_upstream_connect_success_total 6099
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6099
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 1186
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 12147
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 1212
telemt_me_writer_restored_same_endpoint_total 1174
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 45187
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 561226548 (535.23 MB)
telemt_user_octets_to_client{user="hello"} 15422254180 (14.36 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 8778.4 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19413
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 7445
telemt_upstream_connect_success_total 7443
telemt_upstream_connect_attempts_per_request{bucket="1"} 7443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 1557
telemt_me_reconnect_success_total 1552
telemt_me_reader_eof_total 1568
telemt_me_idle_close_by_peer_total 1568
telemt_me_route_drop_no_conn_total 6015
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1569
telemt_me_writer_restored_same_endpoint_total 1548
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 18721
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 137514868 (131.14 MB)
telemt_user_octets_to_client{user="hello"} 5241673964 (4.88 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 8775.8 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34824
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 9197
telemt_upstream_connect_success_total 9129
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 9129
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3182
telemt_me_reconnect_success_total 3174
telemt_me_reader_eof_total 3336
telemt_me_idle_close_by_peer_total 3336
telemt_me_route_drop_no_conn_total 9038
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3337
telemt_me_writer_restored_same_endpoint_total 3168
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 33279
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 447616340 (426.88 MB)
telemt_user_octets_to_client{user="hello"} 14931091348 (13.91 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 8772.5 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26873
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 851
telemt_upstream_connect_attempt_total 4688
telemt_upstream_connect_success_total 4669
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4669
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1974
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 541
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 11604
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 24552
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 260526808 (248.46 MB)
telemt_user_octets_to_client{user="hello"} 16800942660 (15.65 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 8771.3 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35743
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 150
telemt_upstream_connect_attempt_total 5111
telemt_upstream_connect_success_total 5102
telemt_upstream_connect_attempts_per_request{bucket="1"} 5102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 12363
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 3
telemt_pool_force_close_total 50
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 35092
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 11000115508 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 18362080060 (17.10 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```