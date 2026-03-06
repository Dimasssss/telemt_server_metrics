# Server Metrics 2026-03-06 07:52:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 34279.8 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361502
telemt_connections_bad_total 16553
telemt_handshake_timeouts_total 4050
telemt_upstream_connect_attempt_total 35897
telemt_upstream_connect_success_total 35544
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 35544
telemt_upstream_connect_attempts_per_request{bucket="2"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 371
telemt_me_reconnect_attempts_total 13033
telemt_me_reconnect_success_total 12983
telemt_me_reader_eof_total 13436
telemt_me_idle_close_by_peer_total 13436
telemt_me_route_drop_no_conn_total 127949
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1196
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 822
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 399
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 13439
telemt_me_writer_restored_same_endpoint_total 12977
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 320615
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 10290862912 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 115550425460 (107.61 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 34275.2 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159176
telemt_connections_bad_total 257
telemt_handshake_timeouts_total 18224
telemt_upstream_connect_attempt_total 26820
telemt_upstream_connect_success_total 26818
telemt_upstream_connect_attempts_per_request{bucket="1"} 26818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6804
telemt_me_reconnect_success_total 6773
telemt_me_reader_eof_total 6925
telemt_me_idle_close_by_peer_total 6925
telemt_me_route_drop_no_conn_total 46614
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 473
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6926
telemt_me_writer_restored_same_endpoint_total 6766
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 137770
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 1604360084 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 43560877440 (40.57 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 34272.6 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278969
telemt_connections_bad_total 2037
telemt_handshake_timeouts_total 9931
telemt_upstream_connect_attempt_total 37588
telemt_upstream_connect_success_total 37298
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 37298
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 537
telemt_me_reconnect_attempts_total 14191
telemt_me_reconnect_success_total 14148
telemt_me_reader_eof_total 14801
telemt_me_idle_close_by_peer_total 14799
telemt_me_route_drop_no_conn_total 82935
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 749
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 522
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14830
telemt_me_writer_restored_same_endpoint_total 14126
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 242185
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 2722399372 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 76668999100 (71.40 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 34269.2 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210007
telemt_connections_bad_total 29139
telemt_handshake_timeouts_total 9317
telemt_upstream_connect_attempt_total 23626
telemt_upstream_connect_success_total 23539
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 23539
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 259
telemt_me_reconnect_attempts_total 5046
telemt_me_reconnect_success_total 5011
telemt_me_reader_eof_total 5183
telemt_me_idle_close_by_peer_total 5183
telemt_me_route_drop_no_conn_total 63713
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 509
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5184
telemt_me_writer_restored_same_endpoint_total 5004
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 163920
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 2264469632 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 55251674988 (51.46 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 34268.2 (9h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222222
telemt_connections_bad_total 3304
telemt_handshake_timeouts_total 1215
telemt_upstream_connect_attempt_total 23010
telemt_upstream_connect_success_total 22955
telemt_upstream_connect_attempts_per_request{bucket="1"} 22955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 352
telemt_me_reconnect_attempts_total 4098
telemt_me_reconnect_success_total 4078
telemt_me_reader_eof_total 4211
telemt_me_idle_close_by_peer_total 4210
telemt_me_route_drop_no_conn_total 91480
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 482
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4226
telemt_me_writer_restored_same_endpoint_total 4071
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 213008
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 24791993460 (23.09 GB)
telemt_user_octets_to_client{user="hello"} 125656740300 (117.03 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 79
```