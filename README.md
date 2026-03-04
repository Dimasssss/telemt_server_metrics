# Server Metrics 2026-03-04 01:38:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 16048.5 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105718
telemt_connections_bad_total 1366
telemt_handshake_timeouts_total 596
telemt_upstream_connect_attempt_total 13065
telemt_upstream_connect_success_total 13010
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 13010
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 3435
telemt_me_reconnect_success_total 3435
telemt_me_reader_eof_total 3511
telemt_me_idle_close_by_peer_total 3511
telemt_me_route_drop_no_conn_total 39147
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3511
telemt_me_writer_restored_same_endpoint_total 3415
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 101370
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 783568332 (747.27 MB)
telemt_user_octets_to_client{user="hello"} 30879113120 (28.76 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 16045.2 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49500
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12378
telemt_upstream_connect_attempt_total 34202
telemt_upstream_connect_success_total 33794
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 33788
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 689
telemt_me_reconnect_attempts_total 19944
telemt_me_reconnect_success_total 19932
telemt_me_reader_eof_total 20454
telemt_me_idle_close_by_peer_total 20453
telemt_me_route_drop_no_conn_total 17201
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 20515
telemt_me_writer_restored_same_endpoint_total 19912
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 36434
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 280197428 (267.22 MB)
telemt_user_octets_to_client{user="hello"} 22084898832 (20.57 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 16044.0 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115474
telemt_connections_bad_total 40372
telemt_handshake_timeouts_total 1987
telemt_upstream_connect_attempt_total 17859
telemt_upstream_connect_success_total 17750
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 17750
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 6037
telemt_me_reconnect_success_total 6029
telemt_me_reader_eof_total 6277
telemt_me_idle_close_by_peer_total 6275
telemt_me_route_drop_no_conn_total 22065
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 244
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6278
telemt_me_writer_restored_same_endpoint_total 6008
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 71433
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 435112376 (414.96 MB)
telemt_user_octets_to_client{user="hello"} 17975739808 (16.74 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 16042.8 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52024
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 10206
telemt_upstream_connect_success_total 10167
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10167
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 1444
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 18132
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 119
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_restored_same_endpoint_total 1432
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 50435
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 424234240 (404.58 MB)
telemt_user_octets_to_client{user="hello"} 14938227848 (13.91 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 16041.5 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125806
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 55182
telemt_upstream_connect_attempt_total 24818
telemt_upstream_connect_success_total 24683
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 24683
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 13209
telemt_me_reconnect_success_total 13209
telemt_me_reader_eof_total 14061
telemt_me_idle_close_by_peer_total 14060
telemt_me_route_drop_no_conn_total 38484
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 677
telemt_me_writer_removed_unexpected_total 14066
telemt_me_writer_restored_same_endpoint_total 13185
telemt_me_writer_removed_unexpected_minus_restored_total 881
telemt_user_connections_total{user="hello"} 68218
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 325111576 (310.05 MB)
telemt_user_octets_to_client{user="hello"} 15951299536 (14.86 GB)
telemt_user_unique_ips_current{user="hello"} 15
```