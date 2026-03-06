# Server Metrics 2026-03-06 01:54:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 12776.1 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84500
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 772
telemt_upstream_connect_attempt_total 10610
telemt_upstream_connect_success_total 10499
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 10499
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4273
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 2845
telemt_me_reconnect_success_total 2830
telemt_me_reader_eof_total 2940
telemt_me_idle_close_by_peer_total 2940
telemt_me_route_drop_no_conn_total 19988
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 162
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 2940
telemt_me_writer_restored_same_endpoint_total 2824
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 66160
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 760479240 (725.25 MB)
telemt_user_octets_to_client{user="hello"} 23531993744 (21.92 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 12771.7 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28454
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 368
telemt_upstream_connect_attempt_total 9848
telemt_upstream_connect_success_total 9846
telemt_upstream_connect_attempts_per_request{bucket="1"} 9846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1685
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 1694
telemt_me_idle_close_by_peer_total 1694
telemt_me_route_drop_no_conn_total 7689
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 5
telemt_pool_force_close_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1695
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 27586
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 179377036 (171.07 MB)
telemt_user_octets_to_client{user="hello"} 6192342416 (5.77 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 12769.0 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51396
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 12368
telemt_upstream_connect_success_total 12252
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 12252
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 3857
telemt_me_reconnect_success_total 3846
telemt_me_reader_eof_total 4033
telemt_me_idle_close_by_peer_total 4033
telemt_me_route_drop_no_conn_total 13258
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 101
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4034
telemt_me_writer_restored_same_endpoint_total 3839
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 48441
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 554242632 (528.57 MB)
telemt_user_octets_to_client{user="hello"} 18567245040 (17.29 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 12765.7 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40432
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 2701
telemt_upstream_connect_attempt_total 9091
telemt_upstream_connect_success_total 9062
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9062
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3827
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 2026
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2109
telemt_me_route_drop_no_conn_total 16679
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 123
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 4
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 2109
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 35396
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 334208732 (318.73 MB)
telemt_user_octets_to_client{user="hello"} 19678282064 (18.33 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 12764.5 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51000
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 7303
telemt_upstream_connect_success_total 7286
telemt_upstream_connect_attempts_per_request{bucket="1"} 7286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 16122
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 41
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 49986
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 11066788632 (10.31 GB)
telemt_user_octets_to_client{user="hello"} 21394333864 (19.93 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```