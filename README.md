# Server Metrics 2026-03-04 00:26:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 11747.8 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84196
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 360
telemt_upstream_connect_attempt_total 9502
telemt_upstream_connect_success_total 9459
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 9459
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 32694
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 137
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2756
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 81313
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 645369928 (615.47 MB)
telemt_user_octets_to_client{user="hello"} 25341157780 (23.60 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 11744.6 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39111
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 8646
telemt_upstream_connect_attempt_total 21015
telemt_upstream_connect_success_total 20712
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 20706
telemt_upstream_connect_attempts_per_request{bucket="2"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 587
telemt_me_reconnect_attempts_total 11117
telemt_me_reconnect_success_total 11114
telemt_me_reader_eof_total 11344
telemt_me_idle_close_by_peer_total 11343
telemt_me_route_drop_no_conn_total 14888
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 11406
telemt_me_writer_restored_same_endpoint_total 11094
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 29897
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 185237348 (176.66 MB)
telemt_user_octets_to_client{user="hello"} 14772568624 (13.76 GB)
telemt_user_unique_ips_current{user="hello"} 10
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 11743.5 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91385
telemt_connections_bad_total 29154
telemt_handshake_timeouts_total 1842
telemt_upstream_connect_attempt_total 13201
telemt_upstream_connect_success_total 13127
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13127
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 4631
telemt_me_reconnect_success_total 4631
telemt_me_reader_eof_total 4821
telemt_me_idle_close_by_peer_total 4820
telemt_me_route_drop_no_conn_total 18131
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 215
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4822
telemt_me_writer_restored_same_endpoint_total 4610
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 59153
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 361730728 (344.97 MB)
telemt_user_octets_to_client{user="hello"} 15323488788 (14.27 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 11742.2 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40696
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 508
telemt_upstream_connect_attempt_total 7934
telemt_upstream_connect_success_total 7905
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 7905
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 1258
telemt_me_reconnect_success_total 1270
telemt_me_reader_eof_total 1269
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 14837
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 3
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 1269
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 39410
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 380250332 (362.63 MB)
telemt_user_octets_to_client{user="hello"} 10907726092 (10.16 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 11740.9 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98664
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 41261
telemt_upstream_connect_attempt_total 14047
telemt_upstream_connect_success_total 13937
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13937
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 6162
telemt_me_reconnect_success_total 6171
telemt_me_reader_eof_total 6547
telemt_me_idle_close_by_peer_total 6547
telemt_me_route_drop_no_conn_total 35240
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 6551
telemt_me_writer_restored_same_endpoint_total 6147
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 55531
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 274701856 (261.98 MB)
telemt_user_octets_to_client{user="hello"} 14408212652 (13.42 GB)
telemt_user_unique_ips_current{user="hello"} 13
```