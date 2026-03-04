# Server Metrics 2026-03-04 00:11:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 10826.9 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77625
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 9268
telemt_upstream_connect_success_total 9227
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 9227
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2620
telemt_me_reconnect_success_total 2624
telemt_me_reader_eof_total 2680
telemt_me_idle_close_by_peer_total 2680
telemt_me_route_drop_no_conn_total 31571
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 2680
telemt_me_writer_restored_same_endpoint_total 2604
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 75195
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 625671908 (596.69 MB)
telemt_user_octets_to_client{user="hello"} 23468505584 (21.86 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 10823.4 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36817
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 8018
telemt_upstream_connect_attempt_total 18650
telemt_upstream_connect_success_total 18409
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 18407
telemt_upstream_connect_attempts_per_request{bucket="2"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 9643
telemt_me_reconnect_success_total 9643
telemt_me_reader_eof_total 9825
telemt_me_idle_close_by_peer_total 9824
telemt_me_route_drop_no_conn_total 14332
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 9829
telemt_me_writer_restored_same_endpoint_total 9623
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 28248
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 177136860 (168.93 MB)
telemt_user_octets_to_client{user="hello"} 14283795948 (13.30 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 10822.2 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86526
telemt_connections_bad_total 26774
telemt_handshake_timeouts_total 1811
telemt_upstream_connect_attempt_total 12036
telemt_upstream_connect_success_total 11964
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11964
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 4305
telemt_me_reconnect_success_total 4307
telemt_me_reader_eof_total 4491
telemt_me_idle_close_by_peer_total 4490
telemt_me_route_drop_no_conn_total 17489
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4492
telemt_me_writer_restored_same_endpoint_total 4286
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 56724
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 351465576 (335.18 MB)
telemt_user_octets_to_client{user="hello"} 14853619660 (13.83 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 10821.2 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38869
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 502
telemt_upstream_connect_attempt_total 7498
telemt_upstream_connect_success_total 7471
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7471
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1205
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 14431
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 1214
telemt_me_writer_restored_same_endpoint_total 1197
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 37653
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 372811040 (355.54 MB)
telemt_user_octets_to_client{user="hello"} 10778386844 (10.04 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 10819.7 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93157
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 38272
telemt_upstream_connect_attempt_total 11660
telemt_upstream_connect_success_total 11557
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11557
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 4651
telemt_me_reconnect_success_total 4660
telemt_me_reader_eof_total 4897
telemt_me_idle_close_by_peer_total 4897
telemt_me_route_drop_no_conn_total 34565
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 52
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 4901
telemt_me_writer_restored_same_endpoint_total 4636
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 53156
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 267209340 (254.83 MB)
telemt_user_octets_to_client{user="hello"} 14196484292 (13.22 GB)
telemt_user_unique_ips_current{user="hello"} 17
```