# Server Metrics 2026-03-04 06:09:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 32325.1 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266104
telemt_connections_bad_total 2461
telemt_handshake_timeouts_total 4987
telemt_upstream_connect_attempt_total 21670
telemt_upstream_connect_success_total 21571
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21571
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 4598
telemt_me_reader_eof_total 4704
telemt_me_idle_close_by_peer_total 4704
telemt_me_route_drop_no_conn_total 98687
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 678
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4704
telemt_me_writer_restored_same_endpoint_total 4578
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 249315
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 2706780836 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 80398321196 (74.88 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 32321.9 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138400
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 22095
telemt_upstream_connect_attempt_total 71263
telemt_upstream_connect_success_total 70406
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 70400
telemt_upstream_connect_attempts_per_request{bucket="2"} 418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 42635
telemt_me_reconnect_success_total 42605
telemt_me_reader_eof_total 43674
telemt_me_idle_close_by_peer_total 43673
telemt_me_route_drop_no_conn_total 43580
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 25
telemt_me_writer_removed_unexpected_total 43735
telemt_me_writer_restored_same_endpoint_total 42584
telemt_me_writer_removed_unexpected_minus_restored_total 1151
telemt_user_connections_total{user="hello"} 89761
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 836267512 (797.53 MB)
telemt_user_octets_to_client{user="hello"} 37051304176 (34.51 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 32320.5 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268984
telemt_connections_bad_total 92339
telemt_handshake_timeouts_total 6190
telemt_upstream_connect_attempt_total 43965
telemt_upstream_connect_success_total 43694
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 43694
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 18176
telemt_me_reconnect_success_total 18129
telemt_me_reader_eof_total 19111
telemt_me_idle_close_by_peer_total 19108
telemt_me_route_drop_no_conn_total 61846
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 410
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 19119
telemt_me_writer_restored_same_endpoint_total 18108
telemt_me_writer_removed_unexpected_minus_restored_total 1011
telemt_user_connections_total{user="hello"} 162559
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 1217349804 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 42774033608 (39.84 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 32319.7 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139605
telemt_connections_bad_total 11188
telemt_handshake_timeouts_total 3019
telemt_upstream_connect_attempt_total 25659
telemt_upstream_connect_success_total 25568
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 25568
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 5762
telemt_me_reconnect_success_total 5753
telemt_me_reader_eof_total 5862
telemt_me_idle_close_by_peer_total 5862
telemt_me_route_drop_no_conn_total 42132
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 135
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 5862
telemt_me_writer_restored_same_endpoint_total 5732
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 118308
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1034047504 (986.14 MB)
telemt_user_octets_to_client{user="hello"} 44106680564 (41.08 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 32318.2 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284312
telemt_connections_bad_total 6392
telemt_handshake_timeouts_total 126523
telemt_upstream_connect_attempt_total 45752
telemt_upstream_connect_success_total 45433
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 45433
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 628
telemt_me_reconnect_attempts_total 21538
telemt_me_reconnect_success_total 21526
telemt_me_reader_eof_total 22710
telemt_me_idle_close_by_peer_total 22709
telemt_me_route_drop_no_conn_total 65880
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22723
telemt_me_writer_restored_same_endpoint_total 21501
telemt_me_writer_removed_unexpected_minus_restored_total 1222
telemt_user_connections_total{user="hello"} 146601
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 2052732872 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 34016410312 (31.68 GB)
telemt_user_unique_ips_current{user="hello"} 44
```