# Server Metrics 2026-03-04 16:39:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 70159.0 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355697
telemt_connections_bad_total 18930
telemt_handshake_timeouts_total 23079
telemt_upstream_connect_attempt_total 41511
telemt_upstream_connect_success_total 41324
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 41324
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 473
telemt_me_reconnect_attempts_total 9144
telemt_me_reconnect_success_total 9074
telemt_me_reader_eof_total 9390
telemt_me_idle_close_by_peer_total 9389
telemt_me_route_drop_no_conn_total 536534
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2936
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 2006
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1100
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 9391
telemt_me_writer_restored_same_endpoint_total 9052
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 1106354
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 14684710596 (13.68 GB)
telemt_user_octets_to_client{user="hello"} 369366822916 (344.00 GB)
telemt_user_unique_ips_current{user="hello"} 103
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 70155.5 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517866
telemt_connections_bad_total 5933
telemt_handshake_timeouts_total 30780
telemt_upstream_connect_attempt_total 124633
telemt_upstream_connect_success_total 122823
telemt_upstream_connect_fail_total 867
telemt_upstream_connect_attempts_per_request{bucket="1"} 122817
telemt_upstream_connect_attempts_per_request{bucket="2"} 873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 867
telemt_me_keepalive_timeout_total 1637
telemt_me_reconnect_attempts_total 67728
telemt_me_reconnect_success_total 67621
telemt_me_reader_eof_total 69358
telemt_me_idle_close_by_peer_total 69357
telemt_me_route_drop_no_conn_total 217987
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1327
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 182
telemt_me_writer_removed_unexpected_total 69438
telemt_me_writer_restored_same_endpoint_total 67595
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 416334
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 6162178692 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 130782162220 (121.80 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 70154.3 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041415
telemt_connections_bad_total 207597
telemt_handshake_timeouts_total 30395
telemt_upstream_connect_attempt_total 90768
telemt_upstream_connect_success_total 90144
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 90143
telemt_upstream_connect_attempts_per_request{bucket="2"} 303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 1185
telemt_me_reconnect_attempts_total 40265
telemt_me_reconnect_success_total 40157
telemt_me_reader_eof_total 42281
telemt_me_idle_close_by_peer_total 42276
telemt_me_route_drop_no_conn_total 386510
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 287
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2183
telemt_desync_full_logged_total 726
telemt_desync_suppressed_total 1457
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 713
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42294
telemt_me_writer_restored_same_endpoint_total 40135
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 754180
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 14620138236 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 258804585932 (241.03 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 16831.7 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277357
telemt_connections_bad_total 33785
telemt_handshake_timeouts_total 6567
telemt_upstream_connect_attempt_total 6600
telemt_upstream_connect_success_total 6600
telemt_upstream_connect_attempts_per_request{bucket="1"} 6600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2902
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 876
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 893
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 92561
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 294
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_restored_same_endpoint_total 862
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 227376
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 2878070828 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 84182145496 (78.40 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 17191.0 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293328
telemt_connections_bad_total 3076
telemt_handshake_timeouts_total 4117
telemt_upstream_connect_attempt_total 8310
telemt_upstream_connect_success_total 8267
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8267
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 1353
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1384
telemt_me_idle_close_by_peer_total 1384
telemt_me_route_drop_no_conn_total 116332
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 558
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1384
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 253388
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 4183046032 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 75175380108 (70.01 GB)
telemt_user_unique_ips_current{user="hello"} 60
```