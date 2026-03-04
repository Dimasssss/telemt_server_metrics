# Server Metrics 2026-03-04 00:05:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 10519.6 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76385
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 230
telemt_upstream_connect_attempt_total 8683
telemt_upstream_connect_success_total 8642
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 8642
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 2324
telemt_me_reconnect_success_total 2329
telemt_me_reader_eof_total 2371
telemt_me_idle_close_by_peer_total 2371
telemt_me_route_drop_no_conn_total 30915
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 2371
telemt_me_writer_restored_same_endpoint_total 2309
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 73983
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 619970856 (591.25 MB)
telemt_user_octets_to_client{user="hello"} 22965965376 (21.39 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 10516.4 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36054
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 7811
telemt_upstream_connect_attempt_total 17823
telemt_upstream_connect_success_total 17592
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 17592
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 9105
telemt_me_reconnect_success_total 9109
telemt_me_reader_eof_total 9278
telemt_me_idle_close_by_peer_total 9277
telemt_me_route_drop_no_conn_total 13981
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 9278
telemt_me_writer_restored_same_endpoint_total 9089
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 27710
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 174525632 (166.44 MB)
telemt_user_octets_to_client{user="hello"} 14137290812 (13.17 GB)
telemt_user_unique_ips_current{user="hello"} 14
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 10515.1 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84925
telemt_connections_bad_total 25953
telemt_handshake_timeouts_total 1806
telemt_upstream_connect_attempt_total 11693
telemt_upstream_connect_success_total 11621
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11621
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 4219
telemt_me_reconnect_success_total 4221
telemt_me_reader_eof_total 4403
telemt_me_idle_close_by_peer_total 4402
telemt_me_route_drop_no_conn_total 17247
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4404
telemt_me_writer_restored_same_endpoint_total 4200
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 55952
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 348733912 (332.58 MB)
telemt_user_octets_to_client{user="hello"} 14740369320 (13.73 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 10514.2 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38157
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 7062
telemt_upstream_connect_success_total 7035
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7035
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1040
telemt_me_reconnect_success_total 1053
telemt_me_reader_eof_total 1050
telemt_me_idle_close_by_peer_total 1050
telemt_me_route_drop_no_conn_total 14252
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 36957
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 364259332 (347.38 MB)
telemt_user_octets_to_client{user="hello"} 10696603824 (9.96 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 10512.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91100
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 37248
telemt_upstream_connect_attempt_total 10977
telemt_upstream_connect_success_total 10874
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10874
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 4246
telemt_me_reconnect_success_total 4255
telemt_me_reader_eof_total 4476
telemt_me_idle_close_by_peer_total 4476
telemt_me_route_drop_no_conn_total 34308
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 4479
telemt_me_writer_restored_same_endpoint_total 4231
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 52152
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 247443224 (235.98 MB)
telemt_user_octets_to_client{user="hello"} 14059307932 (13.09 GB)
telemt_user_unique_ips_current{user="hello"} 21
```