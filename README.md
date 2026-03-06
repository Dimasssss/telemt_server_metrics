# Server Metrics 2026-03-06 01:28:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 11240.1 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75900
telemt_connections_bad_total 15876
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 9892
telemt_upstream_connect_success_total 9803
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 9803
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 2735
telemt_me_reader_eof_total 2845
telemt_me_idle_close_by_peer_total 2845
telemt_me_route_drop_no_conn_total 18186
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 135
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 2
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 2845
telemt_me_writer_restored_same_endpoint_total 2730
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 57771
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 659660888 (629.10 MB)
telemt_user_octets_to_client{user="hello"} 22097782420 (20.58 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 11235.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25078
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 340
telemt_upstream_connect_attempt_total 8987
telemt_upstream_connect_success_total 8985
telemt_upstream_connect_attempts_per_request{bucket="1"} 8985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 1661
telemt_me_reconnect_success_total 1653
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 6990
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 50
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 4
telemt_pool_force_close_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 24271
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 164927496 (157.29 MB)
telemt_user_octets_to_client{user="hello"} 5678357872 (5.29 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 11233.0 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44525
telemt_connections_bad_total 322
telemt_handshake_timeouts_total 280
telemt_upstream_connect_attempt_total 11674
telemt_upstream_connect_success_total 11564
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11564
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 3814
telemt_me_reconnect_success_total 3803
telemt_me_reader_eof_total 3990
telemt_me_idle_close_by_peer_total 3990
telemt_me_route_drop_no_conn_total 11595
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_me_writer_removed_unexpected_total 3991
telemt_me_writer_restored_same_endpoint_total 3796
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 42233
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 519561392 (495.49 MB)
telemt_user_octets_to_client{user="hello"} 17279584708 (16.09 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 11229.7 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35481
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 2526
telemt_upstream_connect_attempt_total 7888
telemt_upstream_connect_success_total 7863
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 7863
telemt_upstream_connect_attempts_per_request{bucket="2"} 12
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 1651
telemt_me_reconnect_success_total 1641
telemt_me_reader_eof_total 1708
telemt_me_idle_close_by_peer_total 1708
telemt_me_route_drop_no_conn_total 14761
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 104
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 3
telemt_pool_force_close_total 52
telemt_me_writer_removed_unexpected_total 1708
telemt_me_writer_restored_same_endpoint_total 1636
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 31056
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 311463572 (297.03 MB)
telemt_user_octets_to_client{user="hello"} 18407826092 (17.14 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 11228.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44830
telemt_connections_bad_total 90
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 6440
telemt_upstream_connect_success_total 6427
telemt_upstream_connect_attempts_per_request{bucket="1"} 6427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 757
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 14510
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_pool_force_close_total 57
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 43940
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 11046067032 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 20244269188 (18.85 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 28
```