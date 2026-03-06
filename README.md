# Server Metrics 2026-03-06 05:24:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 25369.5 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198489
telemt_connections_bad_total 16011
telemt_handshake_timeouts_total 3233
telemt_upstream_connect_attempt_total 26989
telemt_upstream_connect_success_total 26776
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 26776
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 9873
telemt_me_reconnect_success_total 9837
telemt_me_reader_eof_total 10176
telemt_me_idle_close_by_peer_total 10176
telemt_me_route_drop_no_conn_total 61806
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 616
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 422
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 4
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 10177
telemt_me_writer_restored_same_endpoint_total 9831
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 170531
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 3743117104 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 65877698588 (61.35 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 25364.9 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76066
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 2115
telemt_upstream_connect_attempt_total 24023
telemt_upstream_connect_success_total 24021
telemt_upstream_connect_attempts_per_request{bucket="1"} 24021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 6758
telemt_me_reconnect_success_total 6736
telemt_me_reader_eof_total 6886
telemt_me_idle_close_by_peer_total 6886
telemt_me_route_drop_no_conn_total 22537
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 291
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 8
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6887
telemt_me_writer_restored_same_endpoint_total 6730
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 72353
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 677469628 (646.09 MB)
telemt_user_octets_to_client{user="hello"} 20658378724 (19.24 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 25362.3 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130309
telemt_connections_bad_total 1444
telemt_handshake_timeouts_total 3201
telemt_upstream_connect_attempt_total 25314
telemt_upstream_connect_success_total 25123
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 25123
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 8146
telemt_me_reconnect_success_total 8117
telemt_me_reader_eof_total 8472
telemt_me_idle_close_by_peer_total 8472
telemt_me_route_drop_no_conn_total 37826
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 242
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 8477
telemt_me_writer_restored_same_endpoint_total 8109
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 121996
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1131086032 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 41447089020 (38.60 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 25359.0 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105374
telemt_connections_bad_total 6350
telemt_handshake_timeouts_total 5614
telemt_upstream_connect_attempt_total 18078
telemt_upstream_connect_success_total 18013
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 18013
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 3705
telemt_me_reconnect_success_total 3677
telemt_me_reader_eof_total 3799
telemt_me_idle_close_by_peer_total 3799
telemt_me_route_drop_no_conn_total 36536
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 268
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 3799
telemt_me_writer_restored_same_endpoint_total 3670
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 88790
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 1513350332 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 33820242772 (31.50 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 25358.1 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120805
telemt_connections_bad_total 1028
telemt_handshake_timeouts_total 678
telemt_upstream_connect_attempt_total 16970
telemt_upstream_connect_success_total 16931
telemt_upstream_connect_attempts_per_request{bucket="1"} 16931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 2875
telemt_me_reconnect_success_total 2861
telemt_me_reader_eof_total 2961
telemt_me_idle_close_by_peer_total 2960
telemt_me_route_drop_no_conn_total 42171
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 165
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2965
telemt_me_writer_restored_same_endpoint_total 2854
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 116988
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 23711434412 (22.08 GB)
telemt_user_octets_to_client{user="hello"} 71268888812 (66.37 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 63
```