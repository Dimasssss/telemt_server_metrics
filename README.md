# Server Metrics 2026-03-04 07:11:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 36025.1 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378105
telemt_connections_bad_total 6015
telemt_handshake_timeouts_total 5900
telemt_upstream_connect_attempt_total 23112
telemt_upstream_connect_success_total 23003
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 23003
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 4668
telemt_me_reconnect_success_total 4641
telemt_me_reader_eof_total 4751
telemt_me_idle_close_by_peer_total 4751
telemt_me_route_drop_no_conn_total 125454
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 757
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4751
telemt_me_writer_restored_same_endpoint_total 4621
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 315040
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 3577166584 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 96813130036 (90.16 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 36021.7 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162941
telemt_connections_bad_total 1236
telemt_handshake_timeouts_total 22922
telemt_upstream_connect_attempt_total 74374
telemt_upstream_connect_success_total 73298
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 73292
telemt_upstream_connect_attempts_per_request{bucket="2"} 506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_keepalive_timeout_total 1172
telemt_me_reconnect_attempts_total 43633
telemt_me_reconnect_success_total 43558
telemt_me_reader_eof_total 44640
telemt_me_idle_close_by_peer_total 44639
telemt_me_route_drop_no_conn_total 58175
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 303
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44720
telemt_me_writer_restored_same_endpoint_total 43533
telemt_me_writer_removed_unexpected_minus_restored_total 1187
telemt_user_connections_total{user="hello"} 112039
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 1102726152 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 45081982712 (41.99 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 36020.5 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321923
telemt_connections_bad_total 102003
telemt_handshake_timeouts_total 9577
telemt_upstream_connect_attempt_total 52254
telemt_upstream_connect_success_total 51938
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 51937
telemt_upstream_connect_attempts_per_request{bucket="2"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 685
telemt_me_reconnect_attempts_total 22926
telemt_me_reconnect_success_total 22866
telemt_me_reader_eof_total 24118
telemt_me_idle_close_by_peer_total 24115
telemt_me_route_drop_no_conn_total 88755
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 492
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 24129
telemt_me_writer_restored_same_endpoint_total 22845
telemt_me_writer_removed_unexpected_minus_restored_total 1284
telemt_user_connections_total{user="hello"} 201426
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 1802526592 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 68750901484 (64.03 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 36019.4 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183754
telemt_connections_bad_total 14524
telemt_handshake_timeouts_total 6706
telemt_upstream_connect_attempt_total 27498
telemt_upstream_connect_success_total 27383
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 27383
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 6017
telemt_me_reconnect_success_total 6004
telemt_me_reader_eof_total 6120
telemt_me_idle_close_by_peer_total 6120
telemt_me_route_drop_no_conn_total 55095
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6120
telemt_me_writer_restored_same_endpoint_total 5983
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 144020
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 1432602400 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 52015333032 (48.44 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 36018.2 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324772
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 128987
telemt_upstream_connect_attempt_total 50253
telemt_upstream_connect_success_total 49915
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 49915
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 23048
telemt_me_reconnect_success_total 23032
telemt_me_reader_eof_total 24260
telemt_me_idle_close_by_peer_total 24259
telemt_me_route_drop_no_conn_total 85966
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 24273
telemt_me_writer_restored_same_endpoint_total 23007
telemt_me_writer_removed_unexpected_minus_restored_total 1266
telemt_user_connections_total{user="hello"} 183247
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 2406219320 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 41096667440 (38.27 GB)
telemt_user_unique_ips_current{user="hello"} 48
```