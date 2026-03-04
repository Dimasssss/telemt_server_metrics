# Server Metrics 2026-03-04 01:53:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 16969.5 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110887
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 919
telemt_upstream_connect_attempt_total 14403
telemt_upstream_connect_success_total 14342
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14342
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 3919
telemt_me_reconnect_success_total 3915
telemt_me_reader_eof_total 4007
telemt_me_idle_close_by_peer_total 4007
telemt_me_route_drop_no_conn_total 40378
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 4007
telemt_me_writer_restored_same_endpoint_total 3895
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 106076
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 847623484 (808.36 MB)
telemt_user_octets_to_client{user="hello"} 32380620048 (30.16 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 16966.2 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51785
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 13018
telemt_upstream_connect_attempt_total 37324
telemt_upstream_connect_success_total 36909
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 36903
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 720
telemt_me_reconnect_attempts_total 22122
telemt_me_reconnect_success_total 22106
telemt_me_reader_eof_total 22686
telemt_me_idle_close_by_peer_total 22685
telemt_me_route_drop_no_conn_total 17712
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 22747
telemt_me_writer_restored_same_endpoint_total 22086
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 38003
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 291051404 (277.57 MB)
telemt_user_octets_to_client{user="hello"} 22297821584 (20.77 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 16965.0 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121413
telemt_connections_bad_total 42759
telemt_handshake_timeouts_total 2339
telemt_upstream_connect_attempt_total 19069
telemt_upstream_connect_success_total 18955
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 18955
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6411
telemt_me_reconnect_success_total 6402
telemt_me_reader_eof_total 6668
telemt_me_idle_close_by_peer_total 6666
telemt_me_route_drop_no_conn_total 22741
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 252
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6669
telemt_me_writer_restored_same_endpoint_total 6381
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 73894
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 447964528 (427.21 MB)
telemt_user_octets_to_client{user="hello"} 18434448596 (17.17 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 16963.9 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54575
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 541
telemt_upstream_connect_attempt_total 10677
telemt_upstream_connect_success_total 10628
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 10628
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 1499
telemt_me_reconnect_success_total 1506
telemt_me_reader_eof_total 1511
telemt_me_idle_close_by_peer_total 1511
telemt_me_route_drop_no_conn_total 18943
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 120
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 52895
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 438835136 (418.51 MB)
telemt_user_octets_to_client{user="hello"} 17584101840 (16.38 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 16962.6 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131662
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 58238
telemt_upstream_connect_attempt_total 25353
telemt_upstream_connect_success_total 25193
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 25193
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 13294
telemt_me_reconnect_success_total 13294
telemt_me_reader_eof_total 14148
telemt_me_idle_close_by_peer_total 14147
telemt_me_route_drop_no_conn_total 39185
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1370
telemt_me_writer_removed_unexpected_total 14153
telemt_me_writer_restored_same_endpoint_total 13270
telemt_me_writer_removed_unexpected_minus_restored_total 883
telemt_user_connections_total{user="hello"} 70913
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 356784112 (340.26 MB)
telemt_user_octets_to_client{user="hello"} 16284239496 (15.17 GB)
telemt_user_unique_ips_current{user="hello"} 20
```