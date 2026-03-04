# Server Metrics 2026-03-04 11:47:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 52631.0 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861320
telemt_connections_bad_total 12055
telemt_handshake_timeouts_total 12265
telemt_upstream_connect_attempt_total 32466
telemt_upstream_connect_success_total 32329
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32329
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 362
telemt_me_reconnect_attempts_total 7084
telemt_me_reconnect_success_total 7037
telemt_me_reader_eof_total 7257
telemt_me_idle_close_by_peer_total 7257
telemt_me_route_drop_no_conn_total 325777
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1379
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 14
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7257
telemt_me_writer_restored_same_endpoint_total 7016
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 691181
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 7459724200 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 209888013472 (195.47 GB)
telemt_user_unique_ips_current{user="hello"} 106
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 52627.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342427
telemt_connections_bad_total 3065
telemt_handshake_timeouts_total 27437
telemt_upstream_connect_attempt_total 100979
telemt_upstream_connect_success_total 99453
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 99447
telemt_upstream_connect_attempts_per_request{bucket="2"} 731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1403
telemt_me_reconnect_attempts_total 56964
telemt_me_reconnect_success_total 56877
telemt_me_reader_eof_total 58314
telemt_me_idle_close_by_peer_total 58313
telemt_me_route_drop_no_conn_total 143674
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 624
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58394
telemt_me_writer_restored_same_endpoint_total 56852
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 259124
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 3373380860 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 82042046536 (76.41 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 52626.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653741
telemt_connections_bad_total 157731
telemt_handshake_timeouts_total 20830
telemt_upstream_connect_attempt_total 78638
telemt_upstream_connect_success_total 78175
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 78174
telemt_upstream_connect_attempts_per_request{bucket="2"} 223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 36937
telemt_me_reconnect_success_total 36847
telemt_me_reader_eof_total 38817
telemt_me_idle_close_by_peer_total 38813
telemt_me_route_drop_no_conn_total 245190
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1145
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38829
telemt_me_writer_restored_same_endpoint_total 36825
telemt_me_writer_removed_unexpected_minus_restored_total 2004
telemt_user_connections_total{user="hello"} 454823
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 5928155484 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 151978596948 (141.54 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 52625.1 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422770
telemt_connections_bad_total 29484
telemt_handshake_timeouts_total 67091
telemt_upstream_connect_attempt_total 38746
telemt_upstream_connect_success_total 38591
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 38591
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 436
telemt_me_reconnect_attempts_total 8249
telemt_me_reconnect_success_total 8220
telemt_me_reader_eof_total 8403
telemt_me_idle_close_by_peer_total 8403
telemt_me_route_drop_no_conn_total 121121
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 238
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8403
telemt_me_writer_restored_same_endpoint_total 8199
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 303738
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 3694699044 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 112517618264 (104.79 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 52624.1 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570450
telemt_connections_bad_total 6820
telemt_handshake_timeouts_total 132479
telemt_upstream_connect_attempt_total 74898
telemt_upstream_connect_success_total 74362
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 74362
telemt_upstream_connect_attempts_per_request{bucket="2"} 255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 977
telemt_me_reconnect_attempts_total 35941
telemt_me_reconnect_success_total 35905
telemt_me_reader_eof_total 37661
telemt_me_idle_close_by_peer_total 37660
telemt_me_route_drop_no_conn_total 184274
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 37672
telemt_me_writer_restored_same_endpoint_total 35880
telemt_me_writer_removed_unexpected_minus_restored_total 1792
telemt_user_connections_total{user="hello"} 405823
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 5216478868 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 111868499108 (104.19 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 53
```