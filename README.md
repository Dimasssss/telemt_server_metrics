# Server Metrics 2026-03-03 23:40:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 8984.5 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69586
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 5881
telemt_upstream_connect_success_total 5853
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5853
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 983
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 27710
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 67307
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 574575056 (547.96 MB)
telemt_user_octets_to_client{user="hello"} 20949506148 (19.51 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 8981.2 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32507
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 6732
telemt_upstream_connect_attempt_total 13459
telemt_upstream_connect_success_total 13272
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 13272
telemt_upstream_connect_attempts_per_request{bucket="2"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 6323
telemt_me_reconnect_success_total 6332
telemt_me_reader_eof_total 6439
telemt_me_idle_close_by_peer_total 6438
telemt_me_route_drop_no_conn_total 12634
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 6439
telemt_me_writer_restored_same_endpoint_total 6312
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 25337
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 159281800 (151.90 MB)
telemt_user_octets_to_client{user="hello"} 13502702884 (12.58 GB)
telemt_user_unique_ips_current{user="hello"} 14
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 8979.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76047
telemt_connections_bad_total 21915
telemt_handshake_timeouts_total 1783
telemt_upstream_connect_attempt_total 10497
telemt_upstream_connect_success_total 10445
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10445
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 4000
telemt_me_reconnect_success_total 4005
telemt_me_reader_eof_total 4178
telemt_me_idle_close_by_peer_total 4177
telemt_me_route_drop_no_conn_total 16186
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4179
telemt_me_writer_restored_same_endpoint_total 3984
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 51172
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 329122756 (313.88 MB)
telemt_user_octets_to_client{user="hello"} 13932810184 (12.98 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 8978.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34473
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 487
telemt_upstream_connect_attempt_total 5168
telemt_upstream_connect_success_total 5145
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5145
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 499
telemt_me_reconnect_success_total 512
telemt_me_reader_eof_total 499
telemt_me_idle_close_by_peer_total 499
telemt_me_route_drop_no_conn_total 13108
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
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_restored_same_endpoint_total 493
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 33383
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 337682236 (322.04 MB)
telemt_user_octets_to_client{user="hello"} 9886474016 (9.21 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 8977.6 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81123
telemt_connections_bad_total 32
telemt_handshake_timeouts_total 32103
telemt_upstream_connect_attempt_total 7537
telemt_upstream_connect_success_total 7446
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7446
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 2280
telemt_me_reconnect_success_total 2294
telemt_me_reader_eof_total 2379
telemt_me_idle_close_by_peer_total 2379
telemt_me_route_drop_no_conn_total 33069
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
telemt_me_writer_removed_unexpected_total 2382
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 47561
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 229821832 (219.18 MB)
telemt_user_octets_to_client{user="hello"} 12597041188 (11.73 GB)
telemt_user_unique_ips_current{user="hello"} 19
```