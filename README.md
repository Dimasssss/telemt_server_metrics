# Server Metrics 2026-03-06 07:42:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 33665.6 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349069
telemt_connections_bad_total 16320
telemt_handshake_timeouts_total 3981
telemt_upstream_connect_attempt_total 34909
telemt_upstream_connect_success_total 34558
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 34558
telemt_upstream_connect_attempts_per_request{bucket="2"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 12586
telemt_me_reconnect_success_total 12537
telemt_me_reader_eof_total 12971
telemt_me_idle_close_by_peer_total 12971
telemt_me_route_drop_no_conn_total 122631
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1130
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 452
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 12974
telemt_me_writer_restored_same_endpoint_total 12531
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 308913
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 10141510984 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 111360527388 (103.71 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 33658.1 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152747
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 17712
telemt_upstream_connect_attempt_total 26532
telemt_upstream_connect_success_total 26530
telemt_upstream_connect_attempts_per_request{bucket="1"} 26530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6804
telemt_me_reconnect_success_total 6773
telemt_me_reader_eof_total 6925
telemt_me_idle_close_by_peer_total 6925
telemt_me_route_drop_no_conn_total 44644
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 456
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 306
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6926
telemt_me_writer_restored_same_endpoint_total 6766
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 132133
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 1495538532 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 41769864876 (38.90 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 33655.5 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266475
telemt_connections_bad_total 1972
telemt_handshake_timeouts_total 9134
telemt_upstream_connect_attempt_total 37257
telemt_upstream_connect_success_total 36967
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 36967
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 528
telemt_me_reconnect_attempts_total 14157
telemt_me_reconnect_success_total 14115
telemt_me_reader_eof_total 14768
telemt_me_idle_close_by_peer_total 14766
telemt_me_route_drop_no_conn_total 79568
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 689
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14797
telemt_me_writer_restored_same_endpoint_total 14093
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 233720
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 2388295200 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 72471557180 (67.49 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 33652.1 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202025
telemt_connections_bad_total 27140
telemt_handshake_timeouts_total 8771
telemt_upstream_connect_attempt_total 23309
telemt_upstream_connect_success_total 23222
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 23222
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 5032
telemt_me_reconnect_success_total 4998
telemt_me_reader_eof_total 5170
telemt_me_idle_close_by_peer_total 5170
telemt_me_route_drop_no_conn_total 61938
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 475
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5171
telemt_me_writer_restored_same_endpoint_total 4991
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 158785
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 2218876136 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 54162750108 (50.44 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 33651.2 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215155
telemt_connections_bad_total 3300
telemt_handshake_timeouts_total 1205
telemt_upstream_connect_attempt_total 22475
telemt_upstream_connect_success_total 22420
telemt_upstream_connect_attempts_per_request{bucket="1"} 22420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 3933
telemt_me_reconnect_success_total 3913
telemt_me_reader_eof_total 4040
telemt_me_idle_close_by_peer_total 4039
telemt_me_route_drop_no_conn_total 88048
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 461
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4055
telemt_me_writer_restored_same_endpoint_total 3906
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 206104
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 24729545348 (23.03 GB)
telemt_user_octets_to_client{user="hello"} 121775331464 (113.41 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 86
```