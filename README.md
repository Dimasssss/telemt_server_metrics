# Server Metrics 2026-03-06 00:06:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 6325.9 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48385
telemt_connections_bad_total 14114
telemt_handshake_timeouts_total 443
telemt_upstream_connect_attempt_total 3954
telemt_upstream_connect_success_total 3921
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3921
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 756
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 771
telemt_me_idle_close_by_peer_total 771
telemt_me_route_drop_no_conn_total 8618
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 48
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 771
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 32900
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 460923612 (439.57 MB)
telemt_user_octets_to_client{user="hello"} 13032972068 (12.14 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 6321.4 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14898
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 5734
telemt_upstream_connect_success_total 5732
telemt_upstream_connect_attempts_per_request{bucket="1"} 5732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 1388
telemt_me_reader_eof_total 1399
telemt_me_idle_close_by_peer_total 1399
telemt_me_route_drop_no_conn_total 4991
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 1400
telemt_me_writer_restored_same_endpoint_total 1384
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 14305
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 110551496 (105.43 MB)
telemt_user_octets_to_client{user="hello"} 3103122536 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 6318.8 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25233
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 6400
telemt_upstream_connect_success_total 6351
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 6351
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1970
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 2061
telemt_me_idle_close_by_peer_total 2061
telemt_me_route_drop_no_conn_total 7052
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 2062
telemt_me_writer_restored_same_endpoint_total 1960
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 24522
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 386134056 (368.25 MB)
telemt_user_octets_to_client{user="hello"} 6889173020 (6.42 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 6315.5 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19832
telemt_connections_bad_total 158
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 3230
telemt_upstream_connect_success_total 3217
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 3217
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 325
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 326
telemt_me_idle_close_by_peer_total 326
telemt_me_route_drop_no_conn_total 9415
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_restored_same_endpoint_total 317
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 17963
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 177057516 (168.86 MB)
telemt_user_octets_to_client{user="hello"} 15339257340 (14.29 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 6314.2 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26649
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 3863
telemt_upstream_connect_success_total 3859
telemt_upstream_connect_attempts_per_request{bucket="1"} 3859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 643
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 10192
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 12
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 22
telemt_me_writer_removed_unexpected_total 652
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 26117
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 10951061648 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 16984720544 (15.82 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 29
```