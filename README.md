# Server Metrics 2026-03-03 23:55:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 9905.7 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73692
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 7450
telemt_upstream_connect_success_total 7416
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7416
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 1698
telemt_me_reader_eof_total 1726
telemt_me_idle_close_by_peer_total 1726
telemt_me_route_drop_no_conn_total 29185
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1726
telemt_me_writer_restored_same_endpoint_total 1678
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 71339
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 587547020 (560.33 MB)
telemt_user_octets_to_client{user="hello"} 21717988652 (20.23 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 9902.2 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34706
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 7387
telemt_upstream_connect_attempt_total 15919
telemt_upstream_connect_success_total 15714
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 15714
telemt_upstream_connect_attempts_per_request{bucket="2"} 100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 7863
telemt_me_reconnect_success_total 7870
telemt_me_reader_eof_total 8000
telemt_me_idle_close_by_peer_total 7999
telemt_me_route_drop_no_conn_total 13300
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 8000
telemt_me_writer_restored_same_endpoint_total 7850
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 26867
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 171553260 (163.61 MB)
telemt_user_octets_to_client{user="hello"} 14056264620 (13.09 GB)
telemt_user_unique_ips_current{user="hello"} 11
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 9901.0 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81538
telemt_connections_bad_total 24357
telemt_handshake_timeouts_total 1795
telemt_upstream_connect_attempt_total 11056
telemt_upstream_connect_success_total 10986
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 10986
telemt_upstream_connect_attempts_per_request{bucket="2"} 32
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 4070
telemt_me_reconnect_success_total 4073
telemt_me_reader_eof_total 4251
telemt_me_idle_close_by_peer_total 4250
telemt_me_route_drop_no_conn_total 16794
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4252
telemt_me_writer_restored_same_endpoint_total 4052
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 54186
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 341345764 (325.53 MB)
telemt_user_octets_to_client{user="hello"} 14390155076 (13.40 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 9900.0 (2h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36578
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 6224
telemt_upstream_connect_success_total 6198
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 6198
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 778
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 783
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 13542
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
telemt_me_writer_removed_unexpected_total 783
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 35421
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 354170140 (337.76 MB)
telemt_user_octets_to_client{user="hello"} 10382165032 (9.67 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 9898.7 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87097
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 35175
telemt_upstream_connect_attempt_total 9518
telemt_upstream_connect_success_total 9417
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9417
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 3381
telemt_me_reconnect_success_total 3393
telemt_me_reader_eof_total 3536
telemt_me_idle_close_by_peer_total 3536
telemt_me_route_drop_no_conn_total 33859
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
telemt_me_writer_removed_unexpected_total 3539
telemt_me_writer_restored_same_endpoint_total 3369
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 50340
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 243327036 (232.05 MB)
telemt_user_octets_to_client{user="hello"} 13816714412 (12.87 GB)
telemt_user_unique_ips_current{user="hello"} 12
```