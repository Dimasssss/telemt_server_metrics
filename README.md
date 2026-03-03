# Server Metrics 2026-03-03 23:45:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 9291.6 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70986
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 6391
telemt_upstream_connect_success_total 6357
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6357
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 28213
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1190
telemt_me_writer_restored_same_endpoint_total 1162
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 68691
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 578453936 (551.66 MB)
telemt_user_octets_to_client{user="hello"} 21115203844 (19.67 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 9288.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33309
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 6956
telemt_upstream_connect_attempt_total 14251
telemt_upstream_connect_success_total 14048
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 14048
telemt_upstream_connect_attempts_per_request{bucket="2"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 6786
telemt_me_reconnect_success_total 6792
telemt_me_reader_eof_total 6913
telemt_me_idle_close_by_peer_total 6912
telemt_me_route_drop_no_conn_total 12863
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 6913
telemt_me_writer_restored_same_endpoint_total 6772
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 25912
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 160993852 (153.54 MB)
telemt_user_octets_to_client{user="hello"} 13654931888 (12.72 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 9287.0 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77871
telemt_connections_bad_total 22736
telemt_handshake_timeouts_total 1786
telemt_upstream_connect_attempt_total 10653
telemt_upstream_connect_success_total 10587
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 10587
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 4000
telemt_me_reconnect_success_total 4005
telemt_me_reader_eof_total 4178
telemt_me_idle_close_by_peer_total 4177
telemt_me_route_drop_no_conn_total 16354
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 170
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4179
telemt_me_writer_restored_same_endpoint_total 3984
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 52161
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 336067300 (320.50 MB)
telemt_user_octets_to_client{user="hello"} 14066732840 (13.10 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 9286.0 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35245
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 488
telemt_upstream_connect_attempt_total 5510
telemt_upstream_connect_success_total 5484
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 5484
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 13217
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 569
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 34138
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 349076848 (332.91 MB)
telemt_user_octets_to_client{user="hello"} 9932311856 (9.25 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 9284.7 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83138
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 33141
telemt_upstream_connect_attempt_total 8194
telemt_upstream_connect_success_total 8092
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8092
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 2614
telemt_me_reconnect_success_total 2626
telemt_me_reader_eof_total 2737
telemt_me_idle_close_by_peer_total 2737
telemt_me_route_drop_no_conn_total 33480
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 43
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 2740
telemt_me_writer_restored_same_endpoint_total 2602
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 48505
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 233355780 (222.55 MB)
telemt_user_octets_to_client{user="hello"} 12732882060 (11.86 GB)
telemt_user_unique_ips_current{user="hello"} 15
```