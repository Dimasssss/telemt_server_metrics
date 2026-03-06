# Server Metrics 2026-03-06 06:56:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 30897.7 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291457
telemt_connections_bad_total 16112
telemt_handshake_timeouts_total 3838
telemt_upstream_connect_attempt_total 30818
telemt_upstream_connect_success_total 30531
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 30531
telemt_upstream_connect_attempts_per_request{bucket="2"} 129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 10724
telemt_me_reconnect_success_total 10680
telemt_me_reader_eof_total 11045
telemt_me_idle_close_by_peer_total 11045
telemt_me_route_drop_no_conn_total 99780
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 991
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 688
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 11047
telemt_me_writer_restored_same_endpoint_total 10674
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 257008
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 9065045420 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 94736194208 (88.23 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 30893.1 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124167
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 13394
telemt_upstream_connect_attempt_total 25580
telemt_upstream_connect_success_total 25578
telemt_upstream_connect_attempts_per_request{bucket="1"} 25578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 6784
telemt_me_reconnect_success_total 6756
telemt_me_reader_eof_total 6907
telemt_me_idle_close_by_peer_total 6907
telemt_me_route_drop_no_conn_total 35042
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 398
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6908
telemt_me_writer_restored_same_endpoint_total 6749
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 108358
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1265001096 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35297697536 (32.87 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 30890.6 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207929
telemt_connections_bad_total 1772
telemt_handshake_timeouts_total 5163
telemt_upstream_connect_attempt_total 36402
telemt_upstream_connect_success_total 36145
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 36145
telemt_upstream_connect_attempts_per_request{bucket="2"} 116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 515
telemt_me_reconnect_attempts_total 14112
telemt_me_reconnect_success_total 14072
telemt_me_reader_eof_total 14725
telemt_me_idle_close_by_peer_total 14723
telemt_me_route_drop_no_conn_total 63011
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 413
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 9
telemt_me_writer_removed_unexpected_total 14753
telemt_me_writer_restored_same_endpoint_total 14050
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 185077
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 1880525368 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 60597085608 (56.44 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 30887.1 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166901
telemt_connections_bad_total 18310
telemt_handshake_timeouts_total 6558
telemt_upstream_connect_attempt_total 21957
telemt_upstream_connect_success_total 21882
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 21882
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 236
telemt_me_reconnect_attempts_total 4889
telemt_me_reconnect_success_total 4856
telemt_me_reader_eof_total 5027
telemt_me_idle_close_by_peer_total 5027
telemt_me_route_drop_no_conn_total 53594
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 412
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5028
telemt_me_writer_restored_same_endpoint_total 4849
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 135560
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1942727868 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 45395389628 (42.28 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 30886.2 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180381
telemt_connections_bad_total 3278
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 20861
telemt_upstream_connect_success_total 20814
telemt_upstream_connect_attempts_per_request{bucket="1"} 20814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 3707
telemt_me_reconnect_success_total 3690
telemt_me_reader_eof_total 3808
telemt_me_idle_close_by_peer_total 3807
telemt_me_route_drop_no_conn_total 69140
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 403
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3823
telemt_me_writer_restored_same_endpoint_total 3683
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 172649
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 24363717792 (22.69 GB)
telemt_user_octets_to_client{user="hello"} 105345637700 (98.11 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 88
```