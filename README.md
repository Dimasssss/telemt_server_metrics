# Server Metrics 2026-03-04 13:09:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 57554.5 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016022
telemt_connections_bad_total 13352
telemt_handshake_timeouts_total 15865
telemt_upstream_connect_attempt_total 34030
telemt_upstream_connect_success_total 33883
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33883
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 380
telemt_me_reconnect_attempts_total 7133
telemt_me_reconnect_success_total 7082
telemt_me_reader_eof_total 7302
telemt_me_idle_close_by_peer_total 7302
telemt_me_route_drop_no_conn_total 365842
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1636
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7302
telemt_me_writer_restored_same_endpoint_total 7060
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 799806
telemt_user_connections_current{user="hello"} 1207
telemt_user_octets_from_client{user="hello"} 9039565608 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 260817289728 (242.91 GB)
telemt_user_unique_ips_current{user="hello"} 79
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 57550.9 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395305
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 28788
telemt_upstream_connect_attempt_total 104144
telemt_upstream_connect_success_total 102554
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 102548
telemt_upstream_connect_attempts_per_request{bucket="2"} 763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 1427
telemt_me_reconnect_attempts_total 57582
telemt_me_reconnect_success_total 57491
telemt_me_reader_eof_total 58937
telemt_me_idle_close_by_peer_total 58936
telemt_me_route_drop_no_conn_total 161604
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 782
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59017
telemt_me_writer_restored_same_endpoint_total 57466
telemt_me_writer_removed_unexpected_minus_restored_total 1551
telemt_user_connections_total{user="hello"} 303226
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 3990512548 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 96239174492 (89.63 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 57549.9 (15h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766330
telemt_connections_bad_total 171548
telemt_handshake_timeouts_total 26322
telemt_upstream_connect_attempt_total 81747
telemt_upstream_connect_success_total 81234
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 81233
telemt_upstream_connect_attempts_per_request{bucket="2"} 248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 1065
telemt_me_reconnect_attempts_total 37673
telemt_me_reconnect_success_total 37577
telemt_me_reader_eof_total 39567
telemt_me_idle_close_by_peer_total 39563
telemt_me_route_drop_no_conn_total 282011
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1422
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 929
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39579
telemt_me_writer_restored_same_endpoint_total 37555
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 532918
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 11852519320 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 179379336188 (167.06 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 4227.0 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52102
telemt_connections_bad_total 4931
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 1508
telemt_upstream_connect_success_total 1508
telemt_upstream_connect_attempts_per_request{bucket="1"} 1508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 574
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 96
telemt_me_reconnect_success_total 115
telemt_me_reader_eof_total 96
telemt_me_idle_close_by_peer_total 96
telemt_me_route_drop_no_conn_total 18067
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 54
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_restored_same_endpoint_total 94
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 45529
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 893104784 (851.73 MB)
telemt_user_octets_to_client{user="hello"} 30386079208 (28.30 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 4586.4 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83722
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 1261
telemt_upstream_connect_attempt_total 2324
telemt_upstream_connect_success_total 2309
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2309
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 273
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 26482
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 245
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 273
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 72140
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 776648188 (740.67 MB)
telemt_user_octets_to_client{user="hello"} 19479236064 (18.14 GB)
telemt_user_unique_ips_current{user="hello"} 45
```