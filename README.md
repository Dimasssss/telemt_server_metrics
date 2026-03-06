# Server Metrics 2026-03-06 20:17:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 7791.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177128
telemt_connections_bad_total 1850
telemt_handshake_timeouts_total 7376
telemt_upstream_connect_attempt_total 11254
telemt_upstream_connect_success_total 11144
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 11186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 3378
telemt_me_reconnect_success_total 3362
telemt_me_reader_eof_total 4385
telemt_me_idle_close_by_peer_total 4385
telemt_me_route_drop_no_conn_total 69371
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 620
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4409
telemt_me_writer_restored_same_endpoint_total 3356
telemt_me_writer_removed_unexpected_minus_restored_total 1053
telemt_user_connections_total{user="hello"} 155270
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 2480991316 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 55971409620 (52.13 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 7790.9 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63930
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 2541
telemt_upstream_connect_attempt_total 15900
telemt_upstream_connect_success_total 15899
telemt_upstream_connect_attempts_per_request{bucket="1"} 15899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 5965
telemt_me_reconnect_success_total 5959
telemt_me_reader_eof_total 8407
telemt_me_idle_close_by_peer_total 8405
telemt_me_route_drop_no_conn_total 23337
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 275
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 8407
telemt_me_writer_restored_same_endpoint_total 5957
telemt_me_writer_removed_unexpected_minus_restored_total 2450
telemt_user_connections_total{user="hello"} 56972
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 1068324664 (1018.83 MB)
telemt_user_octets_to_client{user="hello"} 19521823736 (18.18 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 7790.9 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125797
telemt_connections_bad_total 343
telemt_handshake_timeouts_total 1292
telemt_upstream_connect_attempt_total 10068
telemt_upstream_connect_success_total 10009
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 2219
telemt_me_reader_eof_total 2902
telemt_me_idle_close_by_peer_total 2900
telemt_me_route_drop_no_conn_total 50737
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 603
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2958
telemt_me_writer_restored_same_endpoint_total 2212
telemt_me_writer_removed_unexpected_minus_restored_total 746
telemt_user_connections_total{user="hello"} 115310
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 5761247316 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 31745867484 (29.57 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 7791.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136696
telemt_connections_bad_total 46873
telemt_handshake_timeouts_total 9393
telemt_upstream_connect_attempt_total 11209
telemt_upstream_connect_success_total 11176
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 11191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 3434
telemt_me_reconnect_success_total 3424
telemt_me_reader_eof_total 4391
telemt_me_idle_close_by_peer_total 4391
telemt_me_route_drop_no_conn_total 28247
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 59
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 4
telemt_pool_force_close_total 155
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4393
telemt_me_writer_restored_same_endpoint_total 3420
telemt_me_writer_removed_unexpected_minus_restored_total 973
telemt_user_connections_total{user="hello"} 77936
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 1061091700 (1011.94 MB)
telemt_user_octets_to_client{user="hello"} 25761039316 (23.99 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 7789.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106732
telemt_connections_bad_total 449
telemt_handshake_timeouts_total 643
telemt_upstream_connect_attempt_total 11243
telemt_upstream_connect_success_total 11186
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 11198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 453
telemt_me_reconnect_attempts_total 3179
telemt_me_reconnect_success_total 3167
telemt_me_reader_eof_total 4262
telemt_me_idle_close_by_peer_total 4261
telemt_me_route_drop_no_conn_total 38825
telemt_me_route_drop_channel_closed_total 3
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
telemt_me_writer_removed_unexpected_total 4298
telemt_me_writer_restored_same_endpoint_total 3165
telemt_me_writer_removed_unexpected_minus_restored_total 1133
telemt_user_connections_total{user="hello"} 101135
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 8650660920 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 35925485800 (33.46 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 52
```