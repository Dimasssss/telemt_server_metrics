# Server Metrics 2026-03-04 22:34:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 6087.7 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68071
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 5176
telemt_upstream_connect_success_total 5116
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5116
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 16852
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1398
telemt_me_writer_restored_same_endpoint_total 1363
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 57082
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 2299048728 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 28728622852 (26.76 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 6082.3 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24382
telemt_connections_bad_total 677
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 5792
telemt_upstream_connect_success_total 5711
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5711
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1770
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1798
telemt_me_idle_close_by_peer_total 1798
telemt_me_route_drop_no_conn_total 7505
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 1822
telemt_me_writer_restored_same_endpoint_total 1753
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 22822
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 208318144 (198.67 MB)
telemt_user_octets_to_client{user="hello"} 6391192664 (5.95 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 6078.9 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55526
telemt_connections_bad_total 996
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 2114
telemt_upstream_connect_success_total 2091
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2091
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 60
telemt_me_reconnect_success_total 73
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 16791
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 58
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 50768
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 696115048 (663.87 MB)
telemt_user_octets_to_client{user="hello"} 20697109928 (19.28 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 38127.1 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517821
telemt_connections_bad_total 69318
telemt_handshake_timeouts_total 14659
telemt_upstream_connect_attempt_total 16613
telemt_upstream_connect_success_total 16613
telemt_upstream_connect_attempts_per_request{bucket="1"} 16613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 2183
telemt_me_reconnect_success_total 2168
telemt_me_reader_eof_total 2210
telemt_me_idle_close_by_peer_total 2210
telemt_me_route_drop_no_conn_total 177809
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 14
telemt_pool_force_close_total 440
telemt_me_writer_removed_unexpected_total 2211
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 405626
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 5696218668 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 154415314208 (143.81 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 38486.4 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518439
telemt_connections_bad_total 3761
telemt_handshake_timeouts_total 5754
telemt_upstream_connect_attempt_total 22763
telemt_upstream_connect_success_total 22641
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 22641
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 4682
telemt_me_reconnect_success_total 4668
telemt_me_reader_eof_total 4835
telemt_me_idle_close_by_peer_total 4835
telemt_me_route_drop_no_conn_total 228709
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4838
telemt_me_writer_restored_same_endpoint_total 4647
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 468369
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 7217128748 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 151408923484 (141.01 GB)
telemt_user_unique_ips_current{user="hello"} 32
```