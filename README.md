# Server Metrics 2026-03-04 04:57:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 28024.6 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196994
telemt_connections_bad_total 1636
telemt_handshake_timeouts_total 3726
telemt_upstream_connect_attempt_total 19888
telemt_upstream_connect_success_total 19798
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 19798
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 4520
telemt_me_reconnect_success_total 4502
telemt_me_reader_eof_total 4607
telemt_me_idle_close_by_peer_total 4607
telemt_me_route_drop_no_conn_total 64183
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 529
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4607
telemt_me_writer_restored_same_endpoint_total 4482
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 186836
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 1996957892 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 59979063576 (55.86 GB)
telemt_user_unique_ips_current{user="hello"} 82
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 28021.1 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94398
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20782
telemt_upstream_connect_attempt_total 64102
telemt_upstream_connect_success_total 63435
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 63429
telemt_upstream_connect_attempts_per_request{bucket="2"} 323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 981
telemt_me_reconnect_attempts_total 39241
telemt_me_reconnect_success_total 39213
telemt_me_reader_eof_total 40204
telemt_me_idle_close_by_peer_total 40203
telemt_me_route_drop_no_conn_total 29053
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40265
telemt_me_writer_restored_same_endpoint_total 39192
telemt_me_writer_removed_unexpected_minus_restored_total 1073
telemt_user_connections_total{user="hello"} 67761
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 617833664 (589.21 MB)
telemt_user_octets_to_client{user="hello"} 29658026744 (27.62 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 28020.0 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208815
telemt_connections_bad_total 76603
telemt_handshake_timeouts_total 4388
telemt_upstream_connect_attempt_total 36435
telemt_upstream_connect_success_total 36192
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 36192
telemt_upstream_connect_attempts_per_request{bucket="2"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 14599
telemt_me_reconnect_success_total 14561
telemt_me_reader_eof_total 15325
telemt_me_idle_close_by_peer_total 15322
telemt_me_route_drop_no_conn_total 41723
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 317
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 15333
telemt_me_writer_restored_same_endpoint_total 14540
telemt_me_writer_removed_unexpected_minus_restored_total 793
telemt_user_connections_total{user="hello"} 123599
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 793550768 (756.79 MB)
telemt_user_octets_to_client{user="hello"} 31862701096 (29.67 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 28018.8 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104442
telemt_connections_bad_total 5958
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 19199
telemt_upstream_connect_success_total 19116
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 19116
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 3032
telemt_me_reconnect_success_total 3031
telemt_me_reader_eof_total 3055
telemt_me_idle_close_by_peer_total 3055
telemt_me_route_drop_no_conn_total 33591
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3055
telemt_me_writer_restored_same_endpoint_total 3010
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 92844
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 771339892 (735.61 MB)
telemt_user_octets_to_client{user="hello"} 31464625500 (29.30 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 28017.4 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227416
telemt_connections_bad_total 5036
telemt_handshake_timeouts_total 102761
telemt_upstream_connect_attempt_total 41147
telemt_upstream_connect_success_total 40863
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 40863
telemt_upstream_connect_attempts_per_request{bucket="2"} 132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 19896
telemt_me_reconnect_success_total 19887
telemt_me_reader_eof_total 21026
telemt_me_idle_close_by_peer_total 21025
telemt_me_route_drop_no_conn_total 53024
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 158
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 21038
telemt_me_writer_restored_same_endpoint_total 19863
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 115651
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 803800024 (766.56 MB)
telemt_user_octets_to_client{user="hello"} 27090333740 (25.23 GB)
telemt_user_unique_ips_current{user="hello"} 26
```