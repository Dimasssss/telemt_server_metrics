# Server Metrics 2026-03-06 20:23:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 8099.7 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181455
telemt_connections_bad_total 1919
telemt_handshake_timeouts_total 7671
telemt_upstream_connect_attempt_total 11701
telemt_upstream_connect_success_total 11592
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 11634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 339
telemt_me_reconnect_attempts_total 3463
telemt_me_reconnect_success_total 3446
telemt_me_reader_eof_total 4483
telemt_me_idle_close_by_peer_total 4483
telemt_me_route_drop_no_conn_total 71016
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 621
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4507
telemt_me_writer_restored_same_endpoint_total 3440
telemt_me_writer_removed_unexpected_minus_restored_total 1067
telemt_user_connections_total{user="hello"} 159181
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 2530718120 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 57930759192 (53.95 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 8099.5 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65945
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 2772
telemt_upstream_connect_attempt_total 16822
telemt_upstream_connect_success_total 16821
telemt_upstream_connect_attempts_per_request{bucket="1"} 16821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 6376
telemt_me_reconnect_success_total 6369
telemt_me_reader_eof_total 9033
telemt_me_idle_close_by_peer_total 9031
telemt_me_route_drop_no_conn_total 24227
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 277
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 188
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 9033
telemt_me_writer_restored_same_endpoint_total 6367
telemt_me_writer_removed_unexpected_minus_restored_total 2666
telemt_user_connections_total{user="hello"} 58707
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 1078787868 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 20289856368 (18.90 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 8099.5 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129673
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 10816
telemt_upstream_connect_success_total 10757
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 2531
telemt_me_reconnect_success_total 2519
telemt_me_reader_eof_total 3304
telemt_me_idle_close_by_peer_total 3302
telemt_me_route_drop_no_conn_total 52671
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 626
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 3360
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_removed_unexpected_minus_restored_total 848
telemt_user_connections_total{user="hello"} 119071
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 6034259032 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 33544888092 (31.24 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 8099.8 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140098
telemt_connections_bad_total 47151
telemt_handshake_timeouts_total 9855
telemt_upstream_connect_attempt_total 11464
telemt_upstream_connect_success_total 11431
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 11446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 3453
telemt_me_reconnect_success_total 3443
telemt_me_reader_eof_total 4412
telemt_me_idle_close_by_peer_total 4412
telemt_me_route_drop_no_conn_total 30388
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 86
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 4
telemt_pool_force_close_total 155
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4414
telemt_me_writer_restored_same_endpoint_total 3439
telemt_me_writer_removed_unexpected_minus_restored_total 975
telemt_user_connections_total{user="hello"} 80568
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 1081897824 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 26741831708 (24.91 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 8098.4 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109981
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 677
telemt_upstream_connect_attempt_total 11982
telemt_upstream_connect_success_total 11926
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 11938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 463
telemt_me_reconnect_attempts_total 3471
telemt_me_reconnect_success_total 3459
telemt_me_reader_eof_total 4688
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 40700
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 529
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 4724
telemt_me_writer_restored_same_endpoint_total 3457
telemt_me_writer_removed_unexpected_minus_restored_total 1267
telemt_user_connections_total{user="hello"} 104251
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 8677516840 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 36977114660 (34.44 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 55
```