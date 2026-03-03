# Server Metrics 2026-03-03 21:42:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 1921.1 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20981
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 593
telemt_upstream_connect_success_total 586
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 586
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 8790
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 28
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 7
telemt_me_writer_restored_same_endpoint_total 7
telemt_user_connections_total{user="hello"} 20079
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 191817944 (182.93 MB)
telemt_user_octets_to_client{user="hello"} 10008671932 (9.32 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 1917.6 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8429
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 1215
telemt_upstream_connect_attempt_total 646
telemt_upstream_connect_success_total 573
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 573
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 3315
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 7056
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 31941176 (30.46 MB)
telemt_user_octets_to_client{user="hello"} 1968132564 (1.83 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 1916.5 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20781
telemt_connections_bad_total 5252
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 659
telemt_upstream_connect_success_total 644
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 644
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 28
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 4256
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 66
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 14774
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 127933712 (122.01 MB)
telemt_user_octets_to_client{user="hello"} 7163748092 (6.67 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 1915.5 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9126
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 734
telemt_upstream_connect_success_total 725
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 725
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 4379
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 8814
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 75868212 (72.35 MB)
telemt_user_octets_to_client{user="hello"} 2019082776 (1.88 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 1914.2 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21638
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 5177
telemt_upstream_connect_attempt_total 635
telemt_upstream_connect_success_total 612
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 612
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 45
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 21262
telemt_me_single_endpoint_shadow_rotate_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 16052
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 61757484 (58.90 MB)
telemt_user_octets_to_client{user="hello"} 2154244344 (2.01 GB)
telemt_user_unique_ips_current{user="hello"} 27
```