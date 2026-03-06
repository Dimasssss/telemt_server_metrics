# Server Metrics 2026-03-06 21:40:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 12738.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235735
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 8965
telemt_upstream_connect_attempt_total 19674
telemt_upstream_connect_success_total 19515
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 19575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 979
telemt_me_reconnect_attempts_total 5847
telemt_me_reconnect_success_total 5815
telemt_me_reader_eof_total 7541
telemt_me_idle_close_by_peer_total 7541
telemt_me_route_drop_no_conn_total 90181
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 796
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 7648
telemt_me_writer_restored_same_endpoint_total 5809
telemt_me_writer_removed_unexpected_minus_restored_total 1839
telemt_user_connections_total{user="hello"} 211136
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 3143540444 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 80016987608 (74.52 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 12738.6 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91549
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 6359
telemt_upstream_connect_attempt_total 23111
telemt_upstream_connect_success_total 23109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 7588
telemt_me_reconnect_success_total 7577
telemt_me_reader_eof_total 10576
telemt_me_idle_close_by_peer_total 10574
telemt_me_route_drop_no_conn_total 33308
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 566
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10576
telemt_me_writer_restored_same_endpoint_total 7575
telemt_me_writer_removed_unexpected_minus_restored_total 3001
telemt_user_connections_total{user="hello"} 79933
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 1272188476 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 26179148676 (24.38 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 12738.6 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176517
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 2769
telemt_upstream_connect_attempt_total 19449
telemt_upstream_connect_success_total 19311
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 19349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5449
telemt_me_reconnect_success_total 5423
telemt_me_reader_eof_total 7239
telemt_me_idle_close_by_peer_total 7236
telemt_me_route_drop_no_conn_total 69212
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 802
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 6
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7340
telemt_me_writer_restored_same_endpoint_total 5416
telemt_me_writer_removed_unexpected_minus_restored_total 1924
telemt_user_connections_total{user="hello"} 163279
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 9772286872 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 46517781800 (43.32 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 12738.9 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180234
telemt_connections_bad_total 51430
telemt_handshake_timeouts_total 13849
telemt_upstream_connect_attempt_total 20349
telemt_upstream_connect_success_total 20302
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 401
telemt_me_reconnect_attempts_total 6388
telemt_me_reconnect_success_total 6374
telemt_me_reader_eof_total 8328
telemt_me_idle_close_by_peer_total 8328
telemt_me_route_drop_no_conn_total 45049
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 7
telemt_pool_force_close_total 247
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8333
telemt_me_writer_restored_same_endpoint_total 6369
telemt_me_writer_removed_unexpected_minus_restored_total 1964
telemt_user_connections_total{user="hello"} 111797
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 1553259312 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 35440974072 (33.01 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 12737.4 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150301
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 20082
telemt_upstream_connect_success_total 19960
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 730
telemt_me_reconnect_attempts_total 6323
telemt_me_reconnect_success_total 6297
telemt_me_reader_eof_total 8569
telemt_me_idle_close_by_peer_total 8568
telemt_me_route_drop_no_conn_total 52294
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 712
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 6
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8631
telemt_me_writer_restored_same_endpoint_total 6295
telemt_me_writer_removed_unexpected_minus_restored_total 2336
telemt_user_connections_total{user="hello"} 138767
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 9206511016 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 47594317632 (44.33 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```