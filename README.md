# Server Metrics 2026-03-07 00:24:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 22591.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295005
telemt_connections_bad_total 3012
telemt_handshake_timeouts_total 9354
telemt_upstream_connect_attempt_total 60048
telemt_upstream_connect_success_total 58452
telemt_upstream_connect_fail_total 1459
telemt_upstream_connect_attempts_per_request{bucket="1"} 59911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1459
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 32808
telemt_me_reconnect_success_total 31405
telemt_me_reader_eof_total 33953
telemt_me_idle_close_by_peer_total 33953
telemt_me_route_drop_no_conn_total 114031
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 185
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
telemt_me_writer_removed_unexpected_total 34066
telemt_me_writer_restored_same_endpoint_total 31315
telemt_me_writer_restored_fallback_total 84
telemt_me_async_recovery_trigger_total 25995
telemt_me_writer_removed_unexpected_minus_restored_total 2667
telemt_user_connections_total{user="hello"} 267862
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 4173396324 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 119121370396 (110.94 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 22591.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125107
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 14337
telemt_upstream_connect_attempt_total 114472
telemt_upstream_connect_success_total 114468
telemt_upstream_connect_attempts_per_request{bucket="1"} 114468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1073
telemt_me_reconnect_attempts_total 82979
telemt_me_reconnect_success_total 82718
telemt_me_reader_eof_total 77473
telemt_me_idle_close_by_peer_total 77468
telemt_me_route_drop_no_conn_total 40928
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 15
telemt_pool_force_close_total 854
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 77501
telemt_me_writer_restored_same_endpoint_total 82716
telemt_me_async_recovery_trigger_total 25988
telemt_user_connections_total{user="hello"} 104506
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1529222216 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 37104373380 (34.56 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 22591.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228001
telemt_connections_bad_total 1141
telemt_handshake_timeouts_total 3557
telemt_upstream_connect_attempt_total 88690
telemt_upstream_connect_success_total 88520
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 88578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1932
telemt_me_reconnect_attempts_total 61150
telemt_me_reconnect_success_total 61091
telemt_me_reader_eof_total 63832
telemt_me_idle_close_by_peer_total 63827
telemt_me_route_drop_no_conn_total 86651
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 186
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1035
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 63998
telemt_me_writer_restored_same_endpoint_total 61084
telemt_me_async_recovery_trigger_total 77775
telemt_me_writer_removed_unexpected_minus_restored_total 2914
telemt_user_connections_total{user="hello"} 212556
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 18471305080 (17.20 GB)
telemt_user_octets_to_client{user="hello"} 61617649980 (57.39 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 22592.1 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229156
telemt_connections_bad_total 62699
telemt_handshake_timeouts_total 16578
telemt_upstream_connect_attempt_total 39622
telemt_upstream_connect_success_total 39538
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 39574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 780
telemt_me_reconnect_attempts_total 12460
telemt_me_reconnect_success_total 12436
telemt_me_reader_eof_total 16898
telemt_me_idle_close_by_peer_total 16896
telemt_me_route_drop_no_conn_total 61664
telemt_me_single_endpoint_shadow_rotate_total 192
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
telemt_me_writer_removed_unexpected_total 16903
telemt_me_writer_restored_same_endpoint_total 12431
telemt_me_writer_removed_unexpected_minus_restored_total 4472
telemt_user_connections_total{user="hello"} 145971
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1709210676 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 48144245516 (44.84 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 22590.5 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199368
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 2167
telemt_upstream_connect_attempt_total 36362
telemt_upstream_connect_success_total 36214
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 36233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1053
telemt_me_reconnect_attempts_total 10444
telemt_me_reconnect_success_total 10411
telemt_me_reader_eof_total 14154
telemt_me_idle_close_by_peer_total 14152
telemt_me_route_drop_no_conn_total 66956
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 764
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 13
telemt_pool_force_close_total 413
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 14221
telemt_me_writer_restored_same_endpoint_total 10407
telemt_me_writer_removed_unexpected_minus_restored_total 3814
telemt_user_connections_total{user="hello"} 182944
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 10115373472 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 64299216212 (59.88 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```