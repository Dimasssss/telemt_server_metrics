# Server Metrics 2026-03-03 23:04:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 6835.3 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56981
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 3510
telemt_upstream_connect_success_total 3487
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3487
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 391
telemt_me_reconnect_success_total 402
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 21962
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 102
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_restored_same_endpoint_total 382
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 54972
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 497835928 (474.77 MB)
telemt_user_octets_to_client{user="hello"} 18593733968 (17.32 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 6831.9 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26390
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 5206
telemt_upstream_connect_attempt_total 8335
telemt_upstream_connect_success_total 8162
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 8162
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 3295
telemt_me_reconnect_success_total 3306
telemt_me_reader_eof_total 3351
telemt_me_idle_close_by_peer_total 3350
telemt_me_route_drop_no_conn_total 9851
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 3351
telemt_me_writer_restored_same_endpoint_total 3286
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 20829
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 122926876 (117.23 MB)
telemt_user_octets_to_client{user="hello"} 9132949940 (8.51 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 6830.7 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63675
telemt_connections_bad_total 18594
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 7055
telemt_upstream_connect_success_total 7013
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7013
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 2150
telemt_me_reconnect_success_total 2158
telemt_me_reader_eof_total 2242
telemt_me_idle_close_by_peer_total 2241
telemt_me_route_drop_no_conn_total 13329
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 2243
telemt_me_writer_restored_same_endpoint_total 2137
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 42236
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 296643260 (282.90 MB)
telemt_user_octets_to_client{user="hello"} 12966510328 (12.08 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 6829.6 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27794
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 448
telemt_upstream_connect_attempt_total 3796
telemt_upstream_connect_success_total 3775
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3775
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 340
telemt_me_reconnect_success_total 355
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 10650
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 26904
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 213839368 (203.93 MB)
telemt_user_octets_to_client{user="hello"} 8760293232 (8.16 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 6828.4 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62419
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 22766
telemt_upstream_connect_attempt_total 4158
telemt_upstream_connect_success_total 4106
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4106
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 865
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 889
telemt_me_idle_close_by_peer_total 889
telemt_me_route_drop_no_conn_total 30127
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 38595
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 197708264 (188.55 MB)
telemt_user_octets_to_client{user="hello"} 9497873704 (8.85 GB)
telemt_user_unique_ips_current{user="hello"} 26
```