# Server Metrics 2026-03-04 02:54:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 20654.8 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130311
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 16670
telemt_upstream_connect_success_total 16599
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16599
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 4217
telemt_me_reconnect_success_total 4208
telemt_me_reader_eof_total 4306
telemt_me_idle_close_by_peer_total 4306
telemt_me_route_drop_no_conn_total 46441
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 239
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4306
telemt_me_writer_restored_same_endpoint_total 4188
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 124934
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 1087154608 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 37192098396 (34.64 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 20651.5 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61402
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 15934
telemt_upstream_connect_attempt_total 50131
telemt_upstream_connect_success_total 49607
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 49601
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 852
telemt_me_reconnect_attempts_total 31029
telemt_me_reconnect_success_total 31009
telemt_me_reader_eof_total 31816
telemt_me_idle_close_by_peer_total 31815
telemt_me_route_drop_no_conn_total 20361
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 91
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 31877
telemt_me_writer_restored_same_endpoint_total 30989
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 44471
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 350091748 (333.87 MB)
telemt_user_octets_to_client{user="hello"} 24098338888 (22.44 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 20650.2 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144924
telemt_connections_bad_total 52432
telemt_handshake_timeouts_total 3285
telemt_upstream_connect_attempt_total 25339
telemt_upstream_connect_success_total 25160
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 25160
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 9154
telemt_me_reconnect_success_total 9135
telemt_me_reader_eof_total 9521
telemt_me_idle_close_by_peer_total 9519
telemt_me_route_drop_no_conn_total 28126
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
telemt_me_writer_removed_unexpected_total 9523
telemt_me_writer_restored_same_endpoint_total 9114
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 85850
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 521878544 (497.70 MB)
telemt_user_octets_to_client{user="hello"} 20704358488 (19.28 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 20649.1 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65256
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 652
telemt_upstream_connect_attempt_total 13295
telemt_upstream_connect_success_total 13230
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 13230
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 1866
telemt_me_reconnect_success_total 1870
telemt_me_reader_eof_total 1877
telemt_me_idle_close_by_peer_total 1877
telemt_me_route_drop_no_conn_total 22562
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
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_restored_same_endpoint_total 1850
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 63283
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 516317640 (492.40 MB)
telemt_user_octets_to_client{user="hello"} 22343376048 (20.81 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 20647.8 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156721
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 71035
telemt_upstream_connect_attempt_total 30191
telemt_upstream_connect_success_total 30009
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 30009
telemt_upstream_connect_attempts_per_request{bucket="2"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 405
telemt_me_reconnect_attempts_total 14976
telemt_me_reconnect_success_total 14973
telemt_me_reader_eof_total 15896
telemt_me_idle_close_by_peer_total 15895
telemt_me_route_drop_no_conn_total 42645
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
telemt_pool_stale_pick_total 2320
telemt_me_writer_removed_unexpected_total 15901
telemt_me_writer_restored_same_endpoint_total 14949
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 82602
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 472955488 (451.05 MB)
telemt_user_octets_to_client{user="hello"} 18499589740 (17.23 GB)
telemt_user_unique_ips_current{user="hello"} 14
```