# Server Metrics 2026-03-04 23:31:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 9469.7 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89456
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 601
telemt_upstream_connect_attempt_total 10568
telemt_upstream_connect_success_total 10430
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10429
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 480
telemt_me_reconnect_attempts_total 4214
telemt_me_reconnect_success_total 4211
telemt_me_reader_eof_total 4337
telemt_me_idle_close_by_peer_total 4336
telemt_me_route_drop_no_conn_total 24128
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 4396
telemt_me_writer_restored_same_endpoint_total 4191
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 76740
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 2778384392 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 46182993712 (43.01 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 9464.5 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32783
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 225
telemt_upstream_connect_attempt_total 10415
telemt_upstream_connect_success_total 10235
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10231
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 602
telemt_me_reconnect_attempts_total 4120
telemt_me_reconnect_success_total 4108
telemt_me_reader_eof_total 4186
telemt_me_idle_close_by_peer_total 4185
telemt_me_route_drop_no_conn_total 10223
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4248
telemt_me_writer_restored_same_endpoint_total 4089
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 30888
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 266739828 (254.38 MB)
telemt_user_octets_to_client{user="hello"} 8878397192 (8.27 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 9461.0 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78523
telemt_connections_bad_total 1259
telemt_handshake_timeouts_total 596
telemt_upstream_connect_attempt_total 3975
telemt_upstream_connect_success_total 3933
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3933
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 246
telemt_me_reconnect_success_total 258
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 23377
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 72394
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 975462236 (930.27 MB)
telemt_user_octets_to_client{user="hello"} 25116424652 (23.39 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 41509.3 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537181
telemt_connections_bad_total 75058
telemt_handshake_timeouts_total 14705
telemt_upstream_connect_attempt_total 17542
telemt_upstream_connect_success_total 17542
telemt_upstream_connect_attempts_per_request{bucket="1"} 17542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 229
telemt_me_reconnect_attempts_total 2189
telemt_me_reconnect_success_total 2174
telemt_me_reader_eof_total 2216
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 182444
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 168
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
telemt_me_writer_removed_unexpected_total 2217
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 419024
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 5768372544 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 156655510172 (145.90 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 41868.5 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528964
telemt_connections_bad_total 3822
telemt_handshake_timeouts_total 5826
telemt_upstream_connect_attempt_total 27219
telemt_upstream_connect_success_total 27073
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 27073
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 6391
telemt_me_reconnect_success_total 6372
telemt_me_reader_eof_total 6613
telemt_me_idle_close_by_peer_total 6612
telemt_me_route_drop_no_conn_total 233244
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 169
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
telemt_me_writer_removed_unexpected_total 6618
telemt_me_writer_restored_same_endpoint_total 6350
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 478652
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 7334258164 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 159162126676 (148.23 GB)
telemt_user_unique_ips_current{user="hello"} 29
```