# Server Metrics 2026-03-06 23:02:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 17668.3 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268207
telemt_connections_bad_total 2442
telemt_handshake_timeouts_total 9243
telemt_upstream_connect_attempt_total 34775
telemt_upstream_connect_success_total 34219
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 34639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 74
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 1231
telemt_me_reconnect_attempts_total 13876
telemt_me_reconnect_success_total 13494
telemt_me_reader_eof_total 16343
telemt_me_idle_close_by_peer_total 16343
telemt_me_route_drop_no_conn_total 106033
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 855
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 607
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 16453
telemt_me_writer_restored_same_endpoint_total 13467
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 6414
telemt_me_writer_removed_unexpected_minus_restored_total 2965
telemt_user_connections_total{user="hello"} 242316
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3845678684 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 110435399428 (102.85 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 17668.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110382
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 10422
telemt_upstream_connect_attempt_total 49067
telemt_upstream_connect_success_total 49064
telemt_upstream_connect_attempts_per_request{bucket="1"} 49064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 25751
telemt_me_reconnect_success_total 25651
telemt_me_reader_eof_total 27183
telemt_me_idle_close_by_peer_total 27179
telemt_me_route_drop_no_conn_total 38508
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 687
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 502
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 9
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 27203
telemt_me_writer_restored_same_endpoint_total 25649
telemt_me_async_recovery_trigger_total 6405
telemt_me_writer_removed_unexpected_minus_restored_total 1554
telemt_user_connections_total{user="hello"} 94141
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1390001228 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 35009570372 (32.61 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 17668.1 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208023
telemt_connections_bad_total 883
telemt_handshake_timeouts_total 3298
telemt_upstream_connect_attempt_total 37908
telemt_upstream_connect_success_total 37755
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 37801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1310
telemt_me_reconnect_attempts_total 17836
telemt_me_reconnect_success_total 17796
telemt_me_reader_eof_total 18749
telemt_me_idle_close_by_peer_total 18746
telemt_me_route_drop_no_conn_total 79919
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 944
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 10
telemt_pool_force_close_total 298
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 18885
telemt_me_writer_restored_same_endpoint_total 17789
telemt_me_async_recovery_trigger_total 19084
telemt_me_writer_removed_unexpected_minus_restored_total 1096
telemt_user_connections_total{user="hello"} 193304
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 14136876076 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 58073907872 (54.09 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 17668.6 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207133
telemt_connections_bad_total 55850
telemt_handshake_timeouts_total 16148
telemt_upstream_connect_attempt_total 29787
telemt_upstream_connect_success_total 29711
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 29740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 582
telemt_me_reconnect_attempts_total 9455
telemt_me_reconnect_success_total 9436
telemt_me_reader_eof_total 12642
telemt_me_idle_close_by_peer_total 12641
telemt_me_route_drop_no_conn_total 54861
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 9
telemt_pool_force_close_total 332
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 12648
telemt_me_writer_restored_same_endpoint_total 9431
telemt_me_writer_removed_unexpected_minus_restored_total 3217
telemt_user_connections_total{user="hello"} 131642
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 1639032444 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 42067189920 (39.18 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 17667.1 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180390
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 27555
telemt_upstream_connect_success_total 27419
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 27438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 897
telemt_me_reconnect_attempts_total 8243
telemt_me_reconnect_success_total 8213
telemt_me_reader_eof_total 11155
telemt_me_idle_close_by_peer_total 11154
telemt_me_route_drop_no_conn_total 61894
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 9
telemt_pool_force_close_total 342
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 11222
telemt_me_writer_restored_same_endpoint_total 8209
telemt_me_writer_removed_unexpected_minus_restored_total 3013
telemt_user_connections_total{user="hello"} 165153
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10028879124 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 55635108456 (51.81 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 19
```