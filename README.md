# Server Metrics 2026-03-07 00:04:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 21360.2 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288257
telemt_connections_bad_total 3005
telemt_handshake_timeouts_total 9314
telemt_upstream_connect_attempt_total 53869
telemt_upstream_connect_success_total 52535
telemt_upstream_connect_fail_total 1196
telemt_upstream_connect_attempts_per_request{bucket="1"} 53731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1196
telemt_me_keepalive_timeout_total 1466
telemt_me_reconnect_attempts_total 28080
telemt_me_reconnect_success_total 26936
telemt_me_reader_eof_total 29796
telemt_me_idle_close_by_peer_total 29796
telemt_me_route_drop_no_conn_total 111919
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 8
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 185
telemt_me_writer_removed_unexpected_total 29908
telemt_me_writer_restored_same_endpoint_total 26862
telemt_me_writer_restored_fallback_total 68
telemt_me_async_recovery_trigger_total 21096
telemt_me_writer_removed_unexpected_minus_restored_total 2978
telemt_user_connections_total{user="hello"} 261306
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 4090297916 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 116880709916 (108.85 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 21360.2 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121594
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 13324
telemt_upstream_connect_attempt_total 95749
telemt_upstream_connect_success_total 95747
telemt_upstream_connect_attempts_per_request{bucket="1"} 95747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 999
telemt_me_reconnect_attempts_total 66264
telemt_me_reconnect_success_total 66019
telemt_me_reader_eof_total 62599
telemt_me_idle_close_by_peer_total 62594
telemt_me_route_drop_no_conn_total 40438
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 804
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 13
telemt_pool_force_close_total 771
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 62626
telemt_me_writer_restored_same_endpoint_total 66017
telemt_me_async_recovery_trigger_total 21089
telemt_user_connections_total{user="hello"} 102163
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1511465488 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 36553046504 (34.04 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 21360.0 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222724
telemt_connections_bad_total 1128
telemt_handshake_timeouts_total 3544
telemt_upstream_connect_attempt_total 74706
telemt_upstream_connect_success_total 74541
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 74597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1783
telemt_me_reconnect_attempts_total 49109
telemt_me_reconnect_success_total 49057
telemt_me_reader_eof_total 51081
telemt_me_idle_close_by_peer_total 51076
telemt_me_route_drop_no_conn_total 84522
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1029
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 51243
telemt_me_writer_restored_same_endpoint_total 49050
telemt_me_async_recovery_trigger_total 63095
telemt_me_writer_removed_unexpected_minus_restored_total 2193
telemt_user_connections_total{user="hello"} 207337
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 17328953768 (16.14 GB)
telemt_user_octets_to_client{user="hello"} 60352492756 (56.21 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 21360.5 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222320
telemt_connections_bad_total 59165
telemt_handshake_timeouts_total 16186
telemt_upstream_connect_attempt_total 36858
telemt_upstream_connect_success_total 36776
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 36810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 11487
telemt_me_reconnect_success_total 11465
telemt_me_reader_eof_total 15539
telemt_me_idle_close_by_peer_total 15537
telemt_me_route_drop_no_conn_total 60148
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 203
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 464
telemt_me_writer_removed_unexpected_total 15544
telemt_me_writer_restored_same_endpoint_total 11460
telemt_me_writer_removed_unexpected_minus_restored_total 4084
telemt_user_connections_total{user="hello"} 143131
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 1685885124 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 46879661336 (43.66 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 21358.9 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194756
telemt_connections_bad_total 501
telemt_handshake_timeouts_total 2005
telemt_upstream_connect_attempt_total 34063
telemt_upstream_connect_success_total 33916
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 33935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1006
telemt_me_reconnect_attempts_total 9843
telemt_me_reconnect_success_total 9812
telemt_me_reader_eof_total 13311
telemt_me_idle_close_by_peer_total 13310
telemt_me_route_drop_no_conn_total 65847
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 12
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 13378
telemt_me_writer_restored_same_endpoint_total 9808
telemt_me_writer_removed_unexpected_minus_restored_total 3570
telemt_user_connections_total{user="hello"} 178624
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 10079967800 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 60566012156 (56.41 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```