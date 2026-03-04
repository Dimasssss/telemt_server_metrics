# Server Metrics 2026-03-04 01:02:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 13899.0 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95798
telemt_connections_bad_total 687
telemt_handshake_timeouts_total 515
telemt_upstream_connect_attempt_total 10595
telemt_upstream_connect_success_total 10544
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 10544
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 2727
telemt_me_reconnect_success_total 2729
telemt_me_reader_eof_total 2789
telemt_me_idle_close_by_peer_total 2789
telemt_me_route_drop_no_conn_total 36033
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2789
telemt_me_writer_restored_same_endpoint_total 2709
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 92326
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 707217540 (674.46 MB)
telemt_user_octets_to_client{user="hello"} 28042723668 (26.12 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 13895.8 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44892
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 10797
telemt_upstream_connect_attempt_total 27377
telemt_upstream_connect_success_total 27019
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 27013
telemt_upstream_connect_attempts_per_request{bucket="2"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 633
telemt_me_reconnect_attempts_total 15334
telemt_me_reconnect_success_total 15325
telemt_me_reader_eof_total 15685
telemt_me_idle_close_by_peer_total 15684
telemt_me_route_drop_no_conn_total 16244
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 15746
telemt_me_writer_restored_same_endpoint_total 15305
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 33455
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 216675404 (206.64 MB)
telemt_user_octets_to_client{user="hello"} 20006908716 (18.63 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 13894.6 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103849
telemt_connections_bad_total 34780
telemt_handshake_timeouts_total 1929
telemt_upstream_connect_attempt_total 16163
telemt_upstream_connect_success_total 16074
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 16074
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 5692
telemt_me_reconnect_success_total 5687
telemt_me_reader_eof_total 5919
telemt_me_idle_close_by_peer_total 5917
telemt_me_route_drop_no_conn_total 20563
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 5920
telemt_me_writer_restored_same_endpoint_total 5666
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 65856
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 402108080 (383.48 MB)
telemt_user_octets_to_client{user="hello"} 16675076992 (15.53 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 13893.5 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46124
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 8910
telemt_upstream_connect_success_total 8875
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 8875
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 1319
telemt_me_reader_eof_total 1320
telemt_me_idle_close_by_peer_total 1320
telemt_me_route_drop_no_conn_total 16225
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 14
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_restored_same_endpoint_total 1299
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 44671
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 400087388 (381.55 MB)
telemt_user_octets_to_client{user="hello"} 11493830092 (10.70 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 13892.3 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112097
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 48253
telemt_upstream_connect_attempt_total 19895
telemt_upstream_connect_success_total 19770
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 19770
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9949
telemt_me_reconnect_success_total 9953
telemt_me_reader_eof_total 10568
telemt_me_idle_close_by_peer_total 10567
telemt_me_route_drop_no_conn_total 36763
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 10574
telemt_me_writer_restored_same_endpoint_total 9929
telemt_me_writer_removed_unexpected_minus_restored_total 645
telemt_user_connections_total{user="hello"} 61628
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 298990168 (285.14 MB)
telemt_user_octets_to_client{user="hello"} 15189433668 (14.15 GB)
telemt_user_unique_ips_current{user="hello"} 14
```