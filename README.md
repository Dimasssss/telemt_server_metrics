# Server Metrics 2026-03-04 13:40:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 59399.7 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065150
telemt_connections_bad_total 13902
telemt_handshake_timeouts_total 17638
telemt_upstream_connect_attempt_total 35137
telemt_upstream_connect_success_total 34980
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 34980
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 393
telemt_me_reconnect_attempts_total 7367
telemt_me_reconnect_success_total 7311
telemt_me_reader_eof_total 7538
telemt_me_idle_close_by_peer_total 7537
telemt_me_route_drop_no_conn_total 382730
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1761
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7538
telemt_me_writer_restored_same_endpoint_total 7289
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 841513
telemt_user_connections_current{user="hello"} 1170
telemt_user_octets_from_client{user="hello"} 9562446612 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 283694956572 (264.21 GB)
telemt_user_unique_ips_current{user="hello"} 96
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 59396.1 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413067
telemt_connections_bad_total 3535
telemt_handshake_timeouts_total 29152
telemt_upstream_connect_attempt_total 106604
telemt_upstream_connect_success_total 104996
telemt_upstream_connect_fail_total 766
telemt_upstream_connect_attempts_per_request{bucket="1"} 104990
telemt_upstream_connect_attempts_per_request{bucket="2"} 772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 766
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 58614
telemt_me_reconnect_success_total 58520
telemt_me_reader_eof_total 60013
telemt_me_idle_close_by_peer_total 60012
telemt_me_route_drop_no_conn_total 166898
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 60093
telemt_me_writer_restored_same_endpoint_total 58495
telemt_me_writer_removed_unexpected_minus_restored_total 1598
telemt_user_connections_total{user="hello"} 318427
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 4119389144 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 101264299756 (94.31 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 59395.0 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806031
telemt_connections_bad_total 176674
telemt_handshake_timeouts_total 28521
telemt_upstream_connect_attempt_total 82893
telemt_upstream_connect_success_total 82376
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 82375
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1077
telemt_me_reconnect_attempts_total 37922
telemt_me_reconnect_success_total 37825
telemt_me_reader_eof_total 39818
telemt_me_idle_close_by_peer_total 39814
telemt_me_route_drop_no_conn_total 296227
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1591
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 519
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39830
telemt_me_writer_restored_same_endpoint_total 37803
telemt_me_writer_removed_unexpected_minus_restored_total 2027
telemt_user_connections_total{user="hello"} 563735
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 12126866528 (11.29 GB)
telemt_user_octets_to_client{user="hello"} 190848500000 (177.74 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 6072.3 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74615
telemt_connections_bad_total 7249
telemt_handshake_timeouts_total 1140
telemt_upstream_connect_attempt_total 2502
telemt_upstream_connect_success_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 2501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 942
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 260
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 26183
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 86
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 264
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 65136
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 1155536172 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 42283944284 (39.38 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 6431.5 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114864
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1967
telemt_upstream_connect_attempt_total 4683
telemt_upstream_connect_success_total 4666
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 4666
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 1201
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1235
telemt_me_idle_close_by_peer_total 1235
telemt_me_route_drop_no_conn_total 39271
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 304
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 1
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 98890
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 1041756332 (993.50 MB)
telemt_user_octets_to_client{user="hello"} 27066561740 (25.21 GB)
telemt_user_unique_ips_current{user="hello"} 62
```