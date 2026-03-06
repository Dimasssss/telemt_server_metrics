# Server Metrics 2026-03-06 02:55:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 16461.6 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110811
telemt_connections_bad_total 15905
telemt_handshake_timeouts_total 1453
telemt_upstream_connect_attempt_total 15290
telemt_upstream_connect_success_total 15154
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 15154
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 4540
telemt_me_reconnect_success_total 4520
telemt_me_reader_eof_total 4670
telemt_me_idle_close_by_peer_total 4670
telemt_me_route_drop_no_conn_total 29669
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 320
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 4670
telemt_me_writer_restored_same_endpoint_total 4514
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 88163
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 1042469016 (994.18 MB)
telemt_user_octets_to_client{user="hello"} 35299288196 (32.88 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 16457.0 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36513
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 458
telemt_upstream_connect_attempt_total 11851
telemt_upstream_connect_success_total 11849
telemt_upstream_connect_attempts_per_request{bucket="1"} 11849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 1830
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1839
telemt_me_idle_close_by_peer_total 1839
telemt_me_route_drop_no_conn_total 10923
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 107
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1840
telemt_me_writer_restored_same_endpoint_total 1815
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 35400
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 236180712 (225.24 MB)
telemt_user_octets_to_client{user="hello"} 8751498936 (8.15 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 16454.4 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66800
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 1184
telemt_upstream_connect_attempt_total 14886
telemt_upstream_connect_success_total 14760
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 14760
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 4243
telemt_me_reconnect_success_total 4228
telemt_me_reader_eof_total 4426
telemt_me_idle_close_by_peer_total 4426
telemt_me_route_drop_no_conn_total 18354
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 151
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4427
telemt_me_writer_restored_same_endpoint_total 4221
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 62429
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 644757808 (614.89 MB)
telemt_user_octets_to_client{user="hello"} 21786119876 (20.29 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 16450.9 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52493
telemt_connections_bad_total 269
telemt_handshake_timeouts_total 3015
telemt_upstream_connect_attempt_total 10786
telemt_upstream_connect_success_total 10751
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 10751
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 2156
telemt_me_reader_eof_total 2251
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 20638
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2251
telemt_me_writer_restored_same_endpoint_total 2149
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 46354
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 411555664 (392.49 MB)
telemt_user_octets_to_client{user="hello"} 22434479460 (20.89 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 16449.9 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65347
telemt_connections_bad_total 587
telemt_handshake_timeouts_total 441
telemt_upstream_connect_attempt_total 9759
telemt_upstream_connect_success_total 9736
telemt_upstream_connect_attempts_per_request{bucket="1"} 9736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 1060
telemt_me_reconnect_success_total 1056
telemt_me_reader_eof_total 1077
telemt_me_idle_close_by_peer_total 1077
telemt_me_route_drop_no_conn_total 20154
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1077
telemt_me_writer_restored_same_endpoint_total 1050
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 63356
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 12020667556 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 27016433884 (25.16 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```