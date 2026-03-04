# Server Metrics 2026-03-04 11:58:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 53248.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879823
telemt_connections_bad_total 12089
telemt_handshake_timeouts_total 12971
telemt_upstream_connect_attempt_total 32563
telemt_upstream_connect_success_total 32424
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32424
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 362
telemt_me_reconnect_attempts_total 7086
telemt_me_reconnect_success_total 7038
telemt_me_reader_eof_total 7258
telemt_me_idle_close_by_peer_total 7258
telemt_me_route_drop_no_conn_total 329816
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1410
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 928
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 14
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7258
telemt_me_writer_restored_same_endpoint_total 7017
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 703757
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 7557136832 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 214214858480 (199.50 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 53244.7 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351795
telemt_connections_bad_total 3101
telemt_handshake_timeouts_total 27545
telemt_upstream_connect_attempt_total 101051
telemt_upstream_connect_success_total 99524
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 99518
telemt_upstream_connect_attempts_per_request{bucket="2"} 731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1404
telemt_me_reconnect_attempts_total 56966
telemt_me_reconnect_success_total 56878
telemt_me_reader_eof_total 58315
telemt_me_idle_close_by_peer_total 58314
telemt_me_route_drop_no_conn_total 145420
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 636
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58395
telemt_me_writer_restored_same_endpoint_total 56853
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 264456
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 3488143220 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 83785666172 (78.03 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 53243.5 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667610
telemt_connections_bad_total 159450
telemt_handshake_timeouts_total 21423
telemt_upstream_connect_attempt_total 78941
telemt_upstream_connect_success_total 78478
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 78477
telemt_upstream_connect_attempts_per_request{bucket="2"} 223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1026
telemt_me_reconnect_attempts_total 36977
telemt_me_reconnect_success_total 36887
telemt_me_reader_eof_total 38857
telemt_me_idle_close_by_peer_total 38853
telemt_me_route_drop_no_conn_total 249589
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1164
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38869
telemt_me_writer_restored_same_endpoint_total 36865
telemt_me_writer_removed_unexpected_minus_restored_total 2004
telemt_user_connections_total{user="hello"} 464346
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 6030691708 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 154602530264 (143.98 GB)
telemt_user_unique_ips_current{user="hello"} 53
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 53242.5 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429145
telemt_connections_bad_total 30092
telemt_handshake_timeouts_total 67223
telemt_upstream_connect_attempt_total 39130
telemt_upstream_connect_success_total 38973
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 38973
telemt_upstream_connect_attempts_per_request{bucket="2"} 77
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 8314
telemt_me_reconnect_success_total 8285
telemt_me_reader_eof_total 8469
telemt_me_idle_close_by_peer_total 8469
telemt_me_route_drop_no_conn_total 123556
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 219
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8469
telemt_me_writer_restored_same_endpoint_total 8264
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 309125
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 3842850696 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 114189743888 (106.35 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 280.0 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4956
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 86
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 86
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 883
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_user_connections_total{user="hello"} 4343
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 20670492 (19.71 MB)
telemt_user_octets_to_client{user="hello"} 1007919340 (961.23 MB)
telemt_user_unique_ips_current{user="hello"} 64
```