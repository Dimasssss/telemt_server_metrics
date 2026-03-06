# Server Metrics 2026-03-06 03:52:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 19839.9 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137658
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2822
telemt_upstream_connect_attempt_total 22518
telemt_upstream_connect_success_total 22341
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 22341
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 241
telemt_me_reconnect_attempts_total 8556
telemt_me_reconnect_success_total 8528
telemt_me_reader_eof_total 8830
telemt_me_idle_close_by_peer_total 8830
telemt_me_route_drop_no_conn_total 37846
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 8830
telemt_me_writer_restored_same_endpoint_total 8522
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 111377
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 1452086340 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 42747941044 (39.81 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 19835.4 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46996
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 16295
telemt_upstream_connect_success_total 16293
telemt_upstream_connect_attempts_per_request{bucket="1"} 16293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 3152
telemt_me_reconnect_success_total 3138
telemt_me_reader_eof_total 3179
telemt_me_idle_close_by_peer_total 3179
telemt_me_route_drop_no_conn_total 13966
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 155
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 3180
telemt_me_writer_restored_same_endpoint_total 3132
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 45378
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 325051608 (309.99 MB)
telemt_user_octets_to_client{user="hello"} 11331913252 (10.55 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 19832.9 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81770
telemt_connections_bad_total 788
telemt_handshake_timeouts_total 1622
telemt_upstream_connect_attempt_total 19033
telemt_upstream_connect_success_total 18885
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 18885
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 5845
telemt_me_reconnect_success_total 5824
telemt_me_reader_eof_total 6093
telemt_me_idle_close_by_peer_total 6093
telemt_me_route_drop_no_conn_total 22851
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6097
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 76546
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 762230536 (726.92 MB)
telemt_user_octets_to_client{user="hello"} 25671629136 (23.91 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 19829.5 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68497
telemt_connections_bad_total 1234
telemt_handshake_timeouts_total 4166
telemt_upstream_connect_attempt_total 13205
telemt_upstream_connect_success_total 13164
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 13164
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 2634
telemt_me_reconnect_success_total 2615
telemt_me_reader_eof_total 2717
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 24477
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 181
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2717
telemt_me_writer_restored_same_endpoint_total 2608
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 59512
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 646336220 (616.39 MB)
telemt_user_octets_to_client{user="hello"} 25860687704 (24.08 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 19828.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80681
telemt_connections_bad_total 874
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 13483
telemt_upstream_connect_success_total 13456
telemt_upstream_connect_attempts_per_request{bucket="1"} 13456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 2059
telemt_me_reconnect_success_total 2052
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2109
telemt_me_route_drop_no_conn_total 26346
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 2111
telemt_me_writer_restored_same_endpoint_total 2046
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 78041
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 14281205064 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 46964780716 (43.74 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 36
```