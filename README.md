# Server Metrics 2026-03-06 00:32:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 7861.6 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56271
telemt_connections_bad_total 14181
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 5169
telemt_upstream_connect_success_total 5120
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5120
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 937
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 10727
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 956
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 40365
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 536069480 (511.24 MB)
telemt_user_octets_to_client{user="hello"} 14518458300 (13.52 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 7857.0 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17533
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 6648
telemt_upstream_connect_success_total 6646
telemt_upstream_connect_attempts_per_request{bucket="1"} 6646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1464
telemt_me_route_drop_no_conn_total 5471
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 46
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_restored_same_endpoint_total 1446
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 16876
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 127704408 (121.79 MB)
telemt_user_octets_to_client{user="hello"} 3536417936 (3.29 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 7854.3 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31501
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 8749
telemt_upstream_connect_success_total 8685
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 8685
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 3158
telemt_me_reconnect_success_total 3152
telemt_me_reader_eof_total 3313
telemt_me_idle_close_by_peer_total 3313
telemt_me_route_drop_no_conn_total 8483
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 77
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 3314
telemt_me_writer_restored_same_endpoint_total 3146
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 30244
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 425380112 (405.67 MB)
telemt_user_octets_to_client{user="hello"} 11688762032 (10.89 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 7851.0 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24088
telemt_connections_bad_total 161
telemt_handshake_timeouts_total 676
telemt_upstream_connect_attempt_total 3913
telemt_upstream_connect_success_total 3896
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3896
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 368
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 369
telemt_me_idle_close_by_peer_total 369
telemt_me_route_drop_no_conn_total 11166
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 369
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 22027
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 236787740 (225.82 MB)
telemt_user_octets_to_client{user="hello"} 16426957604 (15.30 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 7850.0 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32483
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 4663
telemt_upstream_connect_success_total 4656
telemt_upstream_connect_attempts_per_request{bucket="1"} 4656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 677
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 689
telemt_me_idle_close_by_peer_total 689
telemt_me_route_drop_no_conn_total 11720
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 689
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 31883
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 10965818392 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 17739935112 (16.52 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```