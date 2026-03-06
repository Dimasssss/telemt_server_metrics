# Server Metrics 2026-03-06 03:26:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 18304.3 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125951
telemt_connections_bad_total 15919
telemt_handshake_timeouts_total 2614
telemt_upstream_connect_attempt_total 19059
telemt_upstream_connect_success_total 18891
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 18891
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 6579
telemt_me_reconnect_success_total 6556
telemt_me_reader_eof_total 6774
telemt_me_idle_close_by_peer_total 6774
telemt_me_route_drop_no_conn_total 34062
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 329
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 6774
telemt_me_writer_restored_same_endpoint_total 6550
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 100334
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 1326780880 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 39173038320 (36.48 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 18299.8 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41693
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 558
telemt_upstream_connect_attempt_total 14102
telemt_upstream_connect_success_total 14100
telemt_upstream_connect_attempts_per_request{bucket="1"} 14100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 2385
telemt_me_reconnect_success_total 2375
telemt_me_reader_eof_total 2402
telemt_me_idle_close_by_peer_total 2402
telemt_me_route_drop_no_conn_total 12294
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2403
telemt_me_writer_restored_same_endpoint_total 2369
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 40363
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 290205404 (276.76 MB)
telemt_user_octets_to_client{user="hello"} 10040867672 (9.35 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 18297.1 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75025
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 1580
telemt_upstream_connect_attempt_total 17558
telemt_upstream_connect_success_total 17411
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 17411
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 5266
telemt_me_reconnect_success_total 5248
telemt_me_reader_eof_total 5484
telemt_me_idle_close_by_peer_total 5484
telemt_me_route_drop_no_conn_total 20779
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 5488
telemt_me_writer_restored_same_endpoint_total 5241
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 70097
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 686745320 (654.93 MB)
telemt_user_octets_to_client{user="hello"} 24234034320 (22.57 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 18293.9 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60543
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 3969
telemt_upstream_connect_attempt_total 12541
telemt_upstream_connect_success_total 12504
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 12504
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 2599
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 2684
telemt_me_idle_close_by_peer_total 2684
telemt_me_route_drop_no_conn_total 22596
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2684
telemt_me_writer_restored_same_endpoint_total 2575
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 52981
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 509128880 (485.54 MB)
telemt_user_octets_to_client{user="hello"} 24382861380 (22.71 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 18292.8 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73415
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 509
telemt_upstream_connect_attempt_total 11428
telemt_upstream_connect_success_total 11404
telemt_upstream_connect_attempts_per_request{bucket="1"} 11404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 1362
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 23331
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_restored_same_endpoint_total 1351
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 70952
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 12128696956 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 40787590200 (37.99 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```