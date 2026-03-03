# Server Metrics 2026-03-03 22:18:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 4071.4 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40513
telemt_connections_bad_total 463
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 1931
telemt_upstream_connect_success_total 1921
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1921
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 210
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 15232
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 66
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 1
telemt_pool_force_close_total 38
telemt_me_writer_removed_unexpected_total 193
telemt_me_writer_restored_same_endpoint_total 190
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 39033
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 405043908 (386.28 MB)
telemt_user_octets_to_client{user="hello"} 15462451340 (14.40 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 4068.1 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16651
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 3015
telemt_upstream_connect_attempt_total 3082
telemt_upstream_connect_success_total 2948
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 2948
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 738
telemt_me_reconnect_success_total 752
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 6388
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 746
telemt_me_writer_restored_same_endpoint_total 732
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 13377
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 77455320 (73.87 MB)
telemt_user_octets_to_client{user="hello"} 3523723852 (3.28 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 4066.8 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41458
telemt_connections_bad_total 11137
telemt_handshake_timeouts_total 602
telemt_upstream_connect_attempt_total 2729
telemt_upstream_connect_success_total 2702
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2702
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 406
telemt_me_reconnect_success_total 422
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 8763
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 105
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_restored_same_endpoint_total 401
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 28741
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 212532956 (202.69 MB)
telemt_user_octets_to_client{user="hello"} 11024071140 (10.27 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 4065.8 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19217
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 2324
telemt_upstream_connect_success_total 2309
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2309
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 257
telemt_me_reconnect_success_total 274
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 7671
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 257
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 18643
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 162521668 (154.99 MB)
telemt_user_octets_to_client{user="hello"} 7067085188 (6.58 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 4064.5 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38094
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 9549
telemt_upstream_connect_attempt_total 2182
telemt_upstream_connect_success_total 2150
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2150
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 426
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 25973
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_restored_same_endpoint_total 419
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 27909
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 158506832 (151.16 MB)
telemt_user_octets_to_client{user="hello"} 7012236544 (6.53 GB)
telemt_user_unique_ips_current{user="hello"} 31
```