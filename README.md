# Server Metrics 2026-03-04 00:31:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 12054.9 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86181
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 397
telemt_upstream_connect_attempt_total 9608
telemt_upstream_connect_success_total 9561
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9561
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 33047
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
telemt_user_connections_total{user="hello"} 83144
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 653005092 (622.75 MB)
telemt_user_octets_to_client{user="hello"} 25994212496 (24.21 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 12051.6 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40090
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 8893
telemt_upstream_connect_attempt_total 21793
telemt_upstream_connect_success_total 21483
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 21477
telemt_upstream_connect_attempts_per_request{bucket="2"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 11610
telemt_me_reconnect_success_total 11607
telemt_me_reader_eof_total 11851
telemt_me_idle_close_by_peer_total 11850
telemt_me_route_drop_no_conn_total 15037
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 11913
telemt_me_writer_restored_same_endpoint_total 11587
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 30610
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 188894108 (180.14 MB)
telemt_user_octets_to_client{user="hello"} 15099269776 (14.06 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 12050.3 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92904
telemt_connections_bad_total 29949
telemt_handshake_timeouts_total 1858
telemt_upstream_connect_attempt_total 13663
telemt_upstream_connect_success_total 13582
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 13582
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 167
telemt_me_reconnect_attempts_total 4782
telemt_me_reconnect_success_total 4782
telemt_me_reader_eof_total 4978
telemt_me_idle_close_by_peer_total 4977
telemt_me_route_drop_no_conn_total 18378
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
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4979
telemt_me_writer_restored_same_endpoint_total 4761
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 59859
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 366779184 (349.79 MB)
telemt_user_octets_to_client{user="hello"} 15377294340 (14.32 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 12049.2 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41362
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 510
telemt_upstream_connect_attempt_total 8122
telemt_upstream_connect_success_total 8091
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8091
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1269
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1280
telemt_me_route_drop_no_conn_total 14957
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
telemt_me_writer_removed_unexpected_total 1280
telemt_me_writer_restored_same_endpoint_total 1261
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 40030
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 381546640 (363.87 MB)
telemt_user_octets_to_client{user="hello"} 10943026380 (10.19 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 12047.9 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100646
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 42249
telemt_upstream_connect_attempt_total 14944
telemt_upstream_connect_success_total 14834
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 14834
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 6750
telemt_me_reconnect_success_total 6759
telemt_me_reader_eof_total 7163
telemt_me_idle_close_by_peer_total 7163
telemt_me_route_drop_no_conn_total 35500
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
telemt_me_writer_removed_unexpected_total 7168
telemt_me_writer_restored_same_endpoint_total 6735
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 56441
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 282593228 (269.50 MB)
telemt_user_octets_to_client{user="hello"} 14465438732 (13.47 GB)
telemt_user_unique_ips_current{user="hello"} 11
```