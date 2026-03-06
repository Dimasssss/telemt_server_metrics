# Server Metrics 2026-03-06 04:48:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 23219.1 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172331
telemt_connections_bad_total 15967
telemt_handshake_timeouts_total 3131
telemt_upstream_connect_attempt_total 24482
telemt_upstream_connect_success_total 24285
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 24285
telemt_upstream_connect_attempts_per_request{bucket="2"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 8908
telemt_me_reconnect_success_total 8877
telemt_me_reader_eof_total 9193
telemt_me_idle_close_by_peer_total 9193
telemt_me_route_drop_no_conn_total 49533
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 477
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9194
telemt_me_writer_restored_same_endpoint_total 8871
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 145039
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 3189502212 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 56102352960 (52.25 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 23214.6 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62876
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 22891
telemt_upstream_connect_success_total 22889
telemt_upstream_connect_attempts_per_request{bucket="1"} 22889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 6486
telemt_me_reconnect_success_total 6466
telemt_me_reader_eof_total 6616
telemt_me_idle_close_by_peer_total 6616
telemt_me_route_drop_no_conn_total 18777
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6617
telemt_me_writer_restored_same_endpoint_total 6460
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 60734
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 529768184 (505.23 MB)
telemt_user_octets_to_client{user="hello"} 15615093356 (14.54 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 23212.0 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108988
telemt_connections_bad_total 1353
telemt_handshake_timeouts_total 2434
telemt_upstream_connect_attempt_total 22026
telemt_upstream_connect_success_total 21847
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 21847
telemt_upstream_connect_attempts_per_request{bucket="2"} 80
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 6759
telemt_me_reconnect_success_total 6735
telemt_me_reader_eof_total 7037
telemt_me_idle_close_by_peer_total 7037
telemt_me_route_drop_no_conn_total 30903
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 222
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 7041
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 101787
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 976948916 (931.69 MB)
telemt_user_octets_to_client{user="hello"} 34401950776 (32.04 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 23208.6 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89468
telemt_connections_bad_total 4247
telemt_handshake_timeouts_total 5111
telemt_upstream_connect_attempt_total 15475
telemt_upstream_connect_success_total 15424
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 15424
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 2934
telemt_me_reconnect_success_total 2909
telemt_me_reader_eof_total 3015
telemt_me_idle_close_by_peer_total 3015
telemt_me_route_drop_no_conn_total 30054
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 253
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 3015
telemt_me_writer_restored_same_endpoint_total 2902
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 75690
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 1381922508 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 29846044320 (27.80 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 23207.8 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102875
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 608
telemt_upstream_connect_attempt_total 16106
telemt_upstream_connect_success_total 16069
telemt_upstream_connect_attempts_per_request{bucket="1"} 16069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 2815
telemt_me_reconnect_success_total 2803
telemt_me_reader_eof_total 2901
telemt_me_idle_close_by_peer_total 2900
telemt_me_route_drop_no_conn_total 35222
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 143
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2905
telemt_me_writer_restored_same_endpoint_total 2796
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 99503
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 23479922564 (21.87 GB)
telemt_user_octets_to_client{user="hello"} 57206155664 (53.28 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 49
```