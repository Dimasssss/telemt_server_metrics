# Server Metrics 2026-03-04 00:16:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 11133.8 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80009
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 9464
telemt_upstream_connect_success_total 9421
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 9421
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 32053
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2756
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 77403
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 631788876 (602.52 MB)
telemt_user_octets_to_client{user="hello"} 23970899304 (22.32 GB)
telemt_user_unique_ips_current{user="hello"} 73
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 11130.6 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37624
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 8241
telemt_upstream_connect_attempt_total 19407
telemt_upstream_connect_success_total 19130
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 19124
telemt_upstream_connect_attempts_per_request{bucket="2"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 576
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 10097
telemt_me_reader_eof_total 10296
telemt_me_idle_close_by_peer_total 10295
telemt_me_route_drop_no_conn_total 14508
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 10358
telemt_me_writer_restored_same_endpoint_total 10077
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 28824
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 178912360 (170.62 MB)
telemt_user_octets_to_client{user="hello"} 14315215332 (13.33 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 11129.3 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88071
telemt_connections_bad_total 27556
telemt_handshake_timeouts_total 1813
telemt_upstream_connect_attempt_total 12451
telemt_upstream_connect_success_total 12377
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 12377
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 4415
telemt_me_reconnect_success_total 4416
telemt_me_reader_eof_total 4603
telemt_me_idle_close_by_peer_total 4602
telemt_me_route_drop_no_conn_total 17666
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4604
telemt_me_writer_restored_same_endpoint_total 4395
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 57481
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 353209212 (336.85 MB)
telemt_user_octets_to_client{user="hello"} 14888836048 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 11128.2 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39533
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 506
telemt_upstream_connect_attempt_total 7747
telemt_upstream_connect_success_total 7718
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 7718
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 1256
telemt_me_reconnect_success_total 1267
telemt_me_reader_eof_total 1266
telemt_me_idle_close_by_peer_total 1266
telemt_me_route_drop_no_conn_total 14591
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 3
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 1266
telemt_me_writer_restored_same_endpoint_total 1248
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 38284
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 374262684 (356.92 MB)
telemt_user_octets_to_client{user="hello"} 10859336620 (10.11 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 11126.8 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95034
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 39294
telemt_upstream_connect_attempt_total 12438
telemt_upstream_connect_success_total 12329
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12329
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 5112
telemt_me_reconnect_success_total 5121
telemt_me_reader_eof_total 5404
telemt_me_idle_close_by_peer_total 5404
telemt_me_route_drop_no_conn_total 34730
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 5408
telemt_me_writer_restored_same_endpoint_total 5097
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 53987
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 270033600 (257.52 MB)
telemt_user_octets_to_client{user="hello"} 14303430604 (13.32 GB)
telemt_user_unique_ips_current{user="hello"} 12
```