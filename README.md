# Server Metrics 2026-03-06 18:30:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 1317.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35832
telemt_connections_bad_total 495
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 688
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 36
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 11502
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 32356
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 1077795576 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 11535110624 (10.74 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 1317.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11861
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 1708
telemt_upstream_connect_success_total 1708
telemt_upstream_connect_attempts_per_request{bucket="1"} 1708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1457
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 489
telemt_me_reconnect_success_total 489
telemt_me_reader_eof_total 615
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 3818
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 615
telemt_me_writer_restored_same_endpoint_total 487
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 11340
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 162350404 (154.83 MB)
telemt_user_octets_to_client{user="hello"} 3126736508 (2.91 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 1317.3 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24007
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 449
telemt_upstream_connect_attempt_total 1075
telemt_upstream_connect_success_total 1065
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 105
telemt_me_reader_eof_total 116
telemt_me_idle_close_by_peer_total 116
telemt_me_route_drop_no_conn_total 6538
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 117
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 118
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 22439
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 394230064 (375.97 MB)
telemt_user_octets_to_client{user="hello"} 4368490732 (4.07 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 1317.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27994
telemt_connections_bad_total 10878
telemt_handshake_timeouts_total 692
telemt_upstream_connect_attempt_total 897
telemt_upstream_connect_success_total 885
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 4507
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 66
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 15770
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 76727316 (73.17 MB)
telemt_user_octets_to_client{user="hello"} 5073741480 (4.73 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 1316.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23551
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 760
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 85
telemt_me_reconnect_success_total 83
telemt_me_reader_eof_total 105
telemt_me_idle_close_by_peer_total 105
telemt_me_route_drop_no_conn_total 6513
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 101
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 21920
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 635194484 (605.77 MB)
telemt_user_octets_to_client{user="hello"} 9644300544 (8.98 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 80
```