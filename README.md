# Server Metrics 2026-03-04 00:57:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 13591.6 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94154
telemt_connections_bad_total 686
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 10344
telemt_upstream_connect_success_total 10293
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 10293
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 2707
telemt_me_reconnect_success_total 2710
telemt_me_reader_eof_total 2767
telemt_me_idle_close_by_peer_total 2767
telemt_me_route_drop_no_conn_total 35327
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2767
telemt_me_writer_restored_same_endpoint_total 2690
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 90737
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 699931580 (667.51 MB)
telemt_user_octets_to_client{user="hello"} 27578817780 (25.68 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 13588.4 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44126
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 10338
telemt_upstream_connect_attempt_total 26328
telemt_upstream_connect_success_total 25986
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 25980
telemt_upstream_connect_attempts_per_request{bucket="2"} 161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 628
telemt_me_reconnect_attempts_total 14656
telemt_me_reconnect_success_total 14649
telemt_me_reader_eof_total 14982
telemt_me_idle_close_by_peer_total 14981
telemt_me_route_drop_no_conn_total 15897
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 15043
telemt_me_writer_restored_same_endpoint_total 14629
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 33148
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 215523012 (205.54 MB)
telemt_user_octets_to_client{user="hello"} 19966255100 (18.60 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 13587.1 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101938
telemt_connections_bad_total 33979
telemt_handshake_timeouts_total 1927
telemt_upstream_connect_attempt_total 15938
telemt_upstream_connect_success_total 15849
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 15849
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 197
telemt_me_reconnect_attempts_total 5645
telemt_me_reconnect_success_total 5640
telemt_me_reader_eof_total 5871
telemt_me_idle_close_by_peer_total 5869
telemt_me_route_drop_no_conn_total 20161
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 5872
telemt_me_writer_restored_same_endpoint_total 5619
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 64754
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 397674360 (379.25 MB)
telemt_user_octets_to_client{user="hello"} 16370194916 (15.25 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 13586.3 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45308
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 524
telemt_upstream_connect_attempt_total 8728
telemt_upstream_connect_success_total 8696
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 8696
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1299
telemt_me_reconnect_success_total 1310
telemt_me_reader_eof_total 1309
telemt_me_idle_close_by_peer_total 1309
telemt_me_route_drop_no_conn_total 15740
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 10
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 43872
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 397569692 (379.15 MB)
telemt_user_octets_to_client{user="hello"} 11422012792 (10.64 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 13584.6 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110294
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 47245
telemt_upstream_connect_attempt_total 18922
telemt_upstream_connect_success_total 18805
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18805
telemt_upstream_connect_attempts_per_request{bucket="2"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 9283
telemt_me_reconnect_success_total 9287
telemt_me_reader_eof_total 9859
telemt_me_idle_close_by_peer_total 9858
telemt_me_route_drop_no_conn_total 36387
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 9865
telemt_me_writer_restored_same_endpoint_total 9263
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 60869
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 296645664 (282.90 MB)
telemt_user_octets_to_client{user="hello"} 15007089656 (13.98 GB)
telemt_user_unique_ips_current{user="hello"} 18
```