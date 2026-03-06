# Server Metrics 2026-03-06 01:39:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 11854.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79434
telemt_connections_bad_total 15876
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 10027
telemt_upstream_connect_success_total 9933
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9933
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 2752
telemt_me_reconnect_success_total 2737
telemt_me_reader_eof_total 2847
telemt_me_idle_close_by_peer_total 2847
telemt_me_route_drop_no_conn_total 18829
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 2
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 2847
telemt_me_writer_restored_same_endpoint_total 2731
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 61233
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 672360232 (641.21 MB)
telemt_user_octets_to_client{user="hello"} 22894021780 (21.32 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 11850.1 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26447
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 9254
telemt_upstream_connect_success_total 9252
telemt_upstream_connect_attempts_per_request{bucket="1"} 9252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 1667
telemt_me_reconnect_success_total 1659
telemt_me_reader_eof_total 1676
telemt_me_idle_close_by_peer_total 1676
telemt_me_route_drop_no_conn_total 7266
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
telemt_me_writer_removed_unexpected_total 1677
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 25623
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 169099100 (161.27 MB)
telemt_user_octets_to_client{user="hello"} 5820159020 (5.42 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 11847.5 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47086
telemt_connections_bad_total 323
telemt_handshake_timeouts_total 306
telemt_upstream_connect_attempt_total 11862
telemt_upstream_connect_success_total 11750
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11750
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 3814
telemt_me_reconnect_success_total 3803
telemt_me_reader_eof_total 3990
telemt_me_idle_close_by_peer_total 3990
telemt_me_route_drop_no_conn_total 12143
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 3991
telemt_me_writer_restored_same_endpoint_total 3796
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 44564
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 530701252 (506.12 MB)
telemt_user_octets_to_client{user="hello"} 17897300248 (16.67 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 11844.2 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37419
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 2618
telemt_upstream_connect_attempt_total 8812
telemt_upstream_connect_success_total 8787
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 8787
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2021
telemt_me_reconnect_success_total 2011
telemt_me_reader_eof_total 2105
telemt_me_idle_close_by_peer_total 2105
telemt_me_route_drop_no_conn_total 15920
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 4
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 2105
telemt_me_writer_restored_same_endpoint_total 2006
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 32682
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 316439300 (301.78 MB)
telemt_user_octets_to_client{user="hello"} 19096216468 (17.78 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 11843.1 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47299
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 202
telemt_upstream_connect_attempt_total 6953
telemt_upstream_connect_success_total 6937
telemt_upstream_connect_attempts_per_request{bucket="1"} 6937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 833
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 15120
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 5
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 46351
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 11053168332 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 20619706356 (19.20 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```