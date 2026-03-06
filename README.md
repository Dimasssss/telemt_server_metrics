# Server Metrics 2026-03-06 22:21:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 15203.0 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252484
telemt_connections_bad_total 2242
telemt_handshake_timeouts_total 9099
telemt_upstream_connect_attempt_total 24184
telemt_upstream_connect_success_total 23996
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 24066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1062
telemt_me_reconnect_attempts_total 7268
telemt_me_reconnect_success_total 7229
telemt_me_reader_eof_total 9487
telemt_me_idle_close_by_peer_total 9487
telemt_me_route_drop_no_conn_total 96373
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 821
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 166
telemt_me_writer_removed_unexpected_total 9595
telemt_me_writer_restored_same_endpoint_total 7223
telemt_me_writer_removed_unexpected_minus_restored_total 2372
telemt_user_connections_total{user="hello"} 227382
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 3384812412 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 90125063160 (83.94 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 15202.9 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101561
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 8319
telemt_upstream_connect_attempt_total 30210
telemt_upstream_connect_success_total 30209
telemt_upstream_connect_attempts_per_request{bucket="1"} 30209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 498
telemt_me_reconnect_attempts_total 10552
telemt_me_reconnect_success_total 10539
telemt_me_reader_eof_total 14807
telemt_me_idle_close_by_peer_total 14804
telemt_me_route_drop_no_conn_total 36699
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 649
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 300
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 14807
telemt_me_writer_restored_same_endpoint_total 10537
telemt_me_writer_removed_unexpected_minus_restored_total 4270
telemt_user_connections_total{user="hello"} 87696
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 1333250160 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 28426311612 (26.47 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 15202.7 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195259
telemt_connections_bad_total 830
telemt_handshake_timeouts_total 3217
telemt_upstream_connect_attempt_total 23907
telemt_upstream_connect_success_total 23758
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 23801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1066
telemt_me_reconnect_attempts_total 6931
telemt_me_reconnect_success_total 6900
telemt_me_reader_eof_total 9237
telemt_me_idle_close_by_peer_total 9234
telemt_me_route_drop_no_conn_total 73732
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 875
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 9342
telemt_me_writer_restored_same_endpoint_total 6893
telemt_me_writer_removed_unexpected_minus_restored_total 2449
telemt_user_connections_total{user="hello"} 180826
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 12345776840 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 54789464352 (51.03 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 15203.2 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194459
telemt_connections_bad_total 53646
telemt_handshake_timeouts_total 15131
telemt_upstream_connect_attempt_total 25755
telemt_upstream_connect_success_total 25684
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 25708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 8429
telemt_me_reconnect_success_total 8412
telemt_me_reader_eof_total 11290
telemt_me_idle_close_by_peer_total 11289
telemt_me_route_drop_no_conn_total 49595
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 164
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 11295
telemt_me_writer_restored_same_endpoint_total 8407
telemt_me_writer_removed_unexpected_minus_restored_total 2888
telemt_user_connections_total{user="hello"} 122327
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1599149172 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 37772360268 (35.18 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 15201.8 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167059
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1219
telemt_upstream_connect_attempt_total 23300
telemt_upstream_connect_success_total 23170
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 23189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 802
telemt_me_reconnect_attempts_total 6987
telemt_me_reconnect_success_total 6958
telemt_me_reader_eof_total 9419
telemt_me_idle_close_by_peer_total 9418
telemt_me_route_drop_no_conn_total 58571
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 730
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 7
telemt_pool_force_close_total 295
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9482
telemt_me_writer_restored_same_endpoint_total 6956
telemt_me_writer_removed_unexpected_minus_restored_total 2526
telemt_user_connections_total{user="hello"} 152959
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 9446622436 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 51695287476 (48.14 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 27
```