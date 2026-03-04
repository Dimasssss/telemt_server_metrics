# Server Metrics 2026-03-04 00:00:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 10212.6 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75077
telemt_connections_bad_total 660
telemt_handshake_timeouts_total 227
telemt_upstream_connect_attempt_total 8073
telemt_upstream_connect_success_total 8032
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 8032
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 2004
telemt_me_reconnect_success_total 2009
telemt_me_reader_eof_total 2046
telemt_me_idle_close_by_peer_total 2046
telemt_me_route_drop_no_conn_total 29829
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 2046
telemt_me_writer_restored_same_endpoint_total 1989
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 72695
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 598000720 (570.30 MB)
telemt_user_octets_to_client{user="hello"} 22325311688 (20.79 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 10209.4 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35369
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 7602
telemt_upstream_connect_attempt_total 16863
telemt_upstream_connect_success_total 16642
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 16642
telemt_upstream_connect_attempts_per_request{bucket="2"} 107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 8460
telemt_me_reconnect_success_total 8467
telemt_me_reader_eof_total 8604
telemt_me_idle_close_by_peer_total 8603
telemt_me_route_drop_no_conn_total 13603
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 8604
telemt_me_writer_restored_same_endpoint_total 8447
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 27308
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 173023820 (165.01 MB)
telemt_user_octets_to_client{user="hello"} 14089465076 (13.12 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 10208.2 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83283
telemt_connections_bad_total 25150
telemt_handshake_timeouts_total 1798
telemt_upstream_connect_attempt_total 11362
telemt_upstream_connect_success_total 11290
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11290
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 4130
telemt_me_reconnect_success_total 4133
telemt_me_reader_eof_total 4312
telemt_me_idle_close_by_peer_total 4311
telemt_me_route_drop_no_conn_total 17032
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 183
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4313
telemt_me_writer_restored_same_endpoint_total 4112
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 55125
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 344295152 (328.35 MB)
telemt_user_octets_to_client{user="hello"} 14437552796 (13.45 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 10207.1 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37248
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 498
telemt_upstream_connect_attempt_total 6652
telemt_upstream_connect_success_total 6625
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6625
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 905
telemt_me_reconnect_success_total 918
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 13822
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 36063
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 361437740 (344.69 MB)
telemt_user_octets_to_client{user="hello"} 10590577308 (9.86 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 10205.7 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89138
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 36233
telemt_upstream_connect_attempt_total 10255
telemt_upstream_connect_success_total 10152
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10152
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 3801
telemt_me_reconnect_success_total 3813
telemt_me_reader_eof_total 3983
telemt_me_idle_close_by_peer_total 3983
telemt_me_route_drop_no_conn_total 34069
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 3986
telemt_me_writer_restored_same_endpoint_total 3789
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 51265
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 245185016 (233.83 MB)
telemt_user_octets_to_client{user="hello"} 13877411132 (12.92 GB)
telemt_user_unique_ips_current{user="hello"} 11
```