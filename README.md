# Server Metrics 2026-03-07 02:27:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 29989.4 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333278
telemt_connections_bad_total 3896
telemt_handshake_timeouts_total 9624
telemt_upstream_connect_attempt_total 100370
telemt_upstream_connect_success_total 97353
telemt_upstream_connect_fail_total 2863
telemt_upstream_connect_attempts_per_request{bucket="1"} 100216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2863
telemt_me_keepalive_timeout_total 2036
telemt_me_reconnect_attempts_total 62899
telemt_me_reconnect_success_total 60128
telemt_me_reader_eof_total 62822
telemt_me_idle_close_by_peer_total 62819
telemt_me_route_drop_no_conn_total 124701
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1153
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 836
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 515
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 14
telemt_pool_force_close_total 628
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 62936
telemt_me_writer_restored_same_endpoint_total 59954
telemt_me_writer_restored_fallback_total 168
telemt_me_async_recovery_trigger_total 55417
telemt_me_writer_removed_unexpected_minus_restored_total 2814
telemt_user_connections_total{user="hello"} 303575
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 4460654236 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 132357302992 (123.27 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 29989.4 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146547
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 20091
telemt_upstream_connect_attempt_total 208973
telemt_upstream_connect_success_total 208971
telemt_upstream_connect_attempts_per_request{bucket="1"} 208971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1577
telemt_me_reconnect_attempts_total 165352
telemt_me_reconnect_success_total 164878
telemt_me_reader_eof_total 148460
telemt_me_idle_close_by_peer_total 148455
telemt_me_route_drop_no_conn_total 44673
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 847
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 23
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 148501
telemt_me_writer_restored_same_endpoint_total 164876
telemt_me_async_recovery_trigger_total 55411
telemt_user_connections_total{user="hello"} 119169
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 1621750536 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 40237869392 (37.47 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 29989.2 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259968
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 4378
telemt_upstream_connect_attempt_total 159301
telemt_upstream_connect_success_total 159064
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 159154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 2801
telemt_me_reconnect_attempts_total 121277
telemt_me_reconnect_success_total 121180
telemt_me_reader_eof_total 123253
telemt_me_idle_close_by_peer_total 123248
telemt_me_route_drop_no_conn_total 95121
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1104
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 16
telemt_pool_force_close_total 405
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 123444
telemt_me_writer_restored_same_endpoint_total 121173
telemt_me_async_recovery_trigger_total 165967
telemt_me_writer_removed_unexpected_minus_restored_total 2271
telemt_user_connections_total{user="hello"} 243067
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 23942877008 (22.30 GB)
telemt_user_octets_to_client{user="hello"} 68241214172 (63.55 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 29989.6 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269631
telemt_connections_bad_total 83471
telemt_handshake_timeouts_total 17563
telemt_upstream_connect_attempt_total 59602
telemt_upstream_connect_success_total 59510
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 59554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1131
telemt_me_reconnect_attempts_total 21381
telemt_me_reconnect_success_total 21346
telemt_me_reader_eof_total 29065
telemt_me_idle_close_by_peer_total 29063
telemt_me_route_drop_no_conn_total 73636
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 257
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 29070
telemt_me_writer_restored_same_endpoint_total 21341
telemt_me_writer_removed_unexpected_minus_restored_total 7729
telemt_user_connections_total{user="hello"} 164329
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1816083192 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 51815110576 (48.26 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 29988.0 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226980
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 2935
telemt_upstream_connect_attempt_total 50736
telemt_upstream_connect_success_total 50544
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 50568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1352
telemt_me_reconnect_attempts_total 14788
telemt_me_reconnect_success_total 14747
telemt_me_reader_eof_total 20338
telemt_me_idle_close_by_peer_total 20336
telemt_me_route_drop_no_conn_total 74271
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 813
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 19
telemt_pool_force_close_total 508
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 20407
telemt_me_writer_restored_same_endpoint_total 14739
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5664
telemt_user_connections_total{user="hello"} 208462
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10333649020 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 79453680840 (74.00 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 32
```