# Server Metrics 2026-03-04 00:36:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 12361.8 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88299
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 9679
telemt_upstream_connect_success_total 9632
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9632
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 33449
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2756
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 85062
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 658964564 (628.44 MB)
telemt_user_octets_to_client{user="hello"} 26576981236 (24.75 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 12358.5 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40776
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 9130
telemt_upstream_connect_attempt_total 22678
telemt_upstream_connect_success_total 22368
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 22362
telemt_upstream_connect_attempts_per_request{bucket="2"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 599
telemt_me_reconnect_attempts_total 12218
telemt_me_reconnect_success_total 12211
telemt_me_reader_eof_total 12475
telemt_me_idle_close_by_peer_total 12474
telemt_me_route_drop_no_conn_total 15203
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 12537
telemt_me_writer_restored_same_endpoint_total 12191
telemt_me_writer_removed_unexpected_minus_restored_total 346
telemt_user_connections_total{user="hello"} 31057
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 194984852 (185.95 MB)
telemt_user_octets_to_client{user="hello"} 15639471292 (14.57 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 12359.4 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94687
telemt_connections_bad_total 30756
telemt_handshake_timeouts_total 1894
telemt_upstream_connect_attempt_total 14115
telemt_upstream_connect_success_total 14034
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 14034
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 4961
telemt_me_reconnect_success_total 4959
telemt_me_reader_eof_total 5166
telemt_me_idle_close_by_peer_total 5164
telemt_me_route_drop_no_conn_total 18615
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 215
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 5167
telemt_me_writer_restored_same_endpoint_total 4938
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 60797
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 378454300 (360.92 MB)
telemt_user_octets_to_client{user="hello"} 15553669512 (14.49 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 12356.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42109
telemt_connections_bad_total 140
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 8282
telemt_upstream_connect_success_total 8251
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8251
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1275
telemt_me_reconnect_success_total 1287
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 15139
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 3
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 1286
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 40756
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 382760792 (365.03 MB)
telemt_user_octets_to_client{user="hello"} 10964900816 (10.21 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 12354.8 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102582
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 43240
telemt_upstream_connect_attempt_total 15796
telemt_upstream_connect_success_total 15686
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 15686
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 7328
telemt_me_reconnect_success_total 7332
telemt_me_reader_eof_total 7796
telemt_me_idle_close_by_peer_total 7795
telemt_me_route_drop_no_conn_total 35664
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 7801
telemt_me_writer_restored_same_endpoint_total 7308
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 57345
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 284653088 (271.47 MB)
telemt_user_octets_to_client{user="hello"} 14539444744 (13.54 GB)
telemt_user_unique_ips_current{user="hello"} 14
```