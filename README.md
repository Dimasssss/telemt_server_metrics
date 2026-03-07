# Server Metrics 2026-03-07 00:19:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 22283.4 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293152
telemt_connections_bad_total 3006
telemt_handshake_timeouts_total 9346
telemt_upstream_connect_attempt_total 58243
telemt_upstream_connect_success_total 56697
telemt_upstream_connect_fail_total 1409
telemt_upstream_connect_attempts_per_request{bucket="1"} 58106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1409
telemt_me_keepalive_timeout_total 1517
telemt_me_reconnect_attempts_total 31409
telemt_me_reconnect_success_total 30054
telemt_me_reader_eof_total 32471
telemt_me_idle_close_by_peer_total 32471
telemt_me_route_drop_no_conn_total 113397
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 9
telemt_pool_force_close_total 474
telemt_pool_stale_pick_total 186
telemt_me_writer_removed_unexpected_total 32584
telemt_me_writer_restored_same_endpoint_total 29967
telemt_me_writer_restored_fallback_total 81
telemt_me_async_recovery_trigger_total 24768
telemt_me_writer_removed_unexpected_minus_restored_total 2536
telemt_user_connections_total{user="hello"} 266067
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 4159504052 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 118626370900 (110.48 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 22283.4 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124339
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 14105
telemt_upstream_connect_attempt_total 109494
telemt_upstream_connect_success_total 109491
telemt_upstream_connect_attempts_per_request{bucket="1"} 109491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1054
telemt_me_reconnect_attempts_total 78513
telemt_me_reconnect_success_total 78254
telemt_me_reader_eof_total 73441
telemt_me_idle_close_by_peer_total 73436
telemt_me_route_drop_no_conn_total 40807
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 805
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 14
telemt_pool_force_close_total 854
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 73469
telemt_me_writer_restored_same_endpoint_total 78252
telemt_me_async_recovery_trigger_total 24761
telemt_user_connections_total{user="hello"} 104012
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1524495432 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 37006790420 (34.47 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 22283.2 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226791
telemt_connections_bad_total 1140
telemt_handshake_timeouts_total 3557
telemt_upstream_connect_attempt_total 85130
telemt_upstream_connect_success_total 84960
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 85017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 1900
telemt_me_reconnect_attempts_total 58078
telemt_me_reconnect_success_total 58020
telemt_me_reader_eof_total 60574
telemt_me_idle_close_by_peer_total 60569
telemt_me_route_drop_no_conn_total 86262
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1033
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 773
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 60738
telemt_me_writer_restored_same_endpoint_total 58013
telemt_me_async_recovery_trigger_total 74097
telemt_me_writer_removed_unexpected_minus_restored_total 2725
telemt_user_connections_total{user="hello"} 211350
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 18201657320 (16.95 GB)
telemt_user_octets_to_client{user="hello"} 61267516756 (57.06 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 22283.5 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227255
telemt_connections_bad_total 61709
telemt_handshake_timeouts_total 16320
telemt_upstream_connect_attempt_total 38791
telemt_upstream_connect_success_total 38707
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 38743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 764
telemt_me_reconnect_attempts_total 12126
telemt_me_reconnect_success_total 12102
telemt_me_reader_eof_total 16425
telemt_me_idle_close_by_peer_total 16423
telemt_me_route_drop_no_conn_total 61404
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 467
telemt_me_writer_removed_unexpected_total 16430
telemt_me_writer_restored_same_endpoint_total 12097
telemt_me_writer_removed_unexpected_minus_restored_total 4333
telemt_user_connections_total{user="hello"} 145291
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1705410796 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 47978513948 (44.68 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 22282.0 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198305
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 2133
telemt_upstream_connect_attempt_total 35678
telemt_upstream_connect_success_total 35531
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 35550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1039
telemt_me_reconnect_attempts_total 10236
telemt_me_reconnect_success_total 10204
telemt_me_reader_eof_total 13892
telemt_me_idle_close_by_peer_total 13890
telemt_me_route_drop_no_conn_total 66750
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 13
telemt_pool_force_close_total 413
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 13959
telemt_me_writer_restored_same_endpoint_total 10200
telemt_me_writer_removed_unexpected_minus_restored_total 3759
telemt_user_connections_total{user="hello"} 181940
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 10106591200 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 63717184960 (59.34 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```