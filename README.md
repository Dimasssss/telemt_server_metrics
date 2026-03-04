# Server Metrics 2026-03-04 05:13:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 28946.1 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210279
telemt_connections_bad_total 2303
telemt_handshake_timeouts_total 3949
telemt_upstream_connect_attempt_total 20285
telemt_upstream_connect_success_total 20192
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20192
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 4532
telemt_me_reconnect_success_total 4514
telemt_me_reader_eof_total 4619
telemt_me_idle_close_by_peer_total 4619
telemt_me_route_drop_no_conn_total 68024
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 552
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4619
telemt_me_writer_restored_same_endpoint_total 4494
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 198838
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 2084141084 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 66294360972 (61.74 GB)
telemt_user_unique_ips_current{user="hello"} 76
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 28942.6 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99813
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 21234
telemt_upstream_connect_attempt_total 65508
telemt_upstream_connect_success_total 64798
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 64792
telemt_upstream_connect_attempts_per_request{bucket="2"} 344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 988
telemt_me_reconnect_attempts_total 39779
telemt_me_reconnect_success_total 39751
telemt_me_reader_eof_total 40748
telemt_me_idle_close_by_peer_total 40747
telemt_me_route_drop_no_conn_total 31098
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40809
telemt_me_writer_restored_same_endpoint_total 39730
telemt_me_writer_removed_unexpected_minus_restored_total 1079
telemt_user_connections_total{user="hello"} 72579
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 650724152 (620.58 MB)
telemt_user_octets_to_client{user="hello"} 31134440380 (29.00 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 28941.5 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220951
telemt_connections_bad_total 81272
telemt_handshake_timeouts_total 4450
telemt_upstream_connect_attempt_total 37838
telemt_upstream_connect_success_total 37591
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 37591
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 496
telemt_me_reconnect_attempts_total 15179
telemt_me_reconnect_success_total 15138
telemt_me_reader_eof_total 15939
telemt_me_idle_close_by_peer_total 15936
telemt_me_route_drop_no_conn_total 45151
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 326
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 15947
telemt_me_writer_restored_same_endpoint_total 15117
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 130860
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 884544012 (843.57 MB)
telemt_user_octets_to_client{user="hello"} 33770601300 (31.45 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 28940.6 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111311
telemt_connections_bad_total 7386
telemt_handshake_timeouts_total 1353
telemt_upstream_connect_attempt_total 20315
telemt_upstream_connect_success_total 20227
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 20227
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 3400
telemt_me_reconnect_success_total 3398
telemt_me_reader_eof_total 3428
telemt_me_idle_close_by_peer_total 3428
telemt_me_route_drop_no_conn_total 35370
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3428
telemt_me_writer_restored_same_endpoint_total 3377
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 98040
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 817897084 (780.01 MB)
telemt_user_octets_to_client{user="hello"} 33736112384 (31.42 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 28938.9 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238315
telemt_connections_bad_total 5248
telemt_handshake_timeouts_total 106874
telemt_upstream_connect_attempt_total 42653
telemt_upstream_connect_success_total 42363
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42363
telemt_upstream_connect_attempts_per_request{bucket="2"} 135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 20529
telemt_me_reconnect_success_total 20519
telemt_me_reader_eof_total 21673
telemt_me_idle_close_by_peer_total 21672
telemt_me_route_drop_no_conn_total 55135
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 124
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 174
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 21685
telemt_me_writer_restored_same_endpoint_total 20495
telemt_me_writer_removed_unexpected_minus_restored_total 1190
telemt_user_connections_total{user="hello"} 122012
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 950214052 (906.19 MB)
telemt_user_octets_to_client{user="hello"} 28280082840 (26.34 GB)
telemt_user_unique_ips_current{user="hello"} 22
```