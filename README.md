# Server Metrics 2026-03-06 21:19:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 11505.2 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225955
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 8895
telemt_upstream_connect_attempt_total 17288
telemt_upstream_connect_success_total 17133
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 940
telemt_me_reconnect_attempts_total 5167
telemt_me_reconnect_success_total 5136
telemt_me_reader_eof_total 6641
telemt_me_idle_close_by_peer_total 6641
telemt_me_route_drop_no_conn_total 86607
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 768
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6748
telemt_me_writer_restored_same_endpoint_total 5130
telemt_me_writer_removed_unexpected_minus_restored_total 1618
telemt_user_connections_total{user="hello"} 201559
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 3000356992 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 73186861192 (68.16 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 11505.2 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85927
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 5377
telemt_upstream_connect_attempt_total 21149
telemt_upstream_connect_success_total 21147
telemt_upstream_connect_attempts_per_request{bucket="1"} 21147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 7235
telemt_me_reconnect_success_total 7226
telemt_me_reader_eof_total 10133
telemt_me_idle_close_by_peer_total 10131
telemt_me_route_drop_no_conn_total 30834
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 489
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 5
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10133
telemt_me_writer_restored_same_endpoint_total 7224
telemt_me_writer_removed_unexpected_minus_restored_total 2909
telemt_user_connections_total{user="hello"} 75425
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 1229604168 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 25496353172 (23.75 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 11504.9 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165705
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 2082
telemt_upstream_connect_attempt_total 17495
telemt_upstream_connect_success_total 17362
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 17397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 941
telemt_me_reconnect_attempts_total 4961
telemt_me_reconnect_success_total 4936
telemt_me_reader_eof_total 6622
telemt_me_idle_close_by_peer_total 6619
telemt_me_route_drop_no_conn_total 66098
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 759
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 578
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 6723
telemt_me_writer_restored_same_endpoint_total 4929
telemt_me_writer_removed_unexpected_minus_restored_total 1794
telemt_user_connections_total{user="hello"} 153498
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 8727517504 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 43910364080 (40.89 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 11505.5 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171092
telemt_connections_bad_total 50194
telemt_handshake_timeouts_total 12990
telemt_upstream_connect_attempt_total 18373
telemt_upstream_connect_success_total 18329
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 18348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 5856
telemt_me_reconnect_success_total 5842
telemt_me_reader_eof_total 7602
telemt_me_idle_close_by_peer_total 7602
telemt_me_route_drop_no_conn_total 42964
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 147
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 7607
telemt_me_writer_restored_same_endpoint_total 5837
telemt_me_writer_removed_unexpected_minus_restored_total 1770
telemt_user_connections_total{user="hello"} 104838
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 1489460560 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 32953691064 (30.69 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 11504.0 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141179
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 966
telemt_upstream_connect_attempt_total 17051
telemt_upstream_connect_success_total 16941
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 16957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 664
telemt_me_reconnect_attempts_total 5081
telemt_me_reconnect_success_total 5060
telemt_me_reader_eof_total 6835
telemt_me_idle_close_by_peer_total 6834
telemt_me_route_drop_no_conn_total 49891
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 689
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 6895
telemt_me_writer_restored_same_endpoint_total 5058
telemt_me_writer_removed_unexpected_minus_restored_total 1837
telemt_user_connections_total{user="hello"} 131838
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 9173418440 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 44701326940 (41.63 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 48
```