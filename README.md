# Server Metrics 2026-03-04 12:44:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 56016.3 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 972145
telemt_connections_bad_total 12357
telemt_handshake_timeouts_total 15636
telemt_upstream_connect_attempt_total 33368
telemt_upstream_connect_success_total 33224
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 33224
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 374
telemt_me_reconnect_attempts_total 7112
telemt_me_reconnect_success_total 7063
telemt_me_reader_eof_total 7282
telemt_me_idle_close_by_peer_total 7282
telemt_me_route_drop_no_conn_total 351296
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1564
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1034
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7282
telemt_me_writer_restored_same_endpoint_total 7041
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 763303
telemt_user_connections_current{user="hello"} 1000
telemt_user_octets_from_client{user="hello"} 8193830720 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 238993930880 (222.58 GB)
telemt_user_unique_ips_current{user="hello"} 90
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 56012.9 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380494
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 28318
telemt_upstream_connect_attempt_total 102561
telemt_upstream_connect_success_total 100982
telemt_upstream_connect_fail_total 751
telemt_upstream_connect_attempts_per_request{bucket="1"} 100976
telemt_upstream_connect_attempts_per_request{bucket="2"} 757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 751
telemt_me_keepalive_timeout_total 1416
telemt_me_reconnect_attempts_total 57149
telemt_me_reconnect_success_total 57059
telemt_me_reader_eof_total 58497
telemt_me_idle_close_by_peer_total 58496
telemt_me_route_drop_no_conn_total 155569
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 744
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58577
telemt_me_writer_restored_same_endpoint_total 57034
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 289342
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 3863320124 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 92673937344 (86.31 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 56011.6 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729392
telemt_connections_bad_total 167191
telemt_handshake_timeouts_total 23990
telemt_upstream_connect_attempt_total 81173
telemt_upstream_connect_success_total 80680
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 80679
telemt_upstream_connect_attempts_per_request{bucket="2"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1053
telemt_me_reconnect_attempts_total 37644
telemt_me_reconnect_success_total 37550
telemt_me_reader_eof_total 39539
telemt_me_idle_close_by_peer_total 39535
telemt_me_route_drop_no_conn_total 270281
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1312
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 850
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 6
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39551
telemt_me_writer_restored_same_endpoint_total 37528
telemt_me_writer_removed_unexpected_minus_restored_total 2023
telemt_user_connections_total{user="hello"} 507260
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 11555848460 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 167433957156 (155.94 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 2688.9 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30653
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 643
telemt_upstream_connect_attempt_total 1076
telemt_upstream_connect_success_total 1076
telemt_upstream_connect_attempts_per_request{bucket="1"} 1076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 82
telemt_me_idle_close_by_peer_total 82
telemt_me_route_drop_no_conn_total 10718
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 82
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 26346
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 279811896 (266.85 MB)
telemt_user_octets_to_client{user="hello"} 19070071864 (17.76 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 3048.1 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55393
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 956
telemt_upstream_connect_attempt_total 1132
telemt_upstream_connect_success_total 1123
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1123
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 16624
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 169
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 46163
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 567398864 (541.11 MB)
telemt_user_octets_to_client{user="hello"} 14226330992 (13.25 GB)
telemt_user_unique_ips_current{user="hello"} 56
```