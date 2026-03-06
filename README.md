# Server Metrics 2026-03-06 19:52:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 6248.4 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148806
telemt_connections_bad_total 1495
telemt_handshake_timeouts_total 5642
telemt_upstream_connect_attempt_total 9651
telemt_upstream_connect_success_total 9559
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 3137
telemt_me_reconnect_success_total 3122
telemt_me_reader_eof_total 4074
telemt_me_idle_close_by_peer_total 4074
telemt_me_route_drop_no_conn_total 60202
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 574
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 150
telemt_me_writer_removed_unexpected_total 4098
telemt_me_writer_restored_same_endpoint_total 3116
telemt_me_writer_removed_unexpected_minus_restored_total 982
telemt_user_connections_total{user="hello"} 129945
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 2103896496 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 44029933488 (41.01 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 6248.4 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54517
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 2405
telemt_upstream_connect_attempt_total 11358
telemt_upstream_connect_success_total 11356
telemt_upstream_connect_attempts_per_request{bucket="1"} 11356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 3989
telemt_me_reconnect_success_total 3983
telemt_me_reader_eof_total 5285
telemt_me_idle_close_by_peer_total 5283
telemt_me_route_drop_no_conn_total 19605
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 226
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 5285
telemt_me_writer_restored_same_endpoint_total 3981
telemt_me_writer_removed_unexpected_minus_restored_total 1304
telemt_user_connections_total{user="hello"} 48104
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 965953348 (921.20 MB)
telemt_user_octets_to_client{user="hello"} 14178065528 (13.20 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 6248.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100127
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1150
telemt_upstream_connect_attempt_total 7977
telemt_upstream_connect_success_total 7919
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 512
telemt_me_reconnect_attempts_total 1702
telemt_me_reconnect_success_total 1691
telemt_me_reader_eof_total 2281
telemt_me_idle_close_by_peer_total 2281
telemt_me_route_drop_no_conn_total 31379
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 474
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2337
telemt_me_writer_restored_same_endpoint_total 1684
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 93516
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 4394793764 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 26504319144 (24.68 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 6248.8 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118184
telemt_connections_bad_total 43567
telemt_handshake_timeouts_total 7088
telemt_upstream_connect_attempt_total 8752
telemt_upstream_connect_success_total 8719
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 2624
telemt_me_reconnect_success_total 2615
telemt_me_reader_eof_total 3341
telemt_me_idle_close_by_peer_total 3341
telemt_me_route_drop_no_conn_total 22613
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 431
telemt_me_writer_removed_unexpected_total 3343
telemt_me_writer_restored_same_endpoint_total 2611
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 65275
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 889581040 (848.37 MB)
telemt_user_octets_to_client{user="hello"} 22273398216 (20.74 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 6247.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89728
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 475
telemt_upstream_connect_attempt_total 9061
telemt_upstream_connect_success_total 9011
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 9023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 418
telemt_me_reconnect_attempts_total 2727
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 3711
telemt_me_idle_close_by_peer_total 3710
telemt_me_route_drop_no_conn_total 33776
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 483
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 2
telemt_pool_force_close_total 106
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3747
telemt_me_writer_restored_same_endpoint_total 2714
telemt_me_writer_removed_unexpected_minus_restored_total 1033
telemt_user_connections_total{user="hello"} 85144
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 8414410732 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 31372902320 (29.22 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 56
```