# Server Metrics 2026-03-06 00:12:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 6633.1 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49820
telemt_connections_bad_total 14115
telemt_handshake_timeouts_total 445
telemt_upstream_connect_attempt_total 4195
telemt_upstream_connect_success_total 4150
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4150
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 771
telemt_me_reader_eof_total 790
telemt_me_idle_close_by_peer_total 790
telemt_me_route_drop_no_conn_total 8954
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 34312
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 466208456 (444.61 MB)
telemt_user_octets_to_client{user="hello"} 13282723636 (12.37 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 6628.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15457
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 5948
telemt_upstream_connect_success_total 5946
telemt_upstream_connect_attempts_per_request{bucket="1"} 5946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1424
telemt_me_reconnect_success_total 1424
telemt_me_reader_eof_total 1435
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 5062
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1436
telemt_me_writer_restored_same_endpoint_total 1420
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 14855
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 112564108 (107.35 MB)
telemt_user_octets_to_client{user="hello"} 3182995152 (2.96 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 6626.0 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26440
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 7007
telemt_upstream_connect_success_total 6948
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6948
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 2248
telemt_me_reconnect_success_total 2243
telemt_me_reader_eof_total 2346
telemt_me_idle_close_by_peer_total 2346
telemt_me_route_drop_no_conn_total 7331
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 2347
telemt_me_writer_restored_same_endpoint_total 2238
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 25716
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 390395252 (372.31 MB)
telemt_user_octets_to_client{user="hello"} 7147864596 (6.66 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 6622.6 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20699
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 3387
telemt_upstream_connect_success_total 3372
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3372
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 9571
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 18795
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 179849628 (171.52 MB)
telemt_user_octets_to_client{user="hello"} 15551049176 (14.48 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 6621.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28084
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 4031
telemt_upstream_connect_success_total 4027
telemt_upstream_connect_attempts_per_request{bucket="1"} 4027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 10685
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 13
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 2
telemt_pool_force_close_total 42
telemt_me_writer_removed_unexpected_total 666
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 27541
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 10953888176 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 17332688012 (16.14 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```