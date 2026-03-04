# Server Metrics 2026-03-04 00:41:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 12670.7 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90070
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 9756
telemt_upstream_connect_success_total 9709
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9709
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 2701
telemt_me_reader_eof_total 2758
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 33888
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
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
telemt_user_connections_total{user="hello"} 86742
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 679155312 (647.69 MB)
telemt_user_octets_to_client{user="hello"} 26825281228 (24.98 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 12667.5 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41766
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 9353
telemt_upstream_connect_attempt_total 23501
telemt_upstream_connect_success_total 23191
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23185
telemt_upstream_connect_attempts_per_request{bucket="2"} 145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 605
telemt_me_reconnect_attempts_total 12777
telemt_me_reconnect_success_total 12772
telemt_me_reader_eof_total 13051
telemt_me_idle_close_by_peer_total 13050
telemt_me_route_drop_no_conn_total 15445
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 13113
telemt_me_writer_restored_same_endpoint_total 12752
telemt_me_writer_removed_unexpected_minus_restored_total 361
telemt_user_connections_total{user="hello"} 31796
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 200144096 (190.87 MB)
telemt_user_octets_to_client{user="hello"} 16157346856 (15.05 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 12666.1 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96318
telemt_connections_bad_total 31554
telemt_handshake_timeouts_total 1896
telemt_upstream_connect_attempt_total 14538
telemt_upstream_connect_success_total 14457
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 14457
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 5104
telemt_me_reconnect_success_total 5102
telemt_me_reader_eof_total 5314
telemt_me_idle_close_by_peer_total 5312
telemt_me_route_drop_no_conn_total 18891
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 216
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 5315
telemt_me_writer_restored_same_endpoint_total 5081
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 61617
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 381980872 (364.29 MB)
telemt_user_octets_to_client{user="hello"} 15762934692 (14.68 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 12665.1 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42988
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 514
telemt_upstream_connect_attempt_total 8457
telemt_upstream_connect_success_total 8426
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8426
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 1294
telemt_me_reconnect_success_total 1305
telemt_me_reader_eof_total 1304
telemt_me_idle_close_by_peer_total 1304
telemt_me_route_drop_no_conn_total 15380
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 9
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 3
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 1304
telemt_me_writer_restored_same_endpoint_total 1285
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 41602
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 390186892 (372.11 MB)
telemt_user_octets_to_client{user="hello"} 11075066548 (10.31 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 12663.8 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104543
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 44279
telemt_upstream_connect_attempt_total 16580
telemt_upstream_connect_success_total 16469
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16469
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 7825
telemt_me_reconnect_success_total 7831
telemt_me_reader_eof_total 8315
telemt_me_idle_close_by_peer_total 8314
telemt_me_route_drop_no_conn_total 35879
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 61
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 8320
telemt_me_writer_restored_same_endpoint_total 7807
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 58192
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 287433656 (274.12 MB)
telemt_user_octets_to_client{user="hello"} 14622133948 (13.62 GB)
telemt_user_unique_ips_current{user="hello"} 12
```