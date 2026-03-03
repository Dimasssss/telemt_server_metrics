# Server Metrics 2026-03-03 23:35:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 8677.5 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67715
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 212
telemt_upstream_connect_attempt_total 5480
telemt_upstream_connect_success_total 5453
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5453
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 852
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 27009
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 846
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 65481
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 566650604 (540.40 MB)
telemt_user_octets_to_client{user="hello"} 20626228256 (19.21 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 8674.1 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31833
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 6508
telemt_upstream_connect_attempt_total 12655
telemt_upstream_connect_success_total 12468
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 12468
telemt_upstream_connect_attempts_per_request{bucket="2"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 5811
telemt_me_reconnect_success_total 5820
telemt_me_reader_eof_total 5912
telemt_me_idle_close_by_peer_total 5911
telemt_me_route_drop_no_conn_total 12209
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 5912
telemt_me_writer_restored_same_endpoint_total 5800
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 24900
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 156793896 (149.53 MB)
telemt_user_octets_to_client{user="hello"} 13329705060 (12.41 GB)
telemt_user_unique_ips_current{user="hello"} 10
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 8672.8 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74033
telemt_connections_bad_total 21092
telemt_handshake_timeouts_total 1782
telemt_upstream_connect_attempt_total 10431
telemt_upstream_connect_success_total 10379
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10379
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4000
telemt_me_reconnect_success_total 4005
telemt_me_reader_eof_total 4178
telemt_me_idle_close_by_peer_total 4177
telemt_me_route_drop_no_conn_total 15986
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 161
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 1
telemt_pool_force_close_total 35
telemt_me_writer_removed_unexpected_total 4179
telemt_me_writer_restored_same_endpoint_total 3984
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 49985
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 323512900 (308.53 MB)
telemt_user_octets_to_client{user="hello"} 13769490920 (12.82 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 8671.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33674
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 485
telemt_upstream_connect_attempt_total 4891
telemt_upstream_connect_success_total 4868
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4868
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 450
telemt_me_reconnect_success_total 464
telemt_me_reader_eof_total 448
telemt_me_idle_close_by_peer_total 448
telemt_me_route_drop_no_conn_total 12838
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 448
telemt_me_writer_restored_same_endpoint_total 445
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 32613
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 253024192 (241.30 MB)
telemt_user_octets_to_client{user="hello"} 9799475004 (9.13 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 8670.4 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78878
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 31047
telemt_upstream_connect_attempt_total 6977
telemt_upstream_connect_success_total 6886
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 6886
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 2001
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 2087
telemt_me_idle_close_by_peer_total 2087
telemt_me_route_drop_no_conn_total 32809
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 2090
telemt_me_writer_restored_same_endpoint_total 1991
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 46429
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 226299388 (215.82 MB)
telemt_user_octets_to_client{user="hello"} 12503068496 (11.64 GB)
telemt_user_unique_ips_current{user="hello"} 20
```