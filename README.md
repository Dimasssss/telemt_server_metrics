# Server Metrics 2026-03-06 09:25:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 3199.1 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89539
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 936
telemt_upstream_connect_success_total 932
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 7
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 24862
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 411
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 71465
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 1051975540 (1003.24 MB)
telemt_user_octets_to_client{user="hello"} 23597902696 (21.98 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 3196.6 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59236
telemt_connections_bad_total 320
telemt_handshake_timeouts_total 29470
telemt_upstream_connect_attempt_total 1321
telemt_upstream_connect_success_total 1321
telemt_upstream_connect_attempts_per_request{bucket="1"} 1321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 632
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 40
telemt_me_reader_eof_total 42
telemt_me_idle_close_by_peer_total 42
telemt_me_route_drop_no_conn_total 11193
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 118
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 28838
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 450975920 (430.08 MB)
telemt_user_octets_to_client{user="hello"} 9752791124 (9.08 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 3179.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66660
telemt_connections_bad_total 275
telemt_handshake_timeouts_total 9626
telemt_upstream_connect_attempt_total 1369
telemt_upstream_connect_success_total 1356
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 69
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 60
telemt_me_route_drop_no_conn_total 20288
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 148
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_me_writer_removed_unexpected_total 64
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 53870
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 993727712 (947.69 MB)
telemt_user_octets_to_client{user="hello"} 15059102336 (14.02 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 3164.3 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53252
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 11510
telemt_upstream_connect_attempt_total 1417
telemt_upstream_connect_success_total 1402
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 109
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 19324
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 131
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 37414
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 697804560 (665.48 MB)
telemt_user_octets_to_client{user="hello"} 11210207304 (10.44 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 3106.0 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46319
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 1441
telemt_upstream_connect_success_total 1417
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 167
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 19639
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 163
telemt_me_writer_restored_same_endpoint_total 161
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 42115
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 769455068 (733.81 MB)
telemt_user_octets_to_client{user="hello"} 18010924808 (16.77 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 89
```