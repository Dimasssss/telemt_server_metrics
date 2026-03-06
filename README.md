# Server Metrics 2026-03-06 21:04:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 10579.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215861
telemt_connections_bad_total 2199
telemt_handshake_timeouts_total 8680
telemt_upstream_connect_attempt_total 16485
telemt_upstream_connect_success_total 16333
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 16390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 5072
telemt_me_reconnect_success_total 5042
telemt_me_reader_eof_total 6529
telemt_me_idle_close_by_peer_total 6529
telemt_me_route_drop_no_conn_total 83856
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 741
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 3
telemt_pool_force_close_total 256
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6636
telemt_me_writer_restored_same_endpoint_total 5036
telemt_me_writer_removed_unexpected_minus_restored_total 1600
telemt_user_connections_total{user="hello"} 191798
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 2895360260 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 68619787180 (63.91 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 10579.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81521
telemt_connections_bad_total 54
telemt_handshake_timeouts_total 4638
telemt_upstream_connect_attempt_total 19786
telemt_upstream_connect_success_total 19785
telemt_upstream_connect_attempts_per_request{bucket="1"} 19785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6935
telemt_me_reconnect_success_total 6926
telemt_me_reader_eof_total 9730
telemt_me_idle_close_by_peer_total 9728
telemt_me_route_drop_no_conn_total 28964
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 432
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 9730
telemt_me_writer_restored_same_endpoint_total 6924
telemt_me_writer_removed_unexpected_minus_restored_total 2806
telemt_user_connections_total{user="hello"} 71859
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 1186557280 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 24699110188 (23.00 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 10579.2 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156320
telemt_connections_bad_total 376
telemt_handshake_timeouts_total 1952
telemt_upstream_connect_attempt_total 15847
telemt_upstream_connect_success_total 15719
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 925
telemt_me_reconnect_attempts_total 4330
telemt_me_reconnect_success_total 4305
telemt_me_reader_eof_total 5857
telemt_me_idle_close_by_peer_total 5854
telemt_me_route_drop_no_conn_total 63542
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 730
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 5
telemt_pool_force_close_total 190
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 5958
telemt_me_writer_restored_same_endpoint_total 4298
telemt_me_writer_removed_unexpected_minus_restored_total 1660
telemt_user_connections_total{user="hello"} 144523
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 8017824480 (7.47 GB)
telemt_user_octets_to_client{user="hello"} 41510545308 (38.66 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 10579.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164249
telemt_connections_bad_total 49364
telemt_handshake_timeouts_total 12933
telemt_upstream_connect_attempt_total 15888
telemt_upstream_connect_success_total 15846
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 15864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 4787
telemt_me_reconnect_success_total 4775
telemt_me_reader_eof_total 6090
telemt_me_idle_close_by_peer_total 6090
telemt_me_route_drop_no_conn_total 40494
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 142
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 6096
telemt_me_writer_restored_same_endpoint_total 4770
telemt_me_writer_removed_unexpected_minus_restored_total 1326
telemt_user_connections_total{user="hello"} 98986
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 1302387048 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 31310406528 (29.16 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 10578.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132577
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 876
telemt_upstream_connect_attempt_total 15566
telemt_upstream_connect_success_total 15463
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 15479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 646
telemt_me_reconnect_attempts_total 4519
telemt_me_reconnect_success_total 4498
telemt_me_reader_eof_total 6176
telemt_me_idle_close_by_peer_total 6175
telemt_me_route_drop_no_conn_total 48166
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 641
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 5
telemt_pool_force_close_total 221
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 6235
telemt_me_writer_restored_same_endpoint_total 4496
telemt_me_writer_removed_unexpected_minus_restored_total 1739
telemt_user_connections_total{user="hello"} 124987
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 8859405140 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 42629571428 (39.70 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 61
```