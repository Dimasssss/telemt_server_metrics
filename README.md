# Server Metrics 2026-03-06 07:37:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 33355.7 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343148
telemt_connections_bad_total 16314
telemt_handshake_timeouts_total 3961
telemt_upstream_connect_attempt_total 34307
telemt_upstream_connect_success_total 33956
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 33956
telemt_upstream_connect_attempts_per_request{bucket="2"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 351
telemt_me_reconnect_attempts_total 12274
telemt_me_reconnect_success_total 12224
telemt_me_reader_eof_total 12641
telemt_me_idle_close_by_peer_total 12641
telemt_me_route_drop_no_conn_total 120317
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1126
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 12644
telemt_me_writer_restored_same_endpoint_total 12218
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 303286
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 10055629452 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 109290991760 (101.79 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 33351.2 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149272
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 17132
telemt_upstream_connect_attempt_total 26359
telemt_upstream_connect_success_total 26357
telemt_upstream_connect_attempts_per_request{bucket="1"} 26357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6798
telemt_me_reconnect_success_total 6768
telemt_me_reader_eof_total 6919
telemt_me_idle_close_by_peer_total 6919
telemt_me_route_drop_no_conn_total 43710
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 437
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6920
telemt_me_writer_restored_same_endpoint_total 6761
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 129285
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 1468507688 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 41102156280 (38.28 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 33348.4 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261087
telemt_connections_bad_total 1972
telemt_handshake_timeouts_total 8752
telemt_upstream_connect_attempt_total 37035
telemt_upstream_connect_success_total 36752
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 36752
telemt_upstream_connect_attempts_per_request{bucket="2"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 14134
telemt_me_reconnect_success_total 14092
telemt_me_reader_eof_total 14745
telemt_me_idle_close_by_peer_total 14743
telemt_me_route_drop_no_conn_total 78037
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 641
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14774
telemt_me_writer_restored_same_endpoint_total 14070
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 228903
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2347372280 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 70920835808 (66.05 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 33345.1 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198030
telemt_connections_bad_total 26160
telemt_handshake_timeouts_total 8153
telemt_upstream_connect_attempt_total 23127
telemt_upstream_connect_success_total 23047
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 23047
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 5025
telemt_me_reconnect_success_total 4991
telemt_me_reader_eof_total 5163
telemt_me_idle_close_by_peer_total 5163
telemt_me_route_drop_no_conn_total 60982
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 468
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5164
telemt_me_writer_restored_same_endpoint_total 4984
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 156332
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 2162785004 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 53827115292 (50.13 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 33344.2 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211240
telemt_connections_bad_total 3298
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 22185
telemt_upstream_connect_success_total 22134
telemt_upstream_connect_attempts_per_request{bucket="1"} 22134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 3856
telemt_me_reconnect_success_total 3836
telemt_me_reader_eof_total 3961
telemt_me_idle_close_by_peer_total 3960
telemt_me_route_drop_no_conn_total 85992
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 459
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3976
telemt_me_writer_restored_same_endpoint_total 3829
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 202288
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 24684501468 (22.99 GB)
telemt_user_octets_to_client{user="hello"} 120241083652 (111.98 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 91
```