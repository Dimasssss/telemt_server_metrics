# Server Metrics 2026-03-07 00:29:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 22899.0 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297046
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 9375
telemt_upstream_connect_attempt_total 62027
telemt_upstream_connect_success_total 60391
telemt_upstream_connect_fail_total 1500
telemt_upstream_connect_attempts_per_request{bucket="1"} 61891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1500
telemt_me_keepalive_timeout_total 1563
telemt_me_reconnect_attempts_total 34327
telemt_me_reconnect_success_total 32883
telemt_me_reader_eof_total 35457
telemt_me_idle_close_by_peer_total 35457
telemt_me_route_drop_no_conn_total 114751
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 998
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 9
telemt_pool_force_close_total 474
telemt_pool_stale_pick_total 186
telemt_me_writer_removed_unexpected_total 35570
telemt_me_writer_restored_same_endpoint_total 32790
telemt_me_writer_restored_fallback_total 87
telemt_me_async_recovery_trigger_total 27216
telemt_me_writer_removed_unexpected_minus_restored_total 2693
telemt_user_connections_total{user="hello"} 269834
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 4194048356 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 119407566396 (111.21 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 22899.0 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126259
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 14587
telemt_upstream_connect_attempt_total 118028
telemt_upstream_connect_success_total 118026
telemt_upstream_connect_attempts_per_request{bucket="1"} 118026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1093
telemt_me_reconnect_attempts_total 86105
telemt_me_reconnect_success_total 85844
telemt_me_reader_eof_total 79454
telemt_me_idle_close_by_peer_total 79449
telemt_me_route_drop_no_conn_total 41194
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 15
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 79483
telemt_me_writer_restored_same_endpoint_total 85842
telemt_me_async_recovery_trigger_total 27209
telemt_user_connections_total{user="hello"} 105401
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 1535710484 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 37198169412 (34.64 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 22898.8 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229701
telemt_connections_bad_total 1163
telemt_handshake_timeouts_total 3566
telemt_upstream_connect_attempt_total 91842
telemt_upstream_connect_success_total 91673
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 91731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1976
telemt_me_reconnect_attempts_total 63993
telemt_me_reconnect_success_total 63934
telemt_me_reader_eof_total 65915
telemt_me_idle_close_by_peer_total 65910
telemt_me_route_drop_no_conn_total 87094
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1037
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 12
telemt_pool_force_close_total 350
telemt_pool_stale_pick_total 123
telemt_me_writer_removed_unexpected_total 66081
telemt_me_writer_restored_same_endpoint_total 63927
telemt_me_async_recovery_trigger_total 81434
telemt_me_writer_removed_unexpected_minus_restored_total 2154
telemt_user_connections_total{user="hello"} 214222
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 18740562064 (17.45 GB)
telemt_user_octets_to_client{user="hello"} 61771588932 (57.53 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 22899.2 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231058
telemt_connections_bad_total 63672
telemt_handshake_timeouts_total 16581
telemt_upstream_connect_attempt_total 40518
telemt_upstream_connect_success_total 40434
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 40470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 796
telemt_me_reconnect_attempts_total 12882
telemt_me_reconnect_success_total 12856
telemt_me_reader_eof_total 17532
telemt_me_idle_close_by_peer_total 17530
telemt_me_route_drop_no_conn_total 62415
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 467
telemt_me_writer_removed_unexpected_total 17537
telemt_me_writer_restored_same_endpoint_total 12851
telemt_me_writer_removed_unexpected_minus_restored_total 4686
telemt_user_connections_total{user="hello"} 146891
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1713033732 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 48352238600 (45.03 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 22897.5 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201070
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 2220
telemt_upstream_connect_attempt_total 36653
telemt_upstream_connect_success_total 36504
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 36523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1068
telemt_me_reconnect_attempts_total 10457
telemt_me_reconnect_success_total 10424
telemt_me_reader_eof_total 14172
telemt_me_idle_close_by_peer_total 14170
telemt_me_route_drop_no_conn_total 67333
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 769
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 14239
telemt_me_writer_restored_same_endpoint_total 10420
telemt_me_writer_removed_unexpected_minus_restored_total 3819
telemt_user_connections_total{user="hello"} 184569
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 10121061436 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 64717306916 (60.27 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```