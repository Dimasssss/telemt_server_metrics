# Server Metrics 2026-03-06 01:08:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 10011.6 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69316
telemt_connections_bad_total 15836
telemt_handshake_timeouts_total 634
telemt_upstream_connect_attempt_total 7791
telemt_upstream_connect_success_total 7730
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7730
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1811
telemt_me_idle_close_by_peer_total 1811
telemt_me_route_drop_no_conn_total 15433
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 1811
telemt_me_writer_restored_same_endpoint_total 1745
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 51449
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 597555212 (569.87 MB)
telemt_user_octets_to_client{user="hello"} 20074699548 (18.70 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 10007.0 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22430
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 317
telemt_upstream_connect_attempt_total 8164
telemt_upstream_connect_success_total 8162
telemt_upstream_connect_attempts_per_request{bucket="1"} 8162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 1592
telemt_me_reader_eof_total 1608
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 6437
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 3
telemt_pool_force_close_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1609
telemt_me_writer_restored_same_endpoint_total 1588
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 21671
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 158599496 (151.25 MB)
telemt_user_octets_to_client{user="hello"} 5558882552 (5.18 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 10004.4 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39394
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 233
telemt_upstream_connect_attempt_total 10335
telemt_upstream_connect_success_total 10240
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10240
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 3418
telemt_me_reconnect_success_total 3408
telemt_me_reader_eof_total 3576
telemt_me_idle_close_by_peer_total 3576
telemt_me_route_drop_no_conn_total 10075
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3577
telemt_me_writer_restored_same_endpoint_total 3402
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 37600
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 479915116 (457.68 MB)
telemt_user_octets_to_client{user="hello"} 16694349148 (15.55 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 10001.1 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30680
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 1122
telemt_upstream_connect_attempt_total 6090
telemt_upstream_connect_success_total 6067
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 6067
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2502
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 950
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 973
telemt_me_idle_close_by_peer_total 973
telemt_me_route_drop_no_conn_total 13145
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 67
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 973
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 27868
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 279890468 (266.92 MB)
telemt_user_octets_to_client{user="hello"} 17460087088 (16.26 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 9999.8 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40155
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 5557
telemt_upstream_connect_success_total 5546
telemt_upstream_connect_attempts_per_request{bucket="1"} 5546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 691
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 701
telemt_me_idle_close_by_peer_total 701
telemt_me_route_drop_no_conn_total 13335
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 39428
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 11029268336 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 18821973936 (17.53 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 33
```