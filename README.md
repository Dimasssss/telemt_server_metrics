# Server Metrics 2026-03-06 13:31:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 11378.1 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346283
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 4715
telemt_upstream_connect_success_total 4682
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 518
telemt_me_reconnect_success_total 512
telemt_me_reader_eof_total 529
telemt_me_idle_close_by_peer_total 529
telemt_me_route_drop_no_conn_total 109532
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1901
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 1447
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 282149
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 5343639900 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 119101976064 (110.92 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 11378.0 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128611
telemt_connections_bad_total 814
telemt_handshake_timeouts_total 4193
telemt_upstream_connect_attempt_total 4962
telemt_upstream_connect_success_total 4947
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2670
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 579
telemt_me_idle_close_by_peer_total 579
telemt_me_route_drop_no_conn_total 54534
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 400
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_restored_same_endpoint_total 541
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 116467
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 1235372660 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 54661929464 (50.91 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 11378.0 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272751
telemt_connections_bad_total 4429
telemt_handshake_timeouts_total 25688
telemt_upstream_connect_attempt_total 6618
telemt_upstream_connect_success_total 6580
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 6610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 1558
telemt_me_reader_eof_total 1633
telemt_me_idle_close_by_peer_total 1633
telemt_me_route_drop_no_conn_total 126387
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 409
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1634
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 232680
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 2335466104 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 75604545972 (70.41 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 10693.9 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153628
telemt_connections_bad_total 33845
telemt_handshake_timeouts_total 2933
telemt_upstream_connect_attempt_total 5445
telemt_upstream_connect_success_total 5445
telemt_upstream_connect_attempts_per_request{bucket="1"} 5445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 756
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 63805
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 761
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 114572
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 1393689616 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 46788305312 (43.58 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 11378.1 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210988
telemt_connections_bad_total 7684
telemt_handshake_timeouts_total 2401
telemt_upstream_connect_attempt_total 3817
telemt_upstream_connect_success_total 3811
telemt_upstream_connect_attempts_per_request{bucket="1"} 3811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 211
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 108547
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 330
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 211
telemt_me_writer_restored_same_endpoint_total 203
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 189478
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 13822526904 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 109504420088 (101.98 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 103
```