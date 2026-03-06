# Server Metrics 2026-03-06 09:45:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 4430.6 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124899
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 576
telemt_upstream_connect_attempt_total 1296
telemt_upstream_connect_success_total 1290
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 49044
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 618
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 100073
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 1453952952 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 38780370692 (36.12 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 4427.9 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70603
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 29715
telemt_upstream_connect_attempt_total 2262
telemt_upstream_connect_success_total 2262
telemt_upstream_connect_attempts_per_request{bucket="1"} 2262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1040
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 129
telemt_me_reconnect_success_total 125
telemt_me_reader_eof_total 128
telemt_me_idle_close_by_peer_total 128
telemt_me_route_drop_no_conn_total 15467
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 161
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_restored_same_endpoint_total 125
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 39716
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 635523292 (606.08 MB)
telemt_user_octets_to_client{user="hello"} 12389620080 (11.54 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 4411.2 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90206
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 11185
telemt_upstream_connect_attempt_total 2329
telemt_upstream_connect_success_total 2313
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 210
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 201
telemt_me_idle_close_by_peer_total 200
telemt_me_route_drop_no_conn_total 28376
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 203
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 206
telemt_me_writer_restored_same_endpoint_total 200
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 75537
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 1330169864 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 19686487296 (18.33 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 4395.6 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69382
telemt_connections_bad_total 3994
telemt_handshake_timeouts_total 12039
telemt_upstream_connect_attempt_total 2578
telemt_upstream_connect_success_total 2560
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 423
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 421
telemt_me_route_drop_no_conn_total 24621
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_me_writer_removed_unexpected_total 421
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 51351
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 829455988 (791.03 MB)
telemt_user_octets_to_client{user="hello"} 14641498088 (13.64 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 4337.3 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61742
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 2468
telemt_upstream_connect_success_total 2440
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 28931
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 105
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_removed_unexpected_total 476
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 57002
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 961166444 (916.64 MB)
telemt_user_octets_to_client{user="hello"} 26333483408 (24.52 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 81
```