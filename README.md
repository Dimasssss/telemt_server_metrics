# Server Metrics 2026-03-06 21:30:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 12121.7 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230984
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 8942
telemt_upstream_connect_attempt_total 18183
telemt_upstream_connect_success_total 18027
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 18085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 958
telemt_me_reconnect_attempts_total 5356
telemt_me_reconnect_success_total 5324
telemt_me_reader_eof_total 6871
telemt_me_idle_close_by_peer_total 6871
telemt_me_route_drop_no_conn_total 88189
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 783
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 555
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 6978
telemt_me_writer_restored_same_endpoint_total 5318
telemt_me_writer_removed_unexpected_minus_restored_total 1660
telemt_user_connections_total{user="hello"} 206475
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 3037750024 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 74659188544 (69.53 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 12121.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88743
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 5876
telemt_upstream_connect_attempt_total 21903
telemt_upstream_connect_success_total 21902
telemt_upstream_connect_attempts_per_request{bucket="1"} 21902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 355
telemt_me_reconnect_attempts_total 7315
telemt_me_reconnect_success_total 7305
telemt_me_reader_eof_total 10229
telemt_me_idle_close_by_peer_total 10227
telemt_me_route_drop_no_conn_total 32282
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 532
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 10229
telemt_me_writer_restored_same_endpoint_total 7303
telemt_me_writer_removed_unexpected_minus_restored_total 2926
telemt_user_connections_total{user="hello"} 77680
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1252466172 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 25805757912 (24.03 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 12121.4 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171310
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 2180
telemt_upstream_connect_attempt_total 18592
telemt_upstream_connect_success_total 18457
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 960
telemt_me_reconnect_attempts_total 5318
telemt_me_reconnect_success_total 5292
telemt_me_reader_eof_total 7103
telemt_me_idle_close_by_peer_total 7100
telemt_me_route_drop_no_conn_total 67707
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 786
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 6
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7204
telemt_me_writer_restored_same_endpoint_total 5285
telemt_me_writer_removed_unexpected_minus_restored_total 1919
telemt_user_connections_total{user="hello"} 158872
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 9170271024 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 45318346332 (42.21 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 12121.9 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175973
telemt_connections_bad_total 50744
telemt_handshake_timeouts_total 13488
telemt_upstream_connect_attempt_total 19561
telemt_upstream_connect_success_total 19517
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 6316
telemt_me_reconnect_success_total 6302
telemt_me_reader_eof_total 8249
telemt_me_idle_close_by_peer_total 8249
telemt_me_route_drop_no_conn_total 44136
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 152
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 6
telemt_pool_force_close_total 247
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8254
telemt_me_writer_restored_same_endpoint_total 6297
telemt_me_writer_removed_unexpected_minus_restored_total 1957
telemt_user_connections_total{user="hello"} 108620
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 1530169284 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 34256805288 (31.90 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 12120.3 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145669
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 1020
telemt_upstream_connect_attempt_total 18538
telemt_upstream_connect_success_total 18420
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 18439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 701
telemt_me_reconnect_attempts_total 5679
telemt_me_reconnect_success_total 5653
telemt_me_reader_eof_total 7635
telemt_me_idle_close_by_peer_total 7634
telemt_me_route_drop_no_conn_total 51086
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 706
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 5
telemt_pool_force_close_total 222
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 7697
telemt_me_writer_restored_same_endpoint_total 5651
telemt_me_writer_removed_unexpected_minus_restored_total 2046
telemt_user_connections_total{user="hello"} 135167
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 9189610424 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 45733500104 (42.59 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```