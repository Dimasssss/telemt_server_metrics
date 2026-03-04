# Server Metrics 2026-03-04 01:33:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 15741.5 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104435
telemt_connections_bad_total 1366
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 12637
telemt_upstream_connect_success_total 12582
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 12582
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 3268
telemt_me_reconnect_success_total 3268
telemt_me_reader_eof_total 3341
telemt_me_idle_close_by_peer_total 3341
telemt_me_route_drop_no_conn_total 38767
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3341
telemt_me_writer_restored_same_endpoint_total 3248
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 100122
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 778663504 (742.59 MB)
telemt_user_octets_to_client{user="hello"} 30673109424 (28.57 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 15738.3 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48748
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12167
telemt_upstream_connect_attempt_total 33139
telemt_upstream_connect_success_total 32740
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 32734
telemt_upstream_connect_attempts_per_request{bucket="2"} 189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 19204
telemt_me_reconnect_success_total 19194
telemt_me_reader_eof_total 19668
telemt_me_idle_close_by_peer_total 19667
telemt_me_route_drop_no_conn_total 17113
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 19729
telemt_me_writer_restored_same_endpoint_total 19174
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 35903
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 271613204 (259.03 MB)
telemt_user_octets_to_client{user="hello"} 21714799476 (20.22 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 15737.0 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113814
telemt_connections_bad_total 39570
telemt_handshake_timeouts_total 1982
telemt_upstream_connect_attempt_total 17492
telemt_upstream_connect_success_total 17383
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 17383
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 5924
telemt_me_reconnect_success_total 5917
telemt_me_reader_eof_total 6161
telemt_me_idle_close_by_peer_total 6159
telemt_me_route_drop_no_conn_total 21815
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 243
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6162
telemt_me_writer_restored_same_endpoint_total 5896
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 70752
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 432351816 (412.32 MB)
telemt_user_octets_to_client{user="hello"} 17803059756 (16.58 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 15735.9 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51264
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 10118
telemt_upstream_connect_success_total 10079
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10079
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1444
telemt_me_reconnect_success_total 1452
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 17825
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 119
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_restored_same_endpoint_total 1432
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 49688
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 420397144 (400.92 MB)
telemt_user_octets_to_client{user="hello"} 14211851684 (13.24 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 15734.6 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123778
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 54169
telemt_upstream_connect_attempt_total 24718
telemt_upstream_connect_success_total 24583
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 24583
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 13204
telemt_me_reconnect_success_total 13205
telemt_me_reader_eof_total 14057
telemt_me_idle_close_by_peer_total 14056
telemt_me_route_drop_no_conn_total 38248
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 371
telemt_me_writer_removed_unexpected_total 14062
telemt_me_writer_restored_same_endpoint_total 13181
telemt_me_writer_removed_unexpected_minus_restored_total 881
telemt_user_connections_total{user="hello"} 67261
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 322626196 (307.68 MB)
telemt_user_octets_to_client{user="hello"} 15842505632 (14.75 GB)
telemt_user_unique_ips_current{user="hello"} 25
```