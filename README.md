# Server Metrics 2026-03-04 15:53:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 67392.4 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1276216
telemt_connections_bad_total 17230
telemt_handshake_timeouts_total 22525
telemt_upstream_connect_attempt_total 39081
telemt_upstream_connect_success_total 38903
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 38903
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 445
telemt_me_reconnect_attempts_total 8271
telemt_me_reconnect_success_total 8205
telemt_me_reader_eof_total 8475
telemt_me_idle_close_by_peer_total 8474
telemt_me_route_drop_no_conn_total 470433
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 262
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2579
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 964
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8475
telemt_me_writer_restored_same_endpoint_total 8183
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1032945
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 13689684964 (12.75 GB)
telemt_user_octets_to_client{user="hello"} 347887410272 (324.00 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 67388.8 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484411
telemt_connections_bad_total 4197
telemt_handshake_timeouts_total 30529
telemt_upstream_connect_attempt_total 122974
telemt_upstream_connect_success_total 121235
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 121229
telemt_upstream_connect_attempts_per_request{bucket="2"} 837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_timeout_total 1608
telemt_me_reconnect_attempts_total 67206
telemt_me_reconnect_success_total 67098
telemt_me_reader_eof_total 68825
telemt_me_idle_close_by_peer_total 68824
telemt_me_route_drop_no_conn_total 197079
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 282
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1230
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 863
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 481
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 68905
telemt_me_writer_restored_same_endpoint_total 67073
telemt_me_writer_removed_unexpected_minus_restored_total 1832
telemt_user_connections_total{user="hello"} 385994
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 5919203776 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 122380864168 (113.98 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 67387.9 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981518
telemt_connections_bad_total 199558
telemt_handshake_timeouts_total 30241
telemt_upstream_connect_attempt_total 89467
telemt_upstream_connect_success_total 88855
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 88854
telemt_upstream_connect_attempts_per_request{bucket="2"} 297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 1164
telemt_me_reconnect_attempts_total 40010
telemt_me_reconnect_success_total 39905
telemt_me_reader_eof_total 42000
telemt_me_idle_close_by_peer_total 41995
telemt_me_route_drop_no_conn_total 357129
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 277
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2083
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 785
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 42013
telemt_me_writer_restored_same_endpoint_total 39883
telemt_me_writer_removed_unexpected_minus_restored_total 2130
telemt_user_connections_total{user="hello"} 705723
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 14116244384 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 237776234836 (221.45 GB)
telemt_user_unique_ips_current{user="hello"} 82
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 14064.9 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225785
telemt_connections_bad_total 25457
telemt_handshake_timeouts_total 6242
telemt_upstream_connect_attempt_total 5666
telemt_upstream_connect_success_total 5666
telemt_upstream_connect_attempts_per_request{bucket="1"} 5666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2406
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 866
telemt_me_reconnect_success_total 876
telemt_me_reader_eof_total 884
telemt_me_idle_close_by_peer_total 884
telemt_me_route_drop_no_conn_total 68384
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 227
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 185996
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 2486706992 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 72525788756 (67.54 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 14424.2 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248673
telemt_connections_bad_total 2507
telemt_handshake_timeouts_total 3789
telemt_upstream_connect_attempt_total 7365
telemt_upstream_connect_success_total 7328
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7328
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 1327
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1360
telemt_me_idle_close_by_peer_total 1360
telemt_me_route_drop_no_conn_total 93949
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 523
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_restored_same_endpoint_total 1314
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 213000
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 3564015712 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 63258452288 (58.91 GB)
telemt_user_unique_ips_current{user="hello"} 58
```