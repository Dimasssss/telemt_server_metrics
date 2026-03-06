# Server Metrics 2026-03-06 02:14:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 14004.4 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92924
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 883
telemt_upstream_connect_attempt_total 11873
telemt_upstream_connect_success_total 11762
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 11762
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 3266
telemt_me_reconnect_success_total 3250
telemt_me_reader_eof_total 3369
telemt_me_idle_close_by_peer_total 3369
telemt_me_route_drop_no_conn_total 23621
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 196
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3369
telemt_me_writer_restored_same_endpoint_total 3244
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 73095
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 855069260 (815.46 MB)
telemt_user_octets_to_client{user="hello"} 25366303392 (23.62 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 14000.0 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31242
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 412
telemt_upstream_connect_attempt_total 10214
telemt_upstream_connect_success_total 10212
telemt_upstream_connect_attempts_per_request{bucket="1"} 10212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 1691
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 9085
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 6
telemt_pool_force_close_total 68
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1701
telemt_me_writer_restored_same_endpoint_total 1677
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 30278
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 193638024 (184.67 MB)
telemt_user_octets_to_client{user="hello"} 6624215044 (6.17 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 13997.3 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56721
telemt_connections_bad_total 519
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 13262
telemt_upstream_connect_success_total 13143
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13143
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 4013
telemt_me_reconnect_success_total 4001
telemt_me_reader_eof_total 4192
telemt_me_idle_close_by_peer_total 4192
telemt_me_route_drop_no_conn_total 14839
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4193
telemt_me_writer_restored_same_endpoint_total 3994
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 53266
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 586714512 (559.53 MB)
telemt_user_octets_to_client{user="hello"} 19850188268 (18.49 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 13994.1 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44850
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 2855
telemt_upstream_connect_attempt_total 9688
telemt_upstream_connect_success_total 9659
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9659
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 2072
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2155
telemt_me_route_drop_no_conn_total 18607
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 5
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 2155
telemt_me_writer_restored_same_endpoint_total 2054
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 39431
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 352543376 (336.21 MB)
telemt_user_octets_to_client{user="hello"} 20279104208 (18.89 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 13992.9 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56316
telemt_connections_bad_total 358
telemt_handshake_timeouts_total 393
telemt_upstream_connect_attempt_total 8210
telemt_upstream_connect_success_total 8191
telemt_upstream_connect_attempts_per_request{bucket="1"} 8191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 920
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 17445
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 54762
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 11089836452 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 21804380052 (20.31 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```