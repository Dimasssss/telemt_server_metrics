# Server Metrics 2026-03-04 00:46:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 12977.7 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91471
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 491
telemt_upstream_connect_attempt_total 9945
telemt_upstream_connect_success_total 9896
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 9896
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 2701
telemt_me_reader_eof_total 2758
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 34365
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2758
telemt_me_writer_restored_same_endpoint_total 2681
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 88104
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 684725280 (653.00 MB)
telemt_user_octets_to_client{user="hello"} 27037105628 (25.18 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 12974.3 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42484
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 9586
telemt_upstream_connect_attempt_total 24473
telemt_upstream_connect_success_total 24140
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 24134
telemt_upstream_connect_attempts_per_request{bucket="2"} 156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 613
telemt_me_reconnect_attempts_total 13408
telemt_me_reconnect_success_total 13401
telemt_me_reader_eof_total 13708
telemt_me_idle_close_by_peer_total 13707
telemt_me_route_drop_no_conn_total 15708
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 13770
telemt_me_writer_restored_same_endpoint_total 13381
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 32273
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 206018128 (196.47 MB)
telemt_user_octets_to_client{user="hello"} 17693539792 (16.48 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 12973.2 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98252
telemt_connections_bad_total 32398
telemt_handshake_timeouts_total 1901
telemt_upstream_connect_attempt_total 15013
telemt_upstream_connect_success_total 14926
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 14926
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 5270
telemt_me_reconnect_success_total 5266
telemt_me_reader_eof_total 5485
telemt_me_idle_close_by_peer_total 5483
telemt_me_route_drop_no_conn_total 19146
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 216
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 5486
telemt_me_writer_restored_same_endpoint_total 5245
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 62694
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 386905660 (368.98 MB)
telemt_user_octets_to_client{user="hello"} 15902125044 (14.81 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 12972.1 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43721
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 518
telemt_upstream_connect_attempt_total 8573
telemt_upstream_connect_success_total 8542
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8542
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 1296
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1306
telemt_me_idle_close_by_peer_total 1306
telemt_me_route_drop_no_conn_total 15579
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1306
telemt_me_writer_restored_same_endpoint_total 1287
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 42317
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 392590352 (374.40 MB)
telemt_user_octets_to_client{user="hello"} 11218366932 (10.45 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 12970.6 (3h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106487
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 45279
telemt_upstream_connect_attempt_total 17374
telemt_upstream_connect_success_total 17258
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 17258
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 229
telemt_me_reconnect_attempts_total 8306
telemt_me_reconnect_success_total 8310
telemt_me_reader_eof_total 8838
telemt_me_idle_close_by_peer_total 8837
telemt_me_route_drop_no_conn_total 36013
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 8843
telemt_me_writer_restored_same_endpoint_total 8286
telemt_me_writer_removed_unexpected_minus_restored_total 557
telemt_user_connections_total{user="hello"} 59116
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 290894564 (277.42 MB)
telemt_user_octets_to_client{user="hello"} 14780624940 (13.77 GB)
telemt_user_unique_ips_current{user="hello"} 21
```