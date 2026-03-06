# Server Metrics 2026-03-06 14:28:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 14765.3 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440416
telemt_connections_bad_total 1842
telemt_handshake_timeouts_total 2419
telemt_upstream_connect_attempt_total 8057
telemt_upstream_connect_success_total 8009
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 1828
telemt_me_reconnect_success_total 1819
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1913
telemt_me_route_drop_no_conn_total 156438
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2387
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1808
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 1017
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1915
telemt_me_writer_restored_same_endpoint_total 1813
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 373014
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 10604734556 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 152536249748 (142.06 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 14765.1 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167656
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 5405
telemt_upstream_connect_attempt_total 6367
telemt_upstream_connect_success_total 6351
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 607
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 82840
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 616
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 640
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 153401
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 1685017612 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 71420915228 (66.52 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 14765.0 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347249
telemt_connections_bad_total 5122
telemt_handshake_timeouts_total 35545
telemt_upstream_connect_attempt_total 10977
telemt_upstream_connect_success_total 10927
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 3249
telemt_me_reconnect_success_total 3236
telemt_me_reader_eof_total 3427
telemt_me_idle_close_by_peer_total 3427
telemt_me_route_drop_no_conn_total 164785
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 595
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 3429
telemt_me_writer_restored_same_endpoint_total 3231
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 294708
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 3085181712 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 93982262444 (87.53 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 14081.0 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244712
telemt_connections_bad_total 44369
telemt_handshake_timeouts_total 8611
telemt_upstream_connect_attempt_total 6956
telemt_upstream_connect_success_total 6956
telemt_upstream_connect_attempts_per_request{bucket="1"} 6956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2894
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 964
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 967
telemt_me_idle_close_by_peer_total 967
telemt_me_route_drop_no_conn_total 87213
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_restored_same_endpoint_total 952
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 158577
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 1932542396 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 60637312116 (56.47 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 14765.2 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265812
telemt_connections_bad_total 7893
telemt_handshake_timeouts_total 2560
telemt_upstream_connect_attempt_total 7000
telemt_upstream_connect_success_total 6990
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 1348
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1404
telemt_me_idle_close_by_peer_total 1403
telemt_me_route_drop_no_conn_total 141931
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 442
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 288
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_restored_same_endpoint_total 1335
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 242615
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 14216943676 (13.24 GB)
telemt_user_octets_to_client{user="hello"} 138043638904 (128.56 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 92
```