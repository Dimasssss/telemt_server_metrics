# Server Metrics 2026-03-06 22:00:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 13973.6 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244525
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 9030
telemt_upstream_connect_attempt_total 22199
telemt_upstream_connect_success_total 22036
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 22096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1026
telemt_me_reconnect_attempts_total 6776
telemt_me_reconnect_success_total 6743
telemt_me_reader_eof_total 8838
telemt_me_idle_close_by_peer_total 8838
telemt_me_route_drop_no_conn_total 93885
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 161
telemt_me_writer_removed_unexpected_total 8945
telemt_me_writer_restored_same_endpoint_total 6737
telemt_me_writer_removed_unexpected_minus_restored_total 2208
telemt_user_connections_total{user="hello"} 219697
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 3317618732 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 84579605404 (78.77 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 13973.5 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96377
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 7336
telemt_upstream_connect_attempt_total 26503
telemt_upstream_connect_success_total 26502
telemt_upstream_connect_attempts_per_request{bucket="1"} 26502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 8934
telemt_me_reconnect_success_total 8922
telemt_me_reader_eof_total 12516
telemt_me_idle_close_by_peer_total 12514
telemt_me_route_drop_no_conn_total 35125
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 619
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 12516
telemt_me_writer_restored_same_endpoint_total 8920
telemt_me_writer_removed_unexpected_minus_restored_total 3596
telemt_user_connections_total{user="hello"} 83627
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1316576728 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 26827728520 (24.99 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 13973.5 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186582
telemt_connections_bad_total 589
telemt_handshake_timeouts_total 2970
telemt_upstream_connect_attempt_total 21497
telemt_upstream_connect_success_total 21354
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 21393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1014
telemt_me_reconnect_attempts_total 6141
telemt_me_reconnect_success_total 6114
telemt_me_reader_eof_total 8153
telemt_me_idle_close_by_peer_total 8150
telemt_me_route_drop_no_conn_total 71601
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 854
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 645
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 8254
telemt_me_writer_restored_same_endpoint_total 6107
telemt_me_writer_removed_unexpected_minus_restored_total 2147
telemt_user_connections_total{user="hello"} 172703
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 11113427012 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 52138594536 (48.56 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 13973.9 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187686
telemt_connections_bad_total 52537
telemt_handshake_timeouts_total 14362
telemt_upstream_connect_attempt_total 22323
telemt_upstream_connect_success_total 22254
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 22276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 427
telemt_me_reconnect_attempts_total 6873
telemt_me_reconnect_success_total 6858
telemt_me_reader_eof_total 9039
telemt_me_idle_close_by_peer_total 9039
telemt_me_route_drop_no_conn_total 47543
telemt_me_single_endpoint_shadow_rotate_total 118
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
telemt_me_writer_removed_unexpected_total 9044
telemt_me_writer_restored_same_endpoint_total 6853
telemt_me_writer_removed_unexpected_minus_restored_total 2191
telemt_user_connections_total{user="hello"} 117550
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1581002524 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 36458921472 (33.96 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 13972.4 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159100
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1120
telemt_upstream_connect_attempt_total 21205
telemt_upstream_connect_success_total 21082
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 21101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 761
telemt_me_reconnect_attempts_total 6479
telemt_me_reconnect_success_total 6452
telemt_me_reader_eof_total 8751
telemt_me_idle_close_by_peer_total 8750
telemt_me_route_drop_no_conn_total 56154
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 729
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 6
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8813
telemt_me_writer_restored_same_endpoint_total 6450
telemt_me_writer_removed_unexpected_minus_restored_total 2363
telemt_user_connections_total{user="hello"} 146461
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 9390815516 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 49618732640 (46.21 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 36
```