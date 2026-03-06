# Server Metrics 2026-03-06 01:59:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 13082.9 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86165
telemt_connections_bad_total 15901
telemt_handshake_timeouts_total 792
telemt_upstream_connect_attempt_total 10905
telemt_upstream_connect_success_total 10794
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 10794
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2945
telemt_me_reconnect_success_total 2929
telemt_me_reader_eof_total 3040
telemt_me_idle_close_by_peer_total 3040
telemt_me_route_drop_no_conn_total 20413
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 166
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3040
telemt_me_writer_restored_same_endpoint_total 2923
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 67781
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 767407032 (731.86 MB)
telemt_user_octets_to_client{user="hello"} 23791525508 (22.16 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 13078.4 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29123
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 371
telemt_upstream_connect_attempt_total 9944
telemt_upstream_connect_success_total 9942
telemt_upstream_connect_attempts_per_request{bucket="1"} 9942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1690
telemt_me_reconnect_success_total 1680
telemt_me_reader_eof_total 1697
telemt_me_idle_close_by_peer_total 1697
telemt_me_route_drop_no_conn_total 7817
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
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1698
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 28249
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 181880824 (173.46 MB)
telemt_user_octets_to_client{user="hello"} 6250236712 (5.82 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 13075.9 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52801
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 415
telemt_upstream_connect_attempt_total 12638
telemt_upstream_connect_success_total 12522
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 12522
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 3914
telemt_me_reconnect_success_total 3903
telemt_me_reader_eof_total 4093
telemt_me_idle_close_by_peer_total 4093
telemt_me_route_drop_no_conn_total 13663
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 4094
telemt_me_writer_restored_same_endpoint_total 3896
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 49696
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 560597160 (534.63 MB)
telemt_user_octets_to_client{user="hello"} 18736488008 (17.45 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 13072.5 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41597
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 2735
telemt_upstream_connect_attempt_total 9247
telemt_upstream_connect_success_total 9218
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9218
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 2041
telemt_me_reconnect_success_total 2029
telemt_me_reader_eof_total 2123
telemt_me_idle_close_by_peer_total 2123
telemt_me_route_drop_no_conn_total 17013
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 4
telemt_pool_force_close_total 86
telemt_me_writer_removed_unexpected_total 2123
telemt_me_writer_restored_same_endpoint_total 2024
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 36468
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 343860424 (327.93 MB)
telemt_user_octets_to_client{user="hello"} 19905104248 (18.54 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 13071.3 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52500
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 213
telemt_upstream_connect_attempt_total 7493
telemt_upstream_connect_success_total 7476
telemt_upstream_connect_attempts_per_request{bucket="1"} 7476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 844
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 16345
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 48
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 5
telemt_pool_force_close_total 79
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 51425
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 11077379968 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 21437121236 (19.96 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 33
```