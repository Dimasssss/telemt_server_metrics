# Server Metrics 2026-03-07 02:38:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 30616.9 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337072
telemt_connections_bad_total 3896
telemt_handshake_timeouts_total 9641
telemt_upstream_connect_attempt_total 103761
telemt_upstream_connect_success_total 100620
telemt_upstream_connect_fail_total 2985
telemt_upstream_connect_attempts_per_request{bucket="1"} 103605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2985
telemt_me_keepalive_timeout_total 2084
telemt_me_reconnect_attempts_total 65293
telemt_me_reconnect_success_total 62401
telemt_me_reader_eof_total 65318
telemt_me_idle_close_by_peer_total 65315
telemt_me_route_drop_no_conn_total 125757
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1208
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 14
telemt_pool_force_close_total 628
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 65432
telemt_me_writer_restored_same_endpoint_total 62219
telemt_me_writer_restored_fallback_total 176
telemt_me_async_recovery_trigger_total 57913
telemt_me_writer_removed_unexpected_minus_restored_total 3037
telemt_user_connections_total{user="hello"} 307104
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 4481233588 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 134006022468 (124.80 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 30616.8 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147955
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 20497
telemt_upstream_connect_attempt_total 217158
telemt_upstream_connect_success_total 217156
telemt_upstream_connect_attempts_per_request{bucket="1"} 217156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 169056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1605
telemt_me_reconnect_attempts_total 172541
telemt_me_reconnect_success_total 172052
telemt_me_reader_eof_total 155610
telemt_me_idle_close_by_peer_total 155605
telemt_me_route_drop_no_conn_total 45062
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 264
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 848
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 23
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 155652
telemt_me_writer_restored_same_endpoint_total 172050
telemt_me_async_recovery_trigger_total 57906
telemt_user_connections_total{user="hello"} 120078
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 1630675096 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 40748048016 (37.95 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 30616.7 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262472
telemt_connections_bad_total 1473
telemt_handshake_timeouts_total 4662
telemt_upstream_connect_attempt_total 166394
telemt_upstream_connect_success_total 166156
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 166246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 2889
telemt_me_reconnect_attempts_total 127422
telemt_me_reconnect_success_total 127324
telemt_me_reader_eof_total 129771
telemt_me_idle_close_by_peer_total 129766
telemt_me_route_drop_no_conn_total 95782
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 251
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1105
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 445
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 16
telemt_pool_force_close_total 406
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 129962
telemt_me_writer_restored_same_endpoint_total 127317
telemt_me_async_recovery_trigger_total 173447
telemt_me_writer_removed_unexpected_minus_restored_total 2645
telemt_user_connections_total{user="hello"} 245220
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 24665981944 (22.97 GB)
telemt_user_octets_to_client{user="hello"} 68555731856 (63.85 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 30616.9 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272091
telemt_connections_bad_total 84032
telemt_handshake_timeouts_total 17807
telemt_upstream_connect_attempt_total 61539
telemt_upstream_connect_success_total 61448
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 61492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1158
telemt_me_reconnect_attempts_total 22350
telemt_me_reconnect_success_total 22314
telemt_me_reader_eof_total 30398
telemt_me_idle_close_by_peer_total 30396
telemt_me_route_drop_no_conn_total 74310
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 30403
telemt_me_writer_restored_same_endpoint_total 22309
telemt_me_writer_removed_unexpected_minus_restored_total 8094
telemt_user_connections_total{user="hello"} 165968
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 1833339164 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 52554691176 (48.95 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 30615.5 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229451
telemt_connections_bad_total 523
telemt_handshake_timeouts_total 2999
telemt_upstream_connect_attempt_total 51645
telemt_upstream_connect_success_total 51448
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 51473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1361
telemt_me_reconnect_attempts_total 15000
telemt_me_reconnect_success_total 14957
telemt_me_reader_eof_total 20583
telemt_me_idle_close_by_peer_total 20581
telemt_me_route_drop_no_conn_total 74833
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 814
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 19
telemt_pool_force_close_total 508
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 20652
telemt_me_writer_restored_same_endpoint_total 14949
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5699
telemt_user_connections_total{user="hello"} 210765
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 10359482252 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 80842720372 (75.29 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```