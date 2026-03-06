# Server Metrics 2026-03-06 10:11:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 5967.4 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170451
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 1615
telemt_upstream_connect_attempt_total 1863
telemt_upstream_connect_success_total 1855
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 73949
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 950
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 713
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 136227
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 2432990824 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 57962035620 (53.98 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 5964.8 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86658
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 30012
telemt_upstream_connect_attempt_total 3823
telemt_upstream_connect_success_total 3823
telemt_upstream_connect_attempts_per_request{bucket="1"} 3823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1798
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 441
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 24798
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 244
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_restored_same_endpoint_total 435
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 55109
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 814707804 (776.97 MB)
telemt_user_octets_to_client{user="hello"} 17829727432 (16.61 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 5948.1 (1h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124109
telemt_connections_bad_total 492
telemt_handshake_timeouts_total 12216
telemt_upstream_connect_attempt_total 3762
telemt_upstream_connect_success_total 3740
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 563
telemt_me_reconnect_success_total 552
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 41502
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_restored_same_endpoint_total 552
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 105895
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 1880576720 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 28395822428 (26.45 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 5932.6 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91380
telemt_connections_bad_total 5372
telemt_handshake_timeouts_total 13703
telemt_upstream_connect_attempt_total 3213
telemt_upstream_connect_success_total 3192
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 515
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 33052
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 209
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 69317
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1036817264 (988.79 MB)
telemt_user_octets_to_client{user="hello"} 20235199356 (18.85 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 5874.4 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86725
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 454
telemt_upstream_connect_attempt_total 4095
telemt_upstream_connect_success_total 4060
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 4092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1033
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_route_drop_no_conn_total 52729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_me_writer_removed_unexpected_total 1065
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 81367
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1695982588 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 36228106296 (33.74 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 100
```