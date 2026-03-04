# Server Metrics 2026-03-04 02:39:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 19732.7 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125861
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 1046
telemt_upstream_connect_attempt_total 15868
telemt_upstream_connect_success_total 15799
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 15799
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 4090
telemt_me_reconnect_success_total 4083
telemt_me_reader_eof_total 4175
telemt_me_idle_close_by_peer_total 4175
telemt_me_route_drop_no_conn_total 44912
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 225
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4175
telemt_me_writer_restored_same_endpoint_total 4063
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 120621
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 1027940008 (980.32 MB)
telemt_user_octets_to_client{user="hello"} 35807404092 (33.35 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 19729.4 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59076
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 15343
telemt_upstream_connect_attempt_total 46890
telemt_upstream_connect_success_total 46372
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 46366
telemt_upstream_connect_attempts_per_request{bucket="2"} 249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 821
telemt_me_reconnect_attempts_total 28733
telemt_me_reconnect_success_total 28713
telemt_me_reader_eof_total 29468
telemt_me_idle_close_by_peer_total 29467
telemt_me_route_drop_no_conn_total 19623
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 29529
telemt_me_writer_restored_same_endpoint_total 28693
telemt_me_writer_removed_unexpected_minus_restored_total 836
telemt_user_connections_total{user="hello"} 42762
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 335801508 (320.25 MB)
telemt_user_octets_to_client{user="hello"} 23748217496 (22.12 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 19728.0 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139599
telemt_connections_bad_total 50036
telemt_handshake_timeouts_total 3251
telemt_upstream_connect_attempt_total 23351
telemt_upstream_connect_success_total 23200
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 23200
telemt_upstream_connect_attempts_per_request{bucket="2"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 8083
telemt_me_reconnect_success_total 8067
telemt_me_reader_eof_total 8409
telemt_me_idle_close_by_peer_total 8407
telemt_me_route_drop_no_conn_total 26979
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 8411
telemt_me_writer_restored_same_endpoint_total 8046
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 82983
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 506518936 (483.05 MB)
telemt_user_octets_to_client{user="hello"} 20384203068 (18.98 GB)
telemt_user_unique_ips_current{user="hello"} 13
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 19726.9 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62538
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 649
telemt_upstream_connect_attempt_total 12341
telemt_upstream_connect_success_total 12280
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12280
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 1666
telemt_me_reconnect_success_total 1671
telemt_me_reader_eof_total 1678
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 21633
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 23
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1678
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 60584
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 496193488 (473.21 MB)
telemt_user_octets_to_client{user="hello"} 19999050752 (18.63 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 19725.8 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150695
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 67820
telemt_upstream_connect_attempt_total 28840
telemt_upstream_connect_success_total 28663
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 28663
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 386
telemt_me_reconnect_attempts_total 14501
telemt_me_reconnect_success_total 14499
telemt_me_reader_eof_total 15410
telemt_me_idle_close_by_peer_total 15409
telemt_me_route_drop_no_conn_total 42026
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2173
telemt_me_writer_removed_unexpected_total 15415
telemt_me_writer_restored_same_endpoint_total 14475
telemt_me_writer_removed_unexpected_minus_restored_total 940
telemt_user_connections_total{user="hello"} 79886
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 458923248 (437.66 MB)
telemt_user_octets_to_client{user="hello"} 17986487196 (16.75 GB)
telemt_user_unique_ips_current{user="hello"} 19
```