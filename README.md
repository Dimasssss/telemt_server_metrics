# Server Metrics 2026-03-04 23:15:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 8544.4 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85029
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 552
telemt_upstream_connect_attempt_total 9058
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8932
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 3376
telemt_me_reconnect_success_total 3377
telemt_me_reader_eof_total 3466
telemt_me_idle_close_by_peer_total 3465
telemt_me_route_drop_no_conn_total 22450
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 3515
telemt_me_writer_restored_same_endpoint_total 3357
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 72510
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 2734106340 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 41043447628 (38.22 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 8539.3 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30616
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 10000
telemt_upstream_connect_success_total 9862
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 9859
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 523
telemt_me_reconnect_attempts_total 4079
telemt_me_reconnect_success_total 4074
telemt_me_reader_eof_total 4156
telemt_me_idle_close_by_peer_total 4155
telemt_me_route_drop_no_conn_total 9754
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 121
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_removed_unexpected_total 4210
telemt_me_writer_restored_same_endpoint_total 4055
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 28844
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 252347764 (240.66 MB)
telemt_user_octets_to_client{user="hello"} 8452379692 (7.87 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 8535.8 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72964
telemt_connections_bad_total 1052
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 3478
telemt_upstream_connect_success_total 3442
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3442
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 22208
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 160
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 67305
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 960934536 (916.42 MB)
telemt_user_octets_to_client{user="hello"} 24606576296 (22.92 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 40584.0 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532067
telemt_connections_bad_total 73470
telemt_handshake_timeouts_total 14702
telemt_upstream_connect_attempt_total 17259
telemt_upstream_connect_success_total 17259
telemt_upstream_connect_attempts_per_request{bucket="1"} 17259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 2188
telemt_me_reconnect_success_total 2172
telemt_me_reader_eof_total 2214
telemt_me_idle_close_by_peer_total 2214
telemt_me_route_drop_no_conn_total 181294
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 713
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 17
telemt_pool_force_close_total 469
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 415547
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 5747679756 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 156098686716 (145.38 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 40943.3 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526335
telemt_connections_bad_total 3775
telemt_handshake_timeouts_total 5774
telemt_upstream_connect_attempt_total 26104
telemt_upstream_connect_success_total 25964
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 25964
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 380
telemt_me_reconnect_attempts_total 5908
telemt_me_reconnect_success_total 5893
telemt_me_reader_eof_total 6110
telemt_me_idle_close_by_peer_total 6109
telemt_me_route_drop_no_conn_total 232208
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6113
telemt_me_writer_restored_same_endpoint_total 5872
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 476147
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 7313250376 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 157375561440 (146.57 GB)
telemt_user_unique_ips_current{user="hello"} 23
```