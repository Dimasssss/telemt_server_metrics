# Server Metrics 2026-03-04 23:00:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 7623.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79775
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 501
telemt_upstream_connect_attempt_total 7567
telemt_upstream_connect_success_total 7458
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7457
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 271
telemt_me_reconnect_attempts_total 2542
telemt_me_reconnect_success_total 2543
telemt_me_reader_eof_total 2609
telemt_me_idle_close_by_peer_total 2608
telemt_me_route_drop_no_conn_total 20548
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 2658
telemt_me_writer_restored_same_endpoint_total 2523
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 67465
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 2655913464 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 36831866260 (34.30 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 7618.0 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28179
telemt_connections_bad_total 701
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 8636
telemt_upstream_connect_success_total 8502
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8499
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 515
telemt_me_reconnect_attempts_total 3353
telemt_me_reconnect_success_total 3348
telemt_me_reader_eof_total 3422
telemt_me_idle_close_by_peer_total 3421
telemt_me_route_drop_no_conn_total 8990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 3476
telemt_me_writer_restored_same_endpoint_total 3329
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 26500
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 231456368 (220.73 MB)
telemt_user_octets_to_client{user="hello"} 7729194132 (7.20 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 7614.5 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64152
telemt_connections_bad_total 1045
telemt_handshake_timeouts_total 286
telemt_upstream_connect_attempt_total 3315
telemt_upstream_connect_success_total 3282
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3282
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 20927
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 148
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 59154
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 931351636 (888.21 MB)
telemt_user_octets_to_client{user="hello"} 23459876176 (21.85 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 39662.8 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527349
telemt_connections_bad_total 71899
telemt_handshake_timeouts_total 14688
telemt_upstream_connect_attempt_total 17015
telemt_upstream_connect_success_total 17015
telemt_upstream_connect_attempts_per_request{bucket="1"} 17015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 2187
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2213
telemt_me_idle_close_by_peer_total 2213
telemt_me_route_drop_no_conn_total 180627
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 699
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 15
telemt_pool_force_close_total 456
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2214
telemt_me_writer_restored_same_endpoint_total 2145
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 412435
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5732095580 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 155536266880 (144.85 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 40022.1 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523434
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5761
telemt_upstream_connect_attempt_total 24639
telemt_upstream_connect_success_total 24501
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 24501
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 5269
telemt_me_reconnect_success_total 5254
telemt_me_reader_eof_total 5452
telemt_me_idle_close_by_peer_total 5452
telemt_me_route_drop_no_conn_total 230990
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5455
telemt_me_writer_restored_same_endpoint_total 5233
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 473298
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 7288122228 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 155677929168 (144.99 GB)
telemt_user_unique_ips_current{user="hello"} 29
```