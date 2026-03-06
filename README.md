# Server Metrics 2026-03-06 03:01:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 16768.6 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113079
telemt_connections_bad_total 15907
telemt_handshake_timeouts_total 1601
telemt_upstream_connect_attempt_total 15889
telemt_upstream_connect_success_total 15735
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15735
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 4834
telemt_me_reconnect_success_total 4815
telemt_me_reader_eof_total 4975
telemt_me_idle_close_by_peer_total 4975
telemt_me_route_drop_no_conn_total 30425
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 4975
telemt_me_writer_restored_same_endpoint_total 4809
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 90042
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 1061787000 (1012.60 MB)
telemt_user_octets_to_client{user="hello"} 35955669704 (33.49 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 16764.1 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37323
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 467
telemt_upstream_connect_attempt_total 12206
telemt_upstream_connect_success_total 12204
telemt_upstream_connect_attempts_per_request{bucket="1"} 12204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 1919
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1930
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 11086
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1931
telemt_me_writer_restored_same_endpoint_total 1903
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 36195
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 243930548 (232.63 MB)
telemt_user_octets_to_client{user="hello"} 8966999316 (8.35 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 16761.5 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68202
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 1325
telemt_upstream_connect_attempt_total 15262
telemt_upstream_connect_success_total 15136
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 15136
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 4365
telemt_me_reconnect_success_total 4349
telemt_me_reader_eof_total 4554
telemt_me_idle_close_by_peer_total 4554
telemt_me_route_drop_no_conn_total 18774
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 164
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4555
telemt_me_writer_restored_same_endpoint_total 4342
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 63658
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 648823732 (618.77 MB)
telemt_user_octets_to_client{user="hello"} 22190184952 (20.67 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 16758.2 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53714
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 3060
telemt_upstream_connect_attempt_total 11050
telemt_upstream_connect_success_total 11015
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 11015
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 2230
telemt_me_reconnect_success_total 2216
telemt_me_reader_eof_total 2311
telemt_me_idle_close_by_peer_total 2311
telemt_me_route_drop_no_conn_total 20883
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2311
telemt_me_writer_restored_same_endpoint_total 2209
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 47490
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 418967204 (399.56 MB)
telemt_user_octets_to_client{user="hello"} 22662190980 (21.11 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 16757.1 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66706
telemt_connections_bad_total 595
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 9973
telemt_upstream_connect_success_total 9950
telemt_upstream_connect_attempts_per_request{bucket="1"} 9950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 1084
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_route_drop_no_conn_total 20571
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_restored_same_endpoint_total 1078
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 64688
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 12039325388 (11.21 GB)
telemt_user_octets_to_client{user="hello"} 28143614508 (26.21 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 33
```