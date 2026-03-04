# Server Metrics 2026-03-04 06:50:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 34796.5 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331966
telemt_connections_bad_total 4534
telemt_handshake_timeouts_total 5791
telemt_upstream_connect_attempt_total 22595
telemt_upstream_connect_success_total 22488
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 22488
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4650
telemt_me_reconnect_success_total 4625
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_route_drop_no_conn_total 116932
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 734
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4734
telemt_me_writer_restored_same_endpoint_total 4605
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 292989
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 3149592236 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 91114305464 (84.86 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 34793.3 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154485
telemt_connections_bad_total 1213
telemt_handshake_timeouts_total 22529
telemt_upstream_connect_attempt_total 72813
telemt_upstream_connect_success_total 71781
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 71775
telemt_upstream_connect_attempts_per_request{bucket="2"} 483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_keepalive_timeout_total 1155
telemt_me_reconnect_attempts_total 42946
telemt_me_reconnect_success_total 42872
telemt_me_reader_eof_total 43942
telemt_me_idle_close_by_peer_total 43941
telemt_me_route_drop_no_conn_total 52299
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 286
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44022
telemt_me_writer_restored_same_endpoint_total 42847
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 104288
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 997318704 (951.12 MB)
telemt_user_octets_to_client{user="hello"} 42013608648 (39.13 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 34792.0 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303595
telemt_connections_bad_total 98827
telemt_handshake_timeouts_total 8524
telemt_upstream_connect_attempt_total 49450
telemt_upstream_connect_success_total 49142
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 49141
telemt_upstream_connect_attempts_per_request{bucket="2"} 146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 649
telemt_me_reconnect_attempts_total 21277
telemt_me_reconnect_success_total 21220
telemt_me_reader_eof_total 22387
telemt_me_idle_close_by_peer_total 22384
telemt_me_route_drop_no_conn_total 78422
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 466
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 22395
telemt_me_writer_restored_same_endpoint_total 21199
telemt_me_writer_removed_unexpected_minus_restored_total 1196
telemt_user_connections_total{user="hello"} 187588
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 1557162488 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 59478773316 (55.39 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 34790.9 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169211
telemt_connections_bad_total 13420
telemt_handshake_timeouts_total 5507
telemt_upstream_connect_attempt_total 26961
telemt_upstream_connect_success_total 26858
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26858
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 5987
telemt_me_reconnect_success_total 5975
telemt_me_reader_eof_total 6088
telemt_me_idle_close_by_peer_total 6088
telemt_me_route_drop_no_conn_total 48163
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6088
telemt_me_writer_restored_same_endpoint_total 5954
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 134823
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 1347130500 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 49928230228 (46.50 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 34789.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310591
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 128343
telemt_upstream_connect_attempt_total 48431
telemt_upstream_connect_success_total 48098
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 48098
telemt_upstream_connect_attempts_per_request{bucket="2"} 156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 653
telemt_me_reconnect_attempts_total 22268
telemt_me_reconnect_success_total 22254
telemt_me_reader_eof_total 23460
telemt_me_idle_close_by_peer_total 23459
telemt_me_route_drop_no_conn_total 79079
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23473
telemt_me_writer_restored_same_endpoint_total 22229
telemt_me_writer_removed_unexpected_minus_restored_total 1244
telemt_user_connections_total{user="hello"} 170181
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 2322906956 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 38321453000 (35.69 GB)
telemt_user_unique_ips_current{user="hello"} 37
```