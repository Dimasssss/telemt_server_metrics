# Server Metrics 2026-03-06 02:09:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 13697.3 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90350
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 11538
telemt_upstream_connect_success_total 11426
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 11426
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 3154
telemt_me_reconnect_success_total 3138
telemt_me_reader_eof_total 3255
telemt_me_idle_close_by_peer_total 3255
telemt_me_route_drop_no_conn_total 22828
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 184
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3255
telemt_me_writer_restored_same_endpoint_total 3132
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 71285
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 814149200 (776.43 MB)
telemt_user_octets_to_client{user="hello"} 24430823052 (22.75 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 13692.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30625
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 10131
telemt_upstream_connect_success_total 10129
telemt_upstream_connect_attempts_per_request{bucket="1"} 10129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 1691
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 8933
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
telemt_user_connections_total{user="hello"} 29673
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 188741184 (180.00 MB)
telemt_user_octets_to_client{user="hello"} 6511197272 (6.06 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 13690.1 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55438
telemt_connections_bad_total 519
telemt_handshake_timeouts_total 545
telemt_upstream_connect_attempt_total 13169
telemt_upstream_connect_success_total 13050
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13050
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 4012
telemt_me_reconnect_success_total 4000
telemt_me_reader_eof_total 4191
telemt_me_idle_close_by_peer_total 4191
telemt_me_route_drop_no_conn_total 14646
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 3
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4192
telemt_me_writer_restored_same_endpoint_total 3993
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 52017
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 582434836 (555.45 MB)
telemt_user_octets_to_client{user="hello"} 19649259072 (18.30 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 13686.8 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43855
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 2846
telemt_upstream_connect_attempt_total 9611
telemt_upstream_connect_success_total 9582
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9582
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 2072
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2155
telemt_me_route_drop_no_conn_total 18493
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 5
telemt_pool_force_close_total 86
telemt_me_writer_removed_unexpected_total 2155
telemt_me_writer_restored_same_endpoint_total 2054
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 38569
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 349523140 (333.33 MB)
telemt_user_octets_to_client{user="hello"} 20141270212 (18.76 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 13685.9 (3h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55078
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 7920
telemt_upstream_connect_success_total 7901
telemt_upstream_connect_attempts_per_request{bucket="1"} 7901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 878
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 17010
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
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_restored_same_endpoint_total 868
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 53802
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 11087417600 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 21734369756 (20.24 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 34
```