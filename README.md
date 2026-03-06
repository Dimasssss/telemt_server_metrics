# Server Metrics 2026-03-06 07:32:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 33048.5 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336222
telemt_connections_bad_total 16293
telemt_handshake_timeouts_total 3938
telemt_upstream_connect_attempt_total 33817
telemt_upstream_connect_success_total 33467
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 33467
telemt_upstream_connect_attempts_per_request{bucket="2"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 12025
telemt_me_reconnect_success_total 11977
telemt_me_reader_eof_total 12387
telemt_me_idle_close_by_peer_total 12387
telemt_me_route_drop_no_conn_total 117465
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1125
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 12390
telemt_me_writer_restored_same_endpoint_total 11971
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 296777
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 9973093676 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 107169991948 (99.81 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 33043.7 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145849
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 16526
telemt_upstream_connect_attempt_total 26266
telemt_upstream_connect_success_total 26264
telemt_upstream_connect_attempts_per_request{bucket="1"} 26264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6798
telemt_me_reconnect_success_total 6768
telemt_me_reader_eof_total 6919
telemt_me_idle_close_by_peer_total 6919
telemt_me_route_drop_no_conn_total 42972
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 437
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6920
telemt_me_writer_restored_same_endpoint_total 6761
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 126522
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 1436735532 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 40365159060 (37.59 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 33041.1 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255900
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 8394
telemt_upstream_connect_attempt_total 36904
telemt_upstream_connect_success_total 36621
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 36621
telemt_upstream_connect_attempts_per_request{bucket="2"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 14133
telemt_me_reconnect_success_total 14091
telemt_me_reader_eof_total 14745
telemt_me_idle_close_by_peer_total 14743
telemt_me_route_drop_no_conn_total 76199
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 614
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14773
telemt_me_writer_restored_same_endpoint_total 14069
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 224287
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 2301709384 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 70007129908 (65.20 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 33037.8 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194093
telemt_connections_bad_total 25190
telemt_handshake_timeouts_total 8084
telemt_upstream_connect_attempt_total 23054
telemt_upstream_connect_success_total 22975
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 22975
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 5025
telemt_me_reconnect_success_total 4991
telemt_me_reader_eof_total 5163
telemt_me_idle_close_by_peer_total 5163
telemt_me_route_drop_no_conn_total 60103
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 452
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 306
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5164
telemt_me_writer_restored_same_endpoint_total 4984
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 153765
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 2135722556 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 53557231724 (49.88 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 33036.8 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207336
telemt_connections_bad_total 3297
telemt_handshake_timeouts_total 1180
telemt_upstream_connect_attempt_total 21994
telemt_upstream_connect_success_total 21943
telemt_upstream_connect_attempts_per_request{bucket="1"} 21943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 334
telemt_me_reconnect_attempts_total 3825
telemt_me_reconnect_success_total 3805
telemt_me_reader_eof_total 3929
telemt_me_idle_close_by_peer_total 3928
telemt_me_route_drop_no_conn_total 83999
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 457
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3944
telemt_me_writer_restored_same_endpoint_total 3798
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 198457
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 24624160956 (22.93 GB)
telemt_user_octets_to_client{user="hello"} 118034069908 (109.93 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 94
```