# Server Metrics 2026-03-06 01:44:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 12161.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81097
telemt_connections_bad_total 15877
telemt_handshake_timeouts_total 736
telemt_upstream_connect_attempt_total 10220
telemt_upstream_connect_success_total 10112
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10112
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 2772
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2867
telemt_me_idle_close_by_peer_total 2867
telemt_me_route_drop_no_conn_total 19246
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 152
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 2
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 2867
telemt_me_writer_restored_same_endpoint_total 2751
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 62868
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 732051904 (698.14 MB)
telemt_user_octets_to_client{user="hello"} 23179602688 (21.59 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 12157.2 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26992
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 9456
telemt_upstream_connect_success_total 9454
telemt_upstream_connect_attempts_per_request{bucket="1"} 9454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 7352
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1684
telemt_me_writer_restored_same_endpoint_total 1662
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 26153
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 174351596 (166.27 MB)
telemt_user_octets_to_client{user="hello"} 6020081672 (5.61 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 12154.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48342
telemt_connections_bad_total 323
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 12019
telemt_upstream_connect_success_total 11907
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11907
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 3827
telemt_me_reconnect_success_total 3816
telemt_me_reader_eof_total 4003
telemt_me_idle_close_by_peer_total 4003
telemt_me_route_drop_no_conn_total 12457
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4004
telemt_me_writer_restored_same_endpoint_total 3809
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 45795
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 535860264 (511.04 MB)
telemt_user_octets_to_client{user="hello"} 18263558920 (17.01 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 12151.3 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38405
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 2645
telemt_upstream_connect_attempt_total 8893
telemt_upstream_connect_success_total 8868
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 8868
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3740
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 2022
telemt_me_reconnect_success_total 2012
telemt_me_reader_eof_total 2106
telemt_me_idle_close_by_peer_total 2106
telemt_me_route_drop_no_conn_total 16088
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 117
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 4
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 2106
telemt_me_writer_restored_same_endpoint_total 2007
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 33523
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 319427212 (304.63 MB)
telemt_user_octets_to_client{user="hello"} 19246589932 (17.92 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 12150.1 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48544
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 7045
telemt_upstream_connect_success_total 7029
telemt_upstream_connect_attempts_per_request{bucket="1"} 7029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 15523
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 47566
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 11057552300 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 21003028248 (19.56 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 30
```