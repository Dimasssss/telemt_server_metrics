# Server Metrics 2026-03-04 23:41:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 10083.8 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92296
telemt_connections_bad_total 1394
telemt_handshake_timeouts_total 625
telemt_upstream_connect_attempt_total 11755
telemt_upstream_connect_success_total 11609
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 11608
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 4892
telemt_me_reconnect_success_total 4888
telemt_me_reader_eof_total 5037
telemt_me_idle_close_by_peer_total 5036
telemt_me_route_drop_no_conn_total 24777
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 5096
telemt_me_writer_restored_same_endpoint_total 4868
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 79487
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 2802653104 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 46747394404 (43.54 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 10078.5 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35084
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 10797
telemt_upstream_connect_success_total 10546
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 10539
telemt_upstream_connect_attempts_per_request{bucket="2"} 51
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 4196
telemt_me_reconnect_success_total 4176
telemt_me_reader_eof_total 4238
telemt_me_idle_close_by_peer_total 4237
telemt_me_route_drop_no_conn_total 10824
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4324
telemt_me_writer_restored_same_endpoint_total 4156
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 31964
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 279583424 (266.63 MB)
telemt_user_octets_to_client{user="hello"} 9078956572 (8.46 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 10075.3 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81670
telemt_connections_bad_total 1265
telemt_handshake_timeouts_total 604
telemt_upstream_connect_attempt_total 4391
telemt_upstream_connect_success_total 4349
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4349
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 24188
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 4
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 75434
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 987887580 (942.12 MB)
telemt_user_octets_to_client{user="hello"} 25430498724 (23.68 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 42123.3 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540181
telemt_connections_bad_total 76093
telemt_handshake_timeouts_total 14706
telemt_upstream_connect_attempt_total 17840
telemt_upstream_connect_success_total 17840
telemt_upstream_connect_attempts_per_request{bucket="1"} 17840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 230
telemt_me_reconnect_attempts_total 2217
telemt_me_reconnect_success_total 2201
telemt_me_reader_eof_total 2243
telemt_me_idle_close_by_peer_total 2243
telemt_me_route_drop_no_conn_total 182978
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 170
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2244
telemt_me_writer_restored_same_endpoint_total 2174
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 420962
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 5778955332 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 157371223984 (146.56 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 42482.4 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530957
telemt_connections_bad_total 3823
telemt_handshake_timeouts_total 5829
telemt_upstream_connect_attempt_total 27454
telemt_upstream_connect_success_total 27306
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27306
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 420
telemt_me_reconnect_attempts_total 6395
telemt_me_reconnect_success_total 6376
telemt_me_reader_eof_total 6618
telemt_me_idle_close_by_peer_total 6617
telemt_me_route_drop_no_conn_total 233832
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 9
telemt_pool_force_close_total 409
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6623
telemt_me_writer_restored_same_endpoint_total 6354
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 480626
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 7353064876 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 160305350232 (149.30 GB)
telemt_user_unique_ips_current{user="hello"} 26
```