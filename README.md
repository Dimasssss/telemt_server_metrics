# Server Metrics 2026-03-04 02:49:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 20347.6 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128642
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 16432
telemt_upstream_connect_success_total 16361
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16361
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 4178
telemt_me_reconnect_success_total 4170
telemt_me_reader_eof_total 4267
telemt_me_idle_close_by_peer_total 4267
telemt_me_route_drop_no_conn_total 45952
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 237
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4267
telemt_me_writer_restored_same_endpoint_total 4150
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 123336
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1062567948 (1013.34 MB)
telemt_user_octets_to_client{user="hello"} 36734915816 (34.21 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 20344.3 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60580
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 15721
telemt_upstream_connect_attempt_total 49092
telemt_upstream_connect_success_total 48568
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 48562
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 30288
telemt_me_reconnect_success_total 30268
telemt_me_reader_eof_total 31070
telemt_me_idle_close_by_peer_total 31069
telemt_me_route_drop_no_conn_total 19982
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 31131
telemt_me_writer_restored_same_endpoint_total 30248
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 43870
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 342683944 (326.81 MB)
telemt_user_octets_to_client{user="hello"} 23883310412 (22.24 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 20343.1 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142957
telemt_connections_bad_total 51645
telemt_handshake_timeouts_total 3279
telemt_upstream_connect_attempt_total 24660
telemt_upstream_connect_success_total 24480
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 24480
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 8755
telemt_me_reconnect_success_total 8735
telemt_me_reader_eof_total 9109
telemt_me_idle_close_by_peer_total 9107
telemt_me_route_drop_no_conn_total 27639
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 9111
telemt_me_writer_restored_same_endpoint_total 8714
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 84678
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 513870520 (490.07 MB)
telemt_user_octets_to_client{user="hello"} 20594074076 (19.18 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 20342.1 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64361
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 650
telemt_upstream_connect_attempt_total 12968
telemt_upstream_connect_success_total 12903
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 12903
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1796
telemt_me_idle_close_by_peer_total 1796
telemt_me_route_drop_no_conn_total 22304
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1796
telemt_me_writer_restored_same_endpoint_total 1769
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 62393
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 512093072 (488.37 MB)
telemt_user_octets_to_client{user="hello"} 21861157832 (20.36 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 20340.5 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154660
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 69945
telemt_upstream_connect_attempt_total 29726
telemt_upstream_connect_success_total 29544
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 29544
telemt_upstream_connect_attempts_per_request{bucket="2"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 14790
telemt_me_reconnect_success_total 14787
telemt_me_reader_eof_total 15710
telemt_me_idle_close_by_peer_total 15709
telemt_me_route_drop_no_conn_total 42455
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2271
telemt_me_writer_removed_unexpected_total 15715
telemt_me_writer_restored_same_endpoint_total 14763
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 81648
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 469617376 (447.86 MB)
telemt_user_octets_to_client{user="hello"} 18300413408 (17.04 GB)
telemt_user_unique_ips_current{user="hello"} 17
```