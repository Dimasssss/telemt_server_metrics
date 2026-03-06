# Server Metrics 2026-03-06 09:56:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 5045.0 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140550
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 1600
telemt_upstream_connect_success_total 1592
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 32
telemt_me_reconnect_success_total 28
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 59868
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 753
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 113232
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 1755617624 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 47914128768 (44.62 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 5042.2 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76104
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 29777
telemt_upstream_connect_attempt_total 2883
telemt_upstream_connect_success_total 2883
telemt_upstream_connect_attempts_per_request{bucket="1"} 2883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1322
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 17626
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 200
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 45047
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 760333400 (725.11 MB)
telemt_user_octets_to_client{user="hello"} 13679258852 (12.74 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 5025.6 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101811
telemt_connections_bad_total 414
telemt_handshake_timeouts_total 11563
telemt_upstream_connect_attempt_total 2923
telemt_upstream_connect_success_total 2905
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 368
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 364
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 32035
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 369
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 86494
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 1437186520 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 23096572156 (21.51 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 5010.0 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77986
telemt_connections_bad_total 4547
telemt_handshake_timeouts_total 12570
telemt_upstream_connect_attempt_total 2916
telemt_upstream_connect_success_total 2896
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 510
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 511
telemt_me_idle_close_by_peer_total 511
telemt_me_route_drop_no_conn_total 27975
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 163
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 511
telemt_me_writer_restored_same_endpoint_total 502
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 58366
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 891420792 (850.13 MB)
telemt_user_octets_to_client{user="hello"} 17188228580 (16.01 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 4951.7 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69744
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 3083
telemt_upstream_connect_success_total 3051
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 650
telemt_me_reconnect_success_total 645
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 33166
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 111
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_me_writer_removed_unexpected_total 662
telemt_me_writer_restored_same_endpoint_total 640
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 64814
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 1084251504 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 30369992444 (28.28 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 89
```