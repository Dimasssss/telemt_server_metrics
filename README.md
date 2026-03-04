# Server Metrics 2026-03-04 06:14:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 32632.1 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273424
telemt_connections_bad_total 2997
telemt_handshake_timeouts_total 5000
telemt_upstream_connect_attempt_total 21853
telemt_upstream_connect_success_total 21752
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 21752
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4635
telemt_me_reconnect_success_total 4611
telemt_me_reader_eof_total 4719
telemt_me_idle_close_by_peer_total 4719
telemt_me_route_drop_no_conn_total 101924
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 687
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4719
telemt_me_writer_restored_same_endpoint_total 4591
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 254968
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 2741043276 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 81571695600 (75.97 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 32628.8 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140092
telemt_connections_bad_total 554
telemt_handshake_timeouts_total 22126
telemt_upstream_connect_attempt_total 71341
telemt_upstream_connect_success_total 70476
telemt_upstream_connect_fail_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 70470
telemt_upstream_connect_attempts_per_request{bucket="2"} 422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 416
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 42635
telemt_me_reconnect_success_total 42605
telemt_me_reader_eof_total 43674
telemt_me_idle_close_by_peer_total 43673
telemt_me_route_drop_no_conn_total 44257
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 34
telemt_me_writer_removed_unexpected_total 43735
telemt_me_writer_restored_same_endpoint_total 42584
telemt_me_writer_removed_unexpected_minus_restored_total 1151
telemt_user_connections_total{user="hello"} 91319
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 866629208 (826.48 MB)
telemt_user_octets_to_client{user="hello"} 37559315452 (34.98 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 32627.8 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273574
telemt_connections_bad_total 93134
telemt_handshake_timeouts_total 6505
telemt_upstream_connect_attempt_total 44659
telemt_upstream_connect_success_total 44378
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 44378
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 579
telemt_me_reconnect_attempts_total 18557
telemt_me_reconnect_success_total 18508
telemt_me_reader_eof_total 19527
telemt_me_idle_close_by_peer_total 19524
telemt_me_route_drop_no_conn_total 64716
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 415
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 19535
telemt_me_writer_restored_same_endpoint_total 18487
telemt_me_writer_removed_unexpected_minus_restored_total 1048
telemt_user_connections_total{user="hello"} 165899
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 1237721080 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 43804113920 (40.80 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 32626.6 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142246
telemt_connections_bad_total 11467
telemt_handshake_timeouts_total 3200
telemt_upstream_connect_attempt_total 26083
telemt_upstream_connect_success_total 25990
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 25990
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 5936
telemt_me_reconnect_success_total 5927
telemt_me_reader_eof_total 6040
telemt_me_idle_close_by_peer_total 6040
telemt_me_route_drop_no_conn_total 43031
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 9
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 6040
telemt_me_writer_restored_same_endpoint_total 5906
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 120117
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 1080292732 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 44460627576 (41.41 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 32640.1 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287554
telemt_connections_bad_total 6394
telemt_handshake_timeouts_total 126777
telemt_upstream_connect_attempt_total 46052
telemt_upstream_connect_success_total 45727
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 45727
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 630
telemt_me_reconnect_attempts_total 21596
telemt_me_reconnect_success_total 21584
telemt_me_reader_eof_total 22771
telemt_me_idle_close_by_peer_total 22770
telemt_me_route_drop_no_conn_total 67635
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22784
telemt_me_writer_restored_same_endpoint_total 21559
telemt_me_writer_removed_unexpected_minus_restored_total 1225
telemt_user_connections_total{user="hello"} 149509
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 2087768980 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 34748341524 (32.36 GB)
telemt_user_unique_ips_current{user="hello"} 28
```