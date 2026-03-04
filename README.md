# Server Metrics 2026-03-04 21:53:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 3629.8 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43564
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 1932
telemt_upstream_connect_success_total 1902
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1902
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 290
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 10325
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 273
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 36973
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 2095414548 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 14663620396 (13.66 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 3624.4 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16638
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 2057
telemt_upstream_connect_success_total 2027
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2027
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 892
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 249
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 4472
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 15302
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 158628120 (151.28 MB)
telemt_user_octets_to_client{user="hello"} 4401101924 (4.10 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 3621.3 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37834
telemt_connections_bad_total 518
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 1111
telemt_upstream_connect_success_total 1097
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1097
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 10756
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 109
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 33956
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 555326068 (529.60 MB)
telemt_user_octets_to_client{user="hello"} 12964704344 (12.07 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 35669.3 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500963
telemt_connections_bad_total 65185
telemt_handshake_timeouts_total 14635
telemt_upstream_connect_attempt_total 15451
telemt_upstream_connect_success_total 15451
telemt_upstream_connect_attempts_per_request{bucket="1"} 15451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 2097
telemt_me_reconnect_success_total 2084
telemt_me_reader_eof_total 2121
telemt_me_idle_close_by_peer_total 2121
telemt_me_route_drop_no_conn_total 173225
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 683
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 12
telemt_pool_force_close_total 397
telemt_me_writer_removed_unexpected_total 2122
telemt_me_writer_restored_same_endpoint_total 2060
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 393129
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 5602206656 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 152088128636 (141.64 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 36028.7 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503160
telemt_connections_bad_total 3757
telemt_handshake_timeouts_total 5551
telemt_upstream_connect_attempt_total 21472
telemt_upstream_connect_success_total 21360
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 21360
telemt_upstream_connect_attempts_per_request{bucket="2"} 46
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4559
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 223954
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4714
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 454149
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 7073645848 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 145512364816 (135.52 GB)
telemt_user_unique_ips_current{user="hello"} 21
```