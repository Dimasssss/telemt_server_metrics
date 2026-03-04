# Server Metrics 2026-03-04 00:52:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 13284.9 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92775
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 497
telemt_upstream_connect_attempt_total 10132
telemt_upstream_connect_success_total 10083
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 10083
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 2705
telemt_me_reconnect_success_total 2708
telemt_me_reader_eof_total 2765
telemt_me_idle_close_by_peer_total 2765
telemt_me_route_drop_no_conn_total 34870
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2765
telemt_me_writer_restored_same_endpoint_total 2688
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 89384
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 694559132 (662.38 MB)
telemt_user_octets_to_client{user="hello"} 27159201392 (25.29 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 13281.5 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43305
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 9911
telemt_upstream_connect_attempt_total 25415
telemt_upstream_connect_success_total 25073
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 25067
telemt_upstream_connect_attempts_per_request{bucket="2"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 619
telemt_me_reconnect_attempts_total 14035
telemt_me_reconnect_success_total 14028
telemt_me_reader_eof_total 14349
telemt_me_idle_close_by_peer_total 14348
telemt_me_route_drop_no_conn_total 15802
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 14411
telemt_me_writer_restored_same_endpoint_total 14008
telemt_me_writer_removed_unexpected_minus_restored_total 403
telemt_user_connections_total{user="hello"} 32752
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 211673928 (201.87 MB)
telemt_user_octets_to_client{user="hello"} 19035424096 (17.73 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 13280.2 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99978
telemt_connections_bad_total 33182
telemt_handshake_timeouts_total 1901
telemt_upstream_connect_attempt_total 15471
telemt_upstream_connect_success_total 15384
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 15384
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 5450
telemt_me_reconnect_success_total 5446
telemt_me_reader_eof_total 5669
telemt_me_idle_close_by_peer_total 5667
telemt_me_route_drop_no_conn_total 19509
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 5670
telemt_me_writer_restored_same_endpoint_total 5425
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 63629
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 390079252 (372.01 MB)
telemt_user_octets_to_client{user="hello"} 16110015108 (15.00 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 13279.1 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44465
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 522
telemt_upstream_connect_attempt_total 8645
telemt_upstream_connect_success_total 8614
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8614
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 1299
telemt_me_reconnect_success_total 1310
telemt_me_reader_eof_total 1309
telemt_me_idle_close_by_peer_total 1309
telemt_me_route_drop_no_conn_total 15656
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 43054
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 394498136 (376.22 MB)
telemt_user_octets_to_client{user="hello"} 11259632484 (10.49 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 13277.8 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108465
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 46269
telemt_upstream_connect_attempt_total 18119
telemt_upstream_connect_success_total 18003
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18003
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 8771
telemt_me_reconnect_success_total 8775
telemt_me_reader_eof_total 9309
telemt_me_idle_close_by_peer_total 9308
telemt_me_route_drop_no_conn_total 36207
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 9314
telemt_me_writer_restored_same_endpoint_total 8751
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 60044
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 294415844 (280.78 MB)
telemt_user_octets_to_client{user="hello"} 14935978344 (13.91 GB)
telemt_user_unique_ips_current{user="hello"} 21
```