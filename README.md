# Server Metrics 2026-03-06 21:55:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 13664.3 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242285
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 9014
telemt_upstream_connect_attempt_total 21999
telemt_upstream_connect_success_total 21839
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 21899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1019
telemt_me_reconnect_attempts_total 6771
telemt_me_reconnect_success_total 6738
telemt_me_reader_eof_total 8833
telemt_me_idle_close_by_peer_total 8833
telemt_me_route_drop_no_conn_total 93252
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 809
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 5
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 155
telemt_me_writer_removed_unexpected_total 8940
telemt_me_writer_restored_same_endpoint_total 6732
telemt_me_writer_removed_unexpected_minus_restored_total 2208
telemt_user_connections_total{user="hello"} 217504
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 3283574796 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 84022410780 (78.25 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 13664.3 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95202
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 7095
telemt_upstream_connect_attempt_total 25612
telemt_upstream_connect_success_total 25610
telemt_upstream_connect_attempts_per_request{bucket="1"} 25610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 8559
telemt_me_reconnect_success_total 8547
telemt_me_reader_eof_total 11994
telemt_me_idle_close_by_peer_total 11992
telemt_me_route_drop_no_conn_total 34663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 615
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 11994
telemt_me_writer_restored_same_endpoint_total 8545
telemt_me_writer_removed_unexpected_minus_restored_total 3449
telemt_user_connections_total{user="hello"} 82716
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 1311151844 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 26675851692 (24.84 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 13664.1 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184220
telemt_connections_bad_total 577
telemt_handshake_timeouts_total 2959
telemt_upstream_connect_attempt_total 21265
telemt_upstream_connect_success_total 21122
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 999
telemt_me_reconnect_attempts_total 6141
telemt_me_reconnect_success_total 6114
telemt_me_reader_eof_total 8153
telemt_me_idle_close_by_peer_total 8150
telemt_me_route_drop_no_conn_total 71165
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 844
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 7
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 8254
telemt_me_writer_restored_same_endpoint_total 6107
telemt_me_writer_removed_unexpected_minus_restored_total 2147
telemt_user_connections_total{user="hello"} 170394
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 10761819324 (10.02 GB)
telemt_user_octets_to_client{user="hello"} 51321039112 (47.80 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 13664.4 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185829
telemt_connections_bad_total 52258
telemt_handshake_timeouts_total 14292
telemt_upstream_connect_attempt_total 21637
telemt_upstream_connect_success_total 21571
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 21593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 416
telemt_me_reconnect_attempts_total 6626
telemt_me_reconnect_success_total 6611
telemt_me_reader_eof_total 8690
telemt_me_idle_close_by_peer_total 8690
telemt_me_route_drop_no_conn_total 47093
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 157
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8695
telemt_me_writer_restored_same_endpoint_total 6606
telemt_me_writer_removed_unexpected_minus_restored_total 2089
telemt_user_connections_total{user="hello"} 116063
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 1568463944 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 36073001232 (33.60 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 13662.8 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156949
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 20647
telemt_upstream_connect_success_total 20524
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 754
telemt_me_reconnect_attempts_total 6342
telemt_me_reconnect_success_total 6315
telemt_me_reader_eof_total 8589
telemt_me_idle_close_by_peer_total 8588
telemt_me_route_drop_no_conn_total 55509
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 728
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 6
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8651
telemt_me_writer_restored_same_endpoint_total 6313
telemt_me_writer_removed_unexpected_minus_restored_total 2338
telemt_user_connections_total{user="hello"} 144617
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 9234674036 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 49301737056 (45.92 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```