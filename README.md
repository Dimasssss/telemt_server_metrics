# Server Metrics 2026-03-06 09:40:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 4123.2 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114934
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 548
telemt_upstream_connect_attempt_total 1181
telemt_upstream_connect_success_total 1177
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 41058
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 572
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 92578
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 1324171804 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 34128388784 (31.78 GB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 4120.5 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67819
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 29657
telemt_upstream_connect_attempt_total 2028
telemt_upstream_connect_success_total 2028
telemt_upstream_connect_attempts_per_request{bucket="1"} 2028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 934
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 100
telemt_me_reader_eof_total 103
telemt_me_idle_close_by_peer_total 103
telemt_me_route_drop_no_conn_total 14371
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 140
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_removed_unexpected_total 103
telemt_me_writer_restored_same_endpoint_total 100
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 37029
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 585802680 (558.66 MB)
telemt_user_octets_to_client{user="hello"} 11876664640 (11.06 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 4103.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84304
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 10540
telemt_upstream_connect_attempt_total 2092
telemt_upstream_connect_success_total 2075
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 165
telemt_me_reconnect_success_total 156
telemt_me_reader_eof_total 156
telemt_me_idle_close_by_peer_total 155
telemt_me_route_drop_no_conn_total 26607
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 185
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_me_writer_removed_unexpected_total 161
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 70343
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 1282281800 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 18287477132 (17.03 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 4088.4 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65653
telemt_connections_bad_total 3688
telemt_handshake_timeouts_total 11879
telemt_upstream_connect_attempt_total 2216
telemt_upstream_connect_success_total 2198
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 281
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 279
telemt_me_idle_close_by_peer_total 279
telemt_me_route_drop_no_conn_total 23351
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_me_writer_removed_unexpected_total 279
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 48170
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 800227504 (763.16 MB)
telemt_user_octets_to_client{user="hello"} 13548366132 (12.62 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 4030.0 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58048
telemt_connections_bad_total 269
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 2207
telemt_upstream_connect_success_total 2179
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 383
telemt_me_reconnect_success_total 379
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 26837
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 53433
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 918608780 (876.05 MB)
telemt_user_octets_to_client{user="hello"} 24146475492 (22.49 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 68
```