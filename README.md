# Server Metrics 2026-03-04 01:27:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 15434.7 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103017
telemt_connections_bad_total 1366
telemt_handshake_timeouts_total 539
telemt_upstream_connect_attempt_total 12190
telemt_upstream_connect_success_total 12135
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 12135
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 3097
telemt_me_reconnect_success_total 3099
telemt_me_reader_eof_total 3164
telemt_me_idle_close_by_peer_total 3164
telemt_me_route_drop_no_conn_total 38382
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3164
telemt_me_writer_restored_same_endpoint_total 3079
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 98752
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 740216072 (705.93 MB)
telemt_user_octets_to_client{user="hello"} 30348239284 (28.26 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 15431.2 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48033
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 11958
telemt_upstream_connect_attempt_total 32124
telemt_upstream_connect_success_total 31752
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 31746
telemt_upstream_connect_attempts_per_request{bucket="2"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 671
telemt_me_reconnect_attempts_total 18526
telemt_me_reconnect_success_total 18516
telemt_me_reader_eof_total 18971
telemt_me_idle_close_by_peer_total 18970
telemt_me_route_drop_no_conn_total 16975
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 19032
telemt_me_writer_restored_same_endpoint_total 18496
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 35405
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 253510620 (241.77 MB)
telemt_user_octets_to_client{user="hello"} 20854763868 (19.42 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 15430.1 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112141
telemt_connections_bad_total 38760
telemt_handshake_timeouts_total 1979
telemt_upstream_connect_attempt_total 17126
telemt_upstream_connect_success_total 17021
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 17021
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 5825
telemt_me_reconnect_success_total 5818
telemt_me_reader_eof_total 6059
telemt_me_idle_close_by_peer_total 6057
telemt_me_route_drop_no_conn_total 21622
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6060
telemt_me_writer_restored_same_endpoint_total 5797
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 70015
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 429596280 (409.69 MB)
telemt_user_octets_to_client{user="hello"} 17734214376 (16.52 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 15429.0 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50332
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 10019
telemt_upstream_connect_success_total 9980
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9980
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 1441
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1454
telemt_me_idle_close_by_peer_total 1454
telemt_me_route_drop_no_conn_total 17496
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_restored_same_endpoint_total 1430
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 48788
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 415466764 (396.22 MB)
telemt_user_octets_to_client{user="hello"} 12762245432 (11.89 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 15427.6 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121528
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 53171
telemt_upstream_connect_attempt_total 24620
telemt_upstream_connect_success_total 24485
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 24485
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 13204
telemt_me_reconnect_success_total 13205
telemt_me_reader_eof_total 14057
telemt_me_idle_close_by_peer_total 14056
telemt_me_route_drop_no_conn_total 38016
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 2
telemt_pool_force_close_total 30
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14062
telemt_me_writer_restored_same_endpoint_total 13181
telemt_me_writer_removed_unexpected_minus_restored_total 881
telemt_user_connections_total{user="hello"} 66057
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 315902620 (301.27 MB)
telemt_user_octets_to_client{user="hello"} 15733338700 (14.65 GB)
telemt_user_unique_ips_current{user="hello"} 12
```