# Server Metrics 2026-03-04 23:05:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 7930.4 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81461
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 515
telemt_upstream_connect_attempt_total 8028
telemt_upstream_connect_success_total 7919
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7918
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 375
telemt_me_reconnect_attempts_total 2808
telemt_me_reconnect_success_total 2809
telemt_me_reader_eof_total 2880
telemt_me_idle_close_by_peer_total 2879
telemt_me_route_drop_no_conn_total 21572
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 2929
telemt_me_writer_restored_same_endpoint_total 2789
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 69105
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 2689495648 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 37712302880 (35.12 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 7925.0 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29024
telemt_connections_bad_total 706
telemt_handshake_timeouts_total 188
telemt_upstream_connect_attempt_total 9235
telemt_upstream_connect_success_total 9101
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 9098
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 518
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3696
telemt_me_reader_eof_total 3773
telemt_me_idle_close_by_peer_total 3772
telemt_me_route_drop_no_conn_total 9318
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 3827
telemt_me_writer_restored_same_endpoint_total 3677
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 27326
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 238832524 (227.77 MB)
telemt_user_octets_to_client{user="hello"} 7870347008 (7.33 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 7921.6 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66992
telemt_connections_bad_total 1045
telemt_handshake_timeouts_total 345
telemt_upstream_connect_attempt_total 3339
telemt_upstream_connect_success_total 3307
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3307
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 21374
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 151
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 61780
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 942464072 (898.80 MB)
telemt_user_octets_to_client{user="hello"} 24265119236 (22.60 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 39969.8 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528944
telemt_connections_bad_total 72423
telemt_handshake_timeouts_total 14695
telemt_upstream_connect_attempt_total 17096
telemt_upstream_connect_success_total 17096
telemt_upstream_connect_attempts_per_request{bucket="1"} 17096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 2188
telemt_me_reconnect_success_total 2172
telemt_me_reader_eof_total 2214
telemt_me_idle_close_by_peer_total 2214
telemt_me_route_drop_no_conn_total 180844
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 16
telemt_pool_force_close_total 469
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 413498
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 5738287248 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 155874635536 (145.17 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 40329.2 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524485
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5765
telemt_upstream_connect_attempt_total 25083
telemt_upstream_connect_success_total 24945
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 24945
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 5451
telemt_me_reconnect_success_total 5436
telemt_me_reader_eof_total 5639
telemt_me_idle_close_by_peer_total 5638
telemt_me_route_drop_no_conn_total 231416
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5642
telemt_me_writer_restored_same_endpoint_total 5415
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 474331
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 7299461468 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 156054830264 (145.34 GB)
telemt_user_unique_ips_current{user="hello"} 28
```