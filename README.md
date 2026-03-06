# Server Metrics 2026-03-06 10:06:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 5659.4 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160935
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 1436
telemt_upstream_connect_attempt_total 1830
telemt_upstream_connect_success_total 1822
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 71561
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 867
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 647
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 129185
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 2327610196 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 55045917664 (51.27 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 5656.6 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83196
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 29952
telemt_upstream_connect_attempt_total 3500
telemt_upstream_connect_success_total 3500
telemt_upstream_connect_attempts_per_request{bucket="1"} 3500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1633
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 373
telemt_me_route_drop_no_conn_total 22844
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 239
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 51796
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 794228344 (757.44 MB)
telemt_user_octets_to_client{user="hello"} 16512291208 (15.38 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 5639.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116867
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 12027
telemt_upstream_connect_attempt_total 3449
telemt_upstream_connect_success_total 3427
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 468
telemt_me_reconnect_success_total 457
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 37597
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 270
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 99883
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 1593720308 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 26965844656 (25.11 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 5624.6 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87351
telemt_connections_bad_total 5093
telemt_handshake_timeouts_total 13364
telemt_upstream_connect_attempt_total 3085
telemt_upstream_connect_success_total 3064
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 514
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 31569
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 186
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 514
telemt_me_writer_restored_same_endpoint_total 505
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 66075
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 980744008 (935.31 MB)
telemt_user_octets_to_client{user="hello"} 19250852848 (17.93 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 5566.1 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80919
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 431
telemt_upstream_connect_attempt_total 3724
telemt_upstream_connect_success_total 3689
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 882
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 901
telemt_me_idle_close_by_peer_total 901
telemt_me_route_drop_no_conn_total 44260
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 905
telemt_me_writer_restored_same_endpoint_total 872
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 75728
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1240634560 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 34527615916 (32.16 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 115
```