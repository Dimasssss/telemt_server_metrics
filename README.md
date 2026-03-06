# Server Metrics 2026-03-06 00:42:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 8475.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59922
telemt_connections_bad_total 14746
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 5809
telemt_upstream_connect_success_total 5757
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5757
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1081
telemt_me_reconnect_success_total 1075
telemt_me_reader_eof_total 1101
telemt_me_idle_close_by_peer_total 1101
telemt_me_route_drop_no_conn_total 11660
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
telemt_me_writer_removed_unexpected_total 1101
telemt_me_writer_restored_same_endpoint_total 1070
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 43404
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 552854928 (527.24 MB)
telemt_user_octets_to_client{user="hello"} 15052473388 (14.02 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 8471.3 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18808
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 279
telemt_upstream_connect_attempt_total 7172
telemt_upstream_connect_success_total 7170
telemt_upstream_connect_attempts_per_request{bucket="1"} 7170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 1507
telemt_me_reader_eof_total 1522
telemt_me_idle_close_by_peer_total 1522
telemt_me_route_drop_no_conn_total 5749
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
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 18123
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 135184776 (128.92 MB)
telemt_user_octets_to_client{user="hello"} 4892210636 (4.56 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 8468.6 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33849
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 9022
telemt_upstream_connect_success_total 8954
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8954
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 3173
telemt_me_reconnect_success_total 3166
telemt_me_reader_eof_total 3327
telemt_me_idle_close_by_peer_total 3327
telemt_me_route_drop_no_conn_total 8856
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 82
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3328
telemt_me_writer_restored_same_endpoint_total 3160
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 32313
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 439235932 (418.89 MB)
telemt_user_octets_to_client{user="hello"} 13043665572 (12.15 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 8465.3 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25939
telemt_connections_bad_total 185
telemt_handshake_timeouts_total 778
telemt_upstream_connect_attempt_total 4394
telemt_upstream_connect_success_total 4375
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4375
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1859
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 453
telemt_me_reconnect_success_total 448
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 11494
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
telemt_me_writer_removed_unexpected_total 456
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 23727
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 257649852 (245.71 MB)
telemt_user_octets_to_client{user="hello"} 16697731032 (15.55 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 8464.2 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34798
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 4991
telemt_upstream_connect_success_total 4982
telemt_upstream_connect_attempts_per_request{bucket="1"} 4982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 682
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 12183
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
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 34166
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 10997721268 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 18205448620 (16.96 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```