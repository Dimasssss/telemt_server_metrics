# Server Metrics 2026-03-06 00:58:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 9397.0 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65770
telemt_connections_bad_total 15625
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 6911
telemt_upstream_connect_success_total 6853
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6853
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1431
telemt_me_reconnect_success_total 1422
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1470
telemt_me_route_drop_no_conn_total 13561
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 112
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 1470
telemt_me_writer_restored_same_endpoint_total 1417
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 48262
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 576386072 (549.68 MB)
telemt_user_octets_to_client{user="hello"} 16541168536 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 9392.5 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20963
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 302
telemt_upstream_connect_attempt_total 7892
telemt_upstream_connect_success_total 7889
telemt_upstream_connect_attempts_per_request{bucket="1"} 7889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1592
telemt_me_reader_eof_total 1608
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 6240
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
telemt_pool_force_close_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1609
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 20237
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 141411676 (134.86 MB)
telemt_user_octets_to_client{user="hello"} 5327077608 (4.96 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 9390.0 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37118
telemt_connections_bad_total 300
telemt_handshake_timeouts_total 194
telemt_upstream_connect_attempt_total 9687
telemt_upstream_connect_success_total 9594
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9594
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3229
telemt_me_reconnect_success_total 3220
telemt_me_reader_eof_total 3384
telemt_me_idle_close_by_peer_total 3384
telemt_me_route_drop_no_conn_total 9498
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3385
telemt_me_writer_restored_same_endpoint_total 3214
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 35537
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 472522964 (450.63 MB)
telemt_user_octets_to_client{user="hello"} 16298342868 (15.18 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 9386.4 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28485
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 5338
telemt_upstream_connect_success_total 5317
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5317
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 718
telemt_me_reconnect_success_total 712
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 735
telemt_me_route_drop_no_conn_total 12339
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 63
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 735
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 26055
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 267232724 (254.85 MB)
telemt_user_octets_to_client{user="hello"} 17092844552 (15.92 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 9385.4 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37828
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 5347
telemt_upstream_connect_success_total 5337
telemt_upstream_connect_attempts_per_request{bucket="1"} 5337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 691
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 701
telemt_me_idle_close_by_peer_total 701
telemt_me_route_drop_no_conn_total 12795
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
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 37140
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 11004143976 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 18472253888 (17.20 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 30
```