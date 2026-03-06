# Server Metrics 2026-03-06 02:40:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 15540.1 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103790
telemt_connections_bad_total 15904
telemt_handshake_timeouts_total 1006
telemt_upstream_connect_attempt_total 13823
telemt_upstream_connect_success_total 13705
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13705
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 3905
telemt_me_reconnect_success_total 3888
telemt_me_reader_eof_total 4020
telemt_me_idle_close_by_peer_total 4020
telemt_me_route_drop_no_conn_total 26761
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 270
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 2
telemt_pool_force_close_total 91
telemt_me_writer_removed_unexpected_total 4020
telemt_me_writer_restored_same_endpoint_total 3882
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 82288
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 969545964 (924.63 MB)
telemt_user_octets_to_client{user="hello"} 31444002952 (29.28 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 15535.6 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34527
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 428
telemt_upstream_connect_attempt_total 11003
telemt_upstream_connect_success_total 11001
telemt_upstream_connect_attempts_per_request{bucket="1"} 11001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 1706
telemt_me_reader_eof_total 1723
telemt_me_idle_close_by_peer_total 1723
telemt_me_route_drop_no_conn_total 10195
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1724
telemt_me_writer_restored_same_endpoint_total 1700
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 33488
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 220451784 (210.24 MB)
telemt_user_octets_to_client{user="hello"} 7698008488 (7.17 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 15532.9 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62537
telemt_connections_bad_total 538
telemt_handshake_timeouts_total 815
telemt_upstream_connect_attempt_total 14046
telemt_upstream_connect_success_total 13925
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13925
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 4068
telemt_me_reconnect_success_total 4054
telemt_me_reader_eof_total 4247
telemt_me_idle_close_by_peer_total 4247
telemt_me_route_drop_no_conn_total 17569
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4248
telemt_me_writer_restored_same_endpoint_total 4047
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 58763
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 606976692 (578.86 MB)
telemt_user_octets_to_client{user="hello"} 20839879340 (19.41 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 15529.7 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49370
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 2952
telemt_upstream_connect_attempt_total 10188
telemt_upstream_connect_success_total 10155
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 10155
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 2088
telemt_me_reconnect_success_total 2075
telemt_me_reader_eof_total 2169
telemt_me_idle_close_by_peer_total 2169
telemt_me_route_drop_no_conn_total 19943
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2169
telemt_me_writer_restored_same_endpoint_total 2068
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 43616
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 384220236 (366.42 MB)
telemt_user_octets_to_client{user="hello"} 21548649964 (20.07 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 15528.5 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61860
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 406
telemt_upstream_connect_attempt_total 9181
telemt_upstream_connect_success_total 9160
telemt_upstream_connect_attempts_per_request{bucket="1"} 9160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 18913
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 62
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1049
telemt_me_writer_restored_same_endpoint_total 1022
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 59957
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 11993409428 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 23702745820 (22.07 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 39
```