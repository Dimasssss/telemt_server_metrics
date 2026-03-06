# Server Metrics 2026-03-06 20:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 10262.4 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211747
telemt_connections_bad_total 2199
telemt_handshake_timeouts_total 8679
telemt_upstream_connect_attempt_total 16189
telemt_upstream_connect_success_total 16037
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 16094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 927
telemt_me_reconnect_attempts_total 5025
telemt_me_reconnect_success_total 4996
telemt_me_reader_eof_total 6479
telemt_me_idle_close_by_peer_total 6479
telemt_me_route_drop_no_conn_total 82875
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 735
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 3
telemt_pool_force_close_total 256
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6586
telemt_me_writer_restored_same_endpoint_total 4990
telemt_me_writer_removed_unexpected_minus_restored_total 1596
telemt_user_connections_total{user="hello"} 187744
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 2858704064 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 67413194380 (62.78 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 10262.4 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79890
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 4447
telemt_upstream_connect_attempt_total 19111
telemt_upstream_connect_success_total 19110
telemt_upstream_connect_attempts_per_request{bucket="1"} 19110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 6751
telemt_me_reconnect_success_total 6742
telemt_me_reader_eof_total 9481
telemt_me_idle_close_by_peer_total 9479
telemt_me_route_drop_no_conn_total 28403
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 410
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 9481
telemt_me_writer_restored_same_endpoint_total 6740
telemt_me_writer_removed_unexpected_minus_restored_total 2741
telemt_user_connections_total{user="hello"} 70458
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 1170129028 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 24173018016 (22.51 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 10262.3 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153013
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 15550
telemt_upstream_connect_success_total 15421
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 921
telemt_me_reconnect_attempts_total 4270
telemt_me_reconnect_success_total 4245
telemt_me_reader_eof_total 5792
telemt_me_idle_close_by_peer_total 5789
telemt_me_route_drop_no_conn_total 62726
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 716
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 5892
telemt_me_writer_restored_same_endpoint_total 4238
telemt_me_writer_removed_unexpected_minus_restored_total 1654
telemt_user_connections_total{user="hello"} 141284
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 7759726132 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 40625049472 (37.84 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 10262.7 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161540
telemt_connections_bad_total 49079
telemt_handshake_timeouts_total 12797
telemt_upstream_connect_attempt_total 15127
telemt_upstream_connect_success_total 15085
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 15103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 4488
telemt_me_reconnect_success_total 4477
telemt_me_reader_eof_total 5676
telemt_me_idle_close_by_peer_total 5676
telemt_me_route_drop_no_conn_total 39510
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 5682
telemt_me_writer_restored_same_endpoint_total 4472
telemt_me_writer_removed_unexpected_minus_restored_total 1210
telemt_user_connections_total{user="hello"} 96695
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 1267842820 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 30519707336 (28.42 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 10261.3 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129438
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 848
telemt_upstream_connect_attempt_total 15293
telemt_upstream_connect_success_total 15191
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 15207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 646
telemt_me_reconnect_attempts_total 4503
telemt_me_reconnect_success_total 4483
telemt_me_reader_eof_total 6159
telemt_me_idle_close_by_peer_total 6158
telemt_me_route_drop_no_conn_total 47540
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 638
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 5
telemt_pool_force_close_total 221
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 6218
telemt_me_writer_restored_same_endpoint_total 4481
telemt_me_writer_removed_unexpected_minus_restored_total 1737
telemt_user_connections_total{user="hello"} 122441
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 8845320840 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 41786691032 (38.92 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 47
```