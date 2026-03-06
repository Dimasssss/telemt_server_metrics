# Server Metrics 2026-03-06 03:31:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 18611.4 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128148
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2738
telemt_upstream_connect_attempt_total 19724
telemt_upstream_connect_success_total 19555
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 19555
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 6958
telemt_me_reconnect_success_total 6933
telemt_me_reader_eof_total 7165
telemt_me_idle_close_by_peer_total 7165
telemt_me_route_drop_no_conn_total 34814
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 334
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 7165
telemt_me_writer_restored_same_endpoint_total 6927
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 102364
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 1340974564 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 39688726724 (36.96 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 18606.8 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42653
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 14518
telemt_upstream_connect_success_total 14516
telemt_upstream_connect_attempts_per_request{bucket="1"} 14516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 2525
telemt_me_reconnect_success_total 2514
telemt_me_reader_eof_total 2545
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 12577
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 131
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2546
telemt_me_writer_restored_same_endpoint_total 2508
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 41233
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 294483596 (280.84 MB)
telemt_user_octets_to_client{user="hello"} 10261485860 (9.56 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 18604.1 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76272
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 1585
telemt_upstream_connect_attempt_total 18083
telemt_upstream_connect_success_total 17935
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 17935
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 5515
telemt_me_reconnect_success_total 5495
telemt_me_reader_eof_total 5746
telemt_me_idle_close_by_peer_total 5746
telemt_me_route_drop_no_conn_total 21087
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 5750
telemt_me_writer_restored_same_endpoint_total 5488
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 71206
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 692594356 (660.51 MB)
telemt_user_octets_to_client{user="hello"} 24383827704 (22.71 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 18600.8 (5h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61712
telemt_connections_bad_total 278
telemt_handshake_timeouts_total 4055
telemt_upstream_connect_attempt_total 12623
telemt_upstream_connect_success_total 12586
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 12586
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2599
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 2684
telemt_me_idle_close_by_peer_total 2684
telemt_me_route_drop_no_conn_total 22937
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2684
telemt_me_writer_restored_same_endpoint_total 2575
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 54046
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 526218016 (501.84 MB)
telemt_user_octets_to_client{user="hello"} 24590681036 (22.90 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 18599.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74676
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 514
telemt_upstream_connect_attempt_total 11780
telemt_upstream_connect_success_total 11756
telemt_upstream_connect_attempts_per_request{bucket="1"} 11756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 1457
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1488
telemt_me_idle_close_by_peer_total 1488
telemt_me_route_drop_no_conn_total 23782
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1488
telemt_me_writer_restored_same_endpoint_total 1446
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 72200
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 12137668152 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 41774839596 (38.91 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 41
```