# Server Metrics 2026-03-06 07:16:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 32126.5 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319067
telemt_connections_bad_total 16182
telemt_handshake_timeouts_total 3922
telemt_upstream_connect_attempt_total 32251
telemt_upstream_connect_success_total 31931
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 31931
telemt_upstream_connect_attempts_per_request{bucket="2"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 11224
telemt_me_reconnect_success_total 11177
telemt_me_reader_eof_total 11562
telemt_me_idle_close_by_peer_total 11562
telemt_me_route_drop_no_conn_total 111072
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1084
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 750
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11565
telemt_me_writer_restored_same_endpoint_total 11171
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 280198
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 9571506340 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 101823683336 (94.83 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 32121.9 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136106
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 14788
telemt_upstream_connect_attempt_total 26010
telemt_upstream_connect_success_total 26008
telemt_upstream_connect_attempts_per_request{bucket="1"} 26008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6765
telemt_me_reader_eof_total 6916
telemt_me_idle_close_by_peer_total 6916
telemt_me_route_drop_no_conn_total 40421
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 429
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6917
telemt_me_writer_restored_same_endpoint_total 6758
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 118652
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 1340370928 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 37779390900 (35.18 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 32119.2 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239931
telemt_connections_bad_total 1792
telemt_handshake_timeouts_total 7186
telemt_upstream_connect_attempt_total 36546
telemt_upstream_connect_success_total 36272
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 36272
telemt_upstream_connect_attempts_per_request{bucket="2"} 124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 516
telemt_me_reconnect_attempts_total 14112
telemt_me_reconnect_success_total 14072
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14723
telemt_me_route_drop_no_conn_total 71041
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 507
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 226
telemt_me_writer_removed_unexpected_total 14753
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 211294
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 2178305760 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 66672287380 (62.09 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 32116.0 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182630
telemt_connections_bad_total 22229
telemt_handshake_timeouts_total 7204
telemt_upstream_connect_attempt_total 22620
telemt_upstream_connect_success_total 22541
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 22541
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 4964
telemt_me_reconnect_success_total 4931
telemt_me_reader_eof_total 5102
telemt_me_idle_close_by_peer_total 5102
telemt_me_route_drop_no_conn_total 57696
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 429
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5103
telemt_me_writer_restored_same_endpoint_total 4924
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 146265
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 2071178696 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 51699494712 (48.15 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 32115.0 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195722
telemt_connections_bad_total 3281
telemt_handshake_timeouts_total 1109
telemt_upstream_connect_attempt_total 21445
telemt_upstream_connect_success_total 21395
telemt_upstream_connect_attempts_per_request{bucket="1"} 21395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 3737
telemt_me_reconnect_success_total 3719
telemt_me_reader_eof_total 3837
telemt_me_idle_close_by_peer_total 3836
telemt_me_route_drop_no_conn_total 78655
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 439
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3852
telemt_me_writer_restored_same_endpoint_total 3712
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 187600
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 24488929820 (22.81 GB)
telemt_user_octets_to_client{user="hello"} 113210172680 (105.44 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 76
```