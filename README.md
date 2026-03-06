# Server Metrics 2026-03-06 02:35:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 15233.0 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101522
telemt_connections_bad_total 15904
telemt_handshake_timeouts_total 978
telemt_upstream_connect_attempt_total 13365
telemt_upstream_connect_success_total 13249
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13249
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 3745
telemt_me_reconnect_success_total 3729
telemt_me_reader_eof_total 3858
telemt_me_idle_close_by_peer_total 3858
telemt_me_route_drop_no_conn_total 26022
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 256
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_restored_same_endpoint_total 3723
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 80511
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 947968640 (904.05 MB)
telemt_user_octets_to_client{user="hello"} 30234011400 (28.16 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 15228.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33978
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 426
telemt_upstream_connect_attempt_total 10775
telemt_upstream_connect_success_total 10773
telemt_upstream_connect_attempts_per_request{bucket="1"} 10773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 1696
telemt_me_reconnect_success_total 1688
telemt_me_reader_eof_total 1705
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 9847
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 32961
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 208157800 (198.51 MB)
telemt_user_octets_to_client{user="hello"} 7297510368 (6.80 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 15225.8 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61210
telemt_connections_bad_total 538
telemt_handshake_timeouts_total 690
telemt_upstream_connect_attempt_total 13832
telemt_upstream_connect_success_total 13713
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13713
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 4030
telemt_me_reader_eof_total 4222
telemt_me_idle_close_by_peer_total 4222
telemt_me_route_drop_no_conn_total 17203
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4223
telemt_me_writer_restored_same_endpoint_total 4023
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 57565
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 602556684 (574.64 MB)
telemt_user_octets_to_client{user="hello"} 20482698652 (19.08 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 15222.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48468
telemt_connections_bad_total 264
telemt_handshake_timeouts_total 2936
telemt_upstream_connect_attempt_total 10033
telemt_upstream_connect_success_total 10004
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 10004
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 2079
telemt_me_reconnect_success_total 2066
telemt_me_reader_eof_total 2160
telemt_me_idle_close_by_peer_total 2160
telemt_me_route_drop_no_conn_total 19353
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2160
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 42757
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 378564696 (361.03 MB)
telemt_user_octets_to_client{user="hello"} 21107590164 (19.66 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 15221.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60566
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 406
telemt_upstream_connect_attempt_total 9001
telemt_upstream_connect_success_total 8980
telemt_upstream_connect_attempts_per_request{bucket="1"} 8980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1025
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 18603
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 58682
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 11985286576 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 23491604548 (21.88 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 28
```