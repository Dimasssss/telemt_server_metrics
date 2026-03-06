# Server Metrics 2026-03-06 13:16:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 10455.2 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322092
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 1765
telemt_upstream_connect_attempt_total 3969
telemt_upstream_connect_success_total 3937
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 312
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 98666
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1734
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 1321
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 259101
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 4945903352 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 109852161116 (102.31 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 10455.0 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119844
telemt_connections_bad_total 805
telemt_handshake_timeouts_total 4057
telemt_upstream_connect_attempt_total 4431
telemt_upstream_connect_success_total 4418
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 532
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 47020
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 365
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 108054
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 1127534564 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 50275507776 (46.82 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 10454.9 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247420
telemt_connections_bad_total 3712
telemt_handshake_timeouts_total 18584
telemt_upstream_connect_attempt_total 5953
telemt_upstream_connect_success_total 5920
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 5946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1470
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1538
telemt_me_idle_close_by_peer_total 1538
telemt_me_route_drop_no_conn_total 114393
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 350
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1539
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 216312
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 2187367008 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 71112476220 (66.23 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 9771.2 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136746
telemt_connections_bad_total 29596
telemt_handshake_timeouts_total 2698
telemt_upstream_connect_attempt_total 5002
telemt_upstream_connect_success_total 5002
telemt_upstream_connect_attempts_per_request{bucket="1"} 5002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2126
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 726
telemt_me_reconnect_success_total 720
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 54294
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 191
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_restored_same_endpoint_total 720
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 102477
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 1297449612 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 42844543568 (39.90 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 10455.2 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197219
telemt_connections_bad_total 6877
telemt_handshake_timeouts_total 2368
telemt_upstream_connect_attempt_total 3272
telemt_upstream_connect_success_total 3266
telemt_upstream_connect_attempts_per_request{bucket="1"} 3266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 137
telemt_me_reader_eof_total 143
telemt_me_idle_close_by_peer_total 143
telemt_me_route_drop_no_conn_total 98653
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 309
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 144
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 176891
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 13746564956 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 101529614076 (94.56 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 97
```