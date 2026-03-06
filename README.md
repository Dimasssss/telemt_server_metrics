# Server Metrics 2026-03-06 04:43:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 22911.8 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168097
telemt_connections_bad_total 15966
telemt_handshake_timeouts_total 3089
telemt_upstream_connect_attempt_total 24228
telemt_upstream_connect_success_total 24030
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 24030
telemt_upstream_connect_attempts_per_request{bucket="2"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 8840
telemt_me_reconnect_success_total 8809
telemt_me_reader_eof_total 9125
telemt_me_idle_close_by_peer_total 9125
telemt_me_route_drop_no_conn_total 48440
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 475
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9126
telemt_me_writer_restored_same_endpoint_total 8803
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 140945
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 3155085728 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 54798895244 (51.04 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 22907.2 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61221
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 840
telemt_upstream_connect_attempt_total 22264
telemt_upstream_connect_success_total 22262
telemt_upstream_connect_attempts_per_request{bucket="1"} 22262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 264
telemt_me_reconnect_attempts_total 6147
telemt_me_reconnect_success_total 6127
telemt_me_reader_eof_total 6263
telemt_me_idle_close_by_peer_total 6263
telemt_me_route_drop_no_conn_total 18318
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 230
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6264
telemt_me_writer_restored_same_endpoint_total 6121
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 59137
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 513873108 (490.07 MB)
telemt_user_octets_to_client{user="hello"} 14607375588 (13.60 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 22904.7 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105882
telemt_connections_bad_total 1353
telemt_handshake_timeouts_total 2385
telemt_upstream_connect_attempt_total 21645
telemt_upstream_connect_success_total 21466
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 21466
telemt_upstream_connect_attempts_per_request{bucket="2"} 80
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 6619
telemt_me_reconnect_success_total 6595
telemt_me_reader_eof_total 6895
telemt_me_idle_close_by_peer_total 6895
telemt_me_route_drop_no_conn_total 30102
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6899
telemt_me_writer_restored_same_endpoint_total 6587
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 98830
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 962675700 (918.08 MB)
telemt_user_octets_to_client{user="hello"} 33276347768 (30.99 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 22901.3 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87076
telemt_connections_bad_total 3978
telemt_handshake_timeouts_total 4694
telemt_upstream_connect_attempt_total 15193
telemt_upstream_connect_success_total 15142
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 15142
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 163
telemt_me_reconnect_attempts_total 2869
telemt_me_reconnect_success_total 2845
telemt_me_reader_eof_total 2951
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 29439
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2951
telemt_me_writer_restored_same_endpoint_total 2838
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 73991
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1372731592 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 29370184552 (27.35 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 22900.2 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100503
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 15926
telemt_upstream_connect_success_total 15889
telemt_upstream_connect_attempts_per_request{bucket="1"} 15889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 2805
telemt_me_reconnect_success_total 2793
telemt_me_reader_eof_total 2891
telemt_me_idle_close_by_peer_total 2890
telemt_me_route_drop_no_conn_total 33993
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 136
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2895
telemt_me_writer_restored_same_endpoint_total 2786
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 97182
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 23441267856 (21.83 GB)
telemt_user_octets_to_client{user="hello"} 55676729304 (51.85 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 48
```