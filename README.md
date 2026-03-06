# Server Metrics 2026-03-06 21:09:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 10886.3 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219163
telemt_connections_bad_total 2206
telemt_handshake_timeouts_total 8687
telemt_upstream_connect_attempt_total 16827
telemt_upstream_connect_success_total 16675
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 16732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 933
telemt_me_reconnect_attempts_total 5142
telemt_me_reconnect_success_total 5112
telemt_me_reader_eof_total 6611
telemt_me_idle_close_by_peer_total 6611
telemt_me_route_drop_no_conn_total 84941
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 744
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 4
telemt_pool_force_close_total 256
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6718
telemt_me_writer_restored_same_endpoint_total 5106
telemt_me_writer_removed_unexpected_minus_restored_total 1612
telemt_user_connections_total{user="hello"} 195030
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 2936043860 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 69893839540 (65.09 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 10886.3 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82988
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 4875
telemt_upstream_connect_attempt_total 20584
telemt_upstream_connect_success_total 20583
telemt_upstream_connect_attempts_per_request{bucket="1"} 20583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 7210
telemt_me_reconnect_success_total 7201
telemt_me_reader_eof_total 10106
telemt_me_idle_close_by_peer_total 10104
telemt_me_route_drop_no_conn_total 29658
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 457
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 334
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 5
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 10106
telemt_me_writer_restored_same_endpoint_total 7199
telemt_me_writer_removed_unexpected_minus_restored_total 2907
telemt_user_connections_total{user="hello"} 73069
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 1198566696 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 24920969272 (23.21 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 10886.2 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159761
telemt_connections_bad_total 377
telemt_handshake_timeouts_total 2015
telemt_upstream_connect_attempt_total 16229
telemt_upstream_connect_success_total 16101
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 928
telemt_me_reconnect_attempts_total 4462
telemt_me_reconnect_success_total 4437
telemt_me_reader_eof_total 6007
telemt_me_idle_close_by_peer_total 6004
telemt_me_route_drop_no_conn_total 64353
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 745
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 6108
telemt_me_writer_restored_same_endpoint_total 4430
telemt_me_writer_removed_unexpected_minus_restored_total 1678
telemt_user_connections_total{user="hello"} 147827
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 8249802568 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 42330850052 (39.42 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 10886.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166522
telemt_connections_bad_total 49634
telemt_handshake_timeouts_total 12964
telemt_upstream_connect_attempt_total 16631
telemt_upstream_connect_success_total 16589
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 16607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 5059
telemt_me_reconnect_success_total 5047
telemt_me_reader_eof_total 6482
telemt_me_idle_close_by_peer_total 6482
telemt_me_route_drop_no_conn_total 41389
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 143
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 6487
telemt_me_writer_restored_same_endpoint_total 5042
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 100929
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 1344641272 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 31617680428 (29.45 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 10885.2 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135334
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 15934
telemt_upstream_connect_success_total 15829
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 15845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 653
telemt_me_reconnect_attempts_total 4636
telemt_me_reconnect_success_total 4615
telemt_me_reader_eof_total 6300
telemt_me_idle_close_by_peer_total 6299
telemt_me_route_drop_no_conn_total 48820
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 653
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 6359
telemt_me_writer_restored_same_endpoint_total 4613
telemt_me_writer_removed_unexpected_minus_restored_total 1746
telemt_user_connections_total{user="hello"} 127165
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 9124002236 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 43205080948 (40.24 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```