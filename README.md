# Server Metrics 2026-03-06 23:53:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 20745.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285150
telemt_connections_bad_total 3004
telemt_handshake_timeouts_total 9292
telemt_upstream_connect_attempt_total 51206
telemt_upstream_connect_success_total 50018
telemt_upstream_connect_fail_total 1051
telemt_upstream_connect_attempts_per_request{bucket="1"} 51069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1051
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 25993
telemt_me_reconnect_success_total 24987
telemt_me_reader_eof_total 28042
telemt_me_idle_close_by_peer_total 28042
telemt_me_route_drop_no_conn_total 111235
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 7
telemt_pool_force_close_total 410
telemt_pool_stale_pick_total 179
telemt_me_writer_removed_unexpected_total 28154
telemt_me_writer_restored_same_endpoint_total 24922
telemt_me_writer_restored_fallback_total 59
telemt_me_async_recovery_trigger_total 18652
telemt_me_writer_removed_unexpected_minus_restored_total 3173
telemt_user_connections_total{user="hello"} 258299
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 4055217916 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 115779329000 (107.83 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 20745.9 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119834
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12823
telemt_upstream_connect_attempt_total 87327
telemt_upstream_connect_success_total 87325
telemt_upstream_connect_attempts_per_request{bucket="1"} 87325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 950
telemt_me_reconnect_attempts_total 58889
telemt_me_reconnect_success_total 58661
telemt_me_reader_eof_total 56730
telemt_me_idle_close_by_peer_total 56725
telemt_me_route_drop_no_conn_total 40130
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 801
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 12
telemt_pool_force_close_total 699
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 56755
telemt_me_writer_restored_same_endpoint_total 58659
telemt_me_async_recovery_trigger_total 18646
telemt_user_connections_total{user="hello"} 100933
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 1496786680 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 36445819792 (33.94 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 20745.7 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220329
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 3525
telemt_upstream_connect_attempt_total 67938
telemt_upstream_connect_success_total 67776
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 67829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1700
telemt_me_reconnect_attempts_total 43320
telemt_me_reconnect_success_total 43269
telemt_me_reader_eof_total 44932
telemt_me_idle_close_by_peer_total 44928
telemt_me_route_drop_no_conn_total 83365
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 169
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
telemt_me_writer_removed_unexpected_total 45094
telemt_me_writer_restored_same_endpoint_total 43262
telemt_me_async_recovery_trigger_total 55774
telemt_me_writer_removed_unexpected_minus_restored_total 1832
telemt_user_connections_total{user="hello"} 205006
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 16704142024 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 59775004332 (55.67 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 20746.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220217
telemt_connections_bad_total 58616
telemt_handshake_timeouts_total 16181
telemt_upstream_connect_attempt_total 36077
telemt_upstream_connect_success_total 35996
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 36030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 710
telemt_me_reconnect_attempts_total 11417
telemt_me_reconnect_success_total 11395
telemt_me_reader_eof_total 15449
telemt_me_idle_close_by_peer_total 15447
telemt_me_route_drop_no_conn_total 59451
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 11
telemt_pool_force_close_total 393
telemt_pool_stale_pick_total 453
telemt_me_writer_removed_unexpected_total 15454
telemt_me_writer_restored_same_endpoint_total 11390
telemt_me_writer_removed_unexpected_minus_restored_total 4064
telemt_user_connections_total{user="hello"} 141610
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 1669308976 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 46648026240 (43.44 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 20744.5 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192746
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 32516
telemt_upstream_connect_success_total 32371
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 32390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 980
telemt_me_reconnect_attempts_total 9249
telemt_me_reconnect_success_total 9218
telemt_me_reader_eof_total 12393
telemt_me_idle_close_by_peer_total 12392
telemt_me_route_drop_no_conn_total 65012
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 165
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
telemt_me_writer_removed_unexpected_total 12460
telemt_me_writer_restored_same_endpoint_total 9214
telemt_me_writer_removed_unexpected_minus_restored_total 3246
telemt_user_connections_total{user="hello"} 176729
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 10073328712 (9.38 GB)
telemt_user_octets_to_client{user="hello"} 60304483264 (56.16 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 24
```