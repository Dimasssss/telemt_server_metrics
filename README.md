# Server Metrics 2026-03-06 22:57:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 17361.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266151
telemt_connections_bad_total 2365
telemt_handshake_timeouts_total 9226
telemt_upstream_connect_attempt_total 33129
telemt_upstream_connect_success_total 32628
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 32996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 12720
telemt_me_reconnect_success_total 12390
telemt_me_reader_eof_total 15347
telemt_me_idle_close_by_peer_total 15347
telemt_me_route_drop_no_conn_total 104621
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 848
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 175
telemt_me_writer_removed_unexpected_total 15456
telemt_me_writer_restored_same_endpoint_total 12366
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 5193
telemt_me_writer_removed_unexpected_minus_restored_total 3072
telemt_user_connections_total{user="hello"} 240389
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 3828677364 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 109520822396 (102.00 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 17361.4 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109316
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 10183
telemt_upstream_connect_attempt_total 45076
telemt_upstream_connect_success_total 45074
telemt_upstream_connect_attempts_per_request{bucket="1"} 45074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 22303
telemt_me_reconnect_success_total 22218
telemt_me_reader_eof_total 24061
telemt_me_idle_close_by_peer_total 24057
telemt_me_route_drop_no_conn_total 38214
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 680
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 9
telemt_pool_force_close_total 433
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 24077
telemt_me_writer_restored_same_endpoint_total 22216
telemt_me_async_recovery_trigger_total 5184
telemt_me_writer_removed_unexpected_minus_restored_total 1861
telemt_user_connections_total{user="hello"} 93393
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1386170024 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 34492963292 (32.12 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 17361.2 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206937
telemt_connections_bad_total 880
telemt_handshake_timeouts_total 3290
telemt_upstream_connect_attempt_total 35369
telemt_upstream_connect_success_total 35217
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 35263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1276
telemt_me_reconnect_attempts_total 15690
telemt_me_reconnect_success_total 15651
telemt_me_reader_eof_total 16614
telemt_me_idle_close_by_peer_total 16611
telemt_me_route_drop_no_conn_total 79548
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 937
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 704
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 10
telemt_pool_force_close_total 298
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 16746
telemt_me_writer_restored_same_endpoint_total 15644
telemt_me_async_recovery_trigger_total 15425
telemt_me_writer_removed_unexpected_minus_restored_total 1102
telemt_user_connections_total{user="hello"} 192266
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 14085170288 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 57845956852 (53.87 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 17361.6 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205591
telemt_connections_bad_total 55576
telemt_handshake_timeouts_total 15969
telemt_upstream_connect_attempt_total 29104
telemt_upstream_connect_success_total 29028
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 29057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 9190
telemt_me_reconnect_success_total 9171
telemt_me_reader_eof_total 12301
telemt_me_idle_close_by_peer_total 12300
telemt_me_route_drop_no_conn_total 54588
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
telemt_me_writer_removed_unexpected_total 12307
telemt_me_writer_restored_same_endpoint_total 9166
telemt_me_writer_removed_unexpected_minus_restored_total 3141
telemt_user_connections_total{user="hello"} 130564
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1636413944 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 41842584552 (38.97 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 17360.0 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179264
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1502
telemt_upstream_connect_attempt_total 27164
telemt_upstream_connect_success_total 27029
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 27048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 891
telemt_me_reconnect_attempts_total 8218
telemt_me_reconnect_success_total 8188
telemt_me_reader_eof_total 11129
telemt_me_idle_close_by_peer_total 11128
telemt_me_route_drop_no_conn_total 61624
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
telemt_me_writer_removed_unexpected_total 11196
telemt_me_writer_restored_same_endpoint_total 8184
telemt_me_writer_removed_unexpected_minus_restored_total 3012
telemt_user_connections_total{user="hello"} 164095
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 10025365804 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 55319656168 (51.52 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 31
```