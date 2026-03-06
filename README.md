# Server Metrics 2026-03-06 23:33:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 19511.0 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279407
telemt_connections_bad_total 3002
telemt_handshake_timeouts_total 9269
telemt_upstream_connect_attempt_total 44852
telemt_upstream_connect_success_total 43918
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 44715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 1359
telemt_me_reconnect_attempts_total 21219
telemt_me_reconnect_success_total 20468
telemt_me_reader_eof_total 23436
telemt_me_idle_close_by_peer_total 23436
telemt_me_route_drop_no_conn_total 109832
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 900
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 6
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 23546
telemt_me_writer_restored_same_endpoint_total 20418
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 13741
telemt_me_writer_removed_unexpected_minus_restored_total 3084
telemt_user_connections_total{user="hello"} 252692
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 4001781956 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 114514621564 (106.65 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 19511.4 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116180
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 11859
telemt_upstream_connect_attempt_total 71457
telemt_upstream_connect_success_total 71455
telemt_upstream_connect_attempts_per_request{bucket="1"} 71455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 841
telemt_me_reconnect_attempts_total 45077
telemt_me_reconnect_success_total 44903
telemt_me_reader_eof_total 44145
telemt_me_idle_close_by_peer_total 44141
telemt_me_route_drop_no_conn_total 39712
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 742
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 543
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 11
telemt_pool_force_close_total 604
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44168
telemt_me_writer_restored_same_endpoint_total 44901
telemt_me_async_recovery_trigger_total 13736
telemt_user_connections_total{user="hello"} 98371
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1481771580 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 35779945372 (33.32 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 19511.4 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215421
telemt_connections_bad_total 1081
telemt_handshake_timeouts_total 3519
telemt_upstream_connect_attempt_total 55121
telemt_upstream_connect_success_total 54960
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 55012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1541
telemt_me_reconnect_attempts_total 32370
telemt_me_reconnect_success_total 32322
telemt_me_reader_eof_total 33388
telemt_me_idle_close_by_peer_total 33385
telemt_me_route_drop_no_conn_total 82099
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 983
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 33544
telemt_me_writer_restored_same_endpoint_total 32315
telemt_me_async_recovery_trigger_total 41061
telemt_me_writer_removed_unexpected_minus_restored_total 1229
telemt_user_connections_total{user="hello"} 200210
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 15656496992 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 58957465176 (54.91 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 19511.6 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215254
telemt_connections_bad_total 57507
telemt_handshake_timeouts_total 16168
telemt_upstream_connect_attempt_total 33670
telemt_upstream_connect_success_total 33590
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 33623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 660
telemt_me_reconnect_attempts_total 10740
telemt_me_reconnect_success_total 10719
telemt_me_reader_eof_total 14510
telemt_me_idle_close_by_peer_total 14508
telemt_me_route_drop_no_conn_total 57263
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 198
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 10
telemt_pool_force_close_total 368
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 14515
telemt_me_writer_restored_same_endpoint_total 10714
telemt_me_writer_removed_unexpected_minus_restored_total 3801
telemt_user_connections_total{user="hello"} 137942
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1658927440 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 44613488840 (41.55 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 19510.1 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187388
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 1786
telemt_upstream_connect_attempt_total 30426
telemt_upstream_connect_success_total 30284
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 30303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 949
telemt_me_reconnect_attempts_total 8810
telemt_me_reconnect_success_total 8779
telemt_me_reader_eof_total 11879
telemt_me_idle_close_by_peer_total 11878
telemt_me_route_drop_no_conn_total 63545
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 753
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 11
telemt_pool_force_close_total 364
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 11946
telemt_me_writer_restored_same_endpoint_total 8775
telemt_me_writer_removed_unexpected_minus_restored_total 3171
telemt_user_connections_total{user="hello"} 171633
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 10056678268 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 59339481164 (55.26 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```