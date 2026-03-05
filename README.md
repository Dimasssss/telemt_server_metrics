# Server Metrics 2026-03-05 23:41:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 4790.2 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40908
telemt_connections_bad_total 14105
telemt_handshake_timeouts_total 354
telemt_upstream_connect_attempt_total 3391
telemt_upstream_connect_success_total 3360
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3360
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 744
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 756
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 6812
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 73
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 756
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 25686
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 420653988 (401.17 MB)
telemt_user_octets_to_client{user="hello"} 9967135644 (9.28 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 4785.6 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11749
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 3353
telemt_upstream_connect_success_total 3351
telemt_upstream_connect_attempts_per_request{bucket="1"} 3351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 3751
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_pool_force_close_total 9
telemt_me_writer_removed_unexpected_total 462
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 11243
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 91306820 (87.08 MB)
telemt_user_octets_to_client{user="hello"} 2224209620 (2.07 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 4783.1 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19357
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 3926
telemt_upstream_connect_success_total 3879
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 3879
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 900
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 932
telemt_me_idle_close_by_peer_total 932
telemt_me_route_drop_no_conn_total 5792
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 32
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_force_close_total 2
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 18800
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 359137828 (342.50 MB)
telemt_user_octets_to_client{user="hello"} 5701805100 (5.31 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 4779.7 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15885
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 426
telemt_upstream_connect_attempt_total 2487
telemt_upstream_connect_success_total 2476
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 2476
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 268
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 7775
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 14554
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 164756296 (157.12 MB)
telemt_user_octets_to_client{user="hello"} 13851068040 (12.90 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 4778.6 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20146
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 2820
telemt_upstream_connect_success_total 2818
telemt_upstream_connect_attempts_per_request{bucket="1"} 2818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 462
telemt_me_reconnect_success_total 465
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 471
telemt_me_route_drop_no_conn_total 7987
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 19706
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 10927899756 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 15794835944 (14.71 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 26
```