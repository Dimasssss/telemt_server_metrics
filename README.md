# Server Metrics 2026-03-06 04:28:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 21990.5 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157540
telemt_connections_bad_total 15941
telemt_handshake_timeouts_total 2897
telemt_upstream_connect_attempt_total 23518
telemt_upstream_connect_success_total 23335
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 23335
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 8707
telemt_me_reconnect_success_total 8677
telemt_me_reader_eof_total 8991
telemt_me_idle_close_by_peer_total 8991
telemt_me_route_drop_no_conn_total 44306
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 373
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8991
telemt_me_writer_restored_same_endpoint_total 8671
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 130802
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 3058395776 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 50629137012 (47.15 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 21986.0 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56439
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 773
telemt_upstream_connect_attempt_total 20346
telemt_upstream_connect_success_total 20344
telemt_upstream_connect_attempts_per_request{bucket="1"} 20344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 5118
telemt_me_reconnect_success_total 5102
telemt_me_reader_eof_total 5204
telemt_me_idle_close_by_peer_total 5204
telemt_me_route_drop_no_conn_total 16769
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 198
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5205
telemt_me_writer_restored_same_endpoint_total 5096
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 54495
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 446102996 (425.44 MB)
telemt_user_octets_to_client{user="hello"} 13760298708 (12.82 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 21983.3 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96605
telemt_connections_bad_total 983
telemt_handshake_timeouts_total 1802
telemt_upstream_connect_attempt_total 20625
telemt_upstream_connect_success_total 20449
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 20449
telemt_upstream_connect_attempts_per_request{bucket="2"} 79
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 243
telemt_me_reconnect_attempts_total 6236
telemt_me_reconnect_success_total 6213
telemt_me_reader_eof_total 6492
telemt_me_idle_close_by_peer_total 6492
telemt_me_route_drop_no_conn_total 27276
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6496
telemt_me_writer_restored_same_endpoint_total 6205
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 90752
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 917725652 (875.21 MB)
telemt_user_octets_to_client{user="hello"} 30734201604 (28.62 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 21980.0 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81206
telemt_connections_bad_total 3150
telemt_handshake_timeouts_total 4583
telemt_upstream_connect_attempt_total 14553
telemt_upstream_connect_success_total 14506
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 14506
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 2803
telemt_me_reconnect_success_total 2780
telemt_me_reader_eof_total 2885
telemt_me_idle_close_by_peer_total 2885
telemt_me_route_drop_no_conn_total 27957
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 220
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2885
telemt_me_writer_restored_same_endpoint_total 2773
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 69251
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1339124128 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 28308002816 (26.36 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 21978.9 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93735
telemt_connections_bad_total 1001
telemt_handshake_timeouts_total 597
telemt_upstream_connect_attempt_total 15443
telemt_upstream_connect_success_total 15412
telemt_upstream_connect_attempts_per_request{bucket="1"} 15412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 2761
telemt_me_reconnect_success_total 2751
telemt_me_reader_eof_total 2850
telemt_me_idle_close_by_peer_total 2850
telemt_me_route_drop_no_conn_total 31034
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2852
telemt_me_writer_restored_same_endpoint_total 2744
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 90605
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 23147811840 (21.56 GB)
telemt_user_octets_to_client{user="hello"} 51814647288 (48.26 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 53
```