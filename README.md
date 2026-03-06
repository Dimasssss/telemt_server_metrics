# Server Metrics 2026-03-06 06:10:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 28133.5 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241776
telemt_connections_bad_total 16055
telemt_handshake_timeouts_total 3585
telemt_upstream_connect_attempt_total 28316
telemt_upstream_connect_success_total 28071
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 28071
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 10073
telemt_me_reconnect_success_total 10034
telemt_me_reader_eof_total 10374
telemt_me_idle_close_by_peer_total 10374
telemt_me_route_drop_no_conn_total 80444
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 713
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10375
telemt_me_writer_restored_same_endpoint_total 10028
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 211880
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 6012087164 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 78133926584 (72.77 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 28128.9 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99529
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 7296
telemt_upstream_connect_attempt_total 24634
telemt_upstream_connect_success_total 24632
telemt_upstream_connect_attempts_per_request{bucket="1"} 24632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6772
telemt_me_reconnect_success_total 6745
telemt_me_reader_eof_total 6896
telemt_me_idle_close_by_peer_total 6896
telemt_me_route_drop_no_conn_total 28796
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 325
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 9
telemt_pool_force_close_total 175
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6897
telemt_me_writer_restored_same_endpoint_total 6739
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 90243
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 888455272 (847.30 MB)
telemt_user_octets_to_client{user="hello"} 30781303520 (28.67 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 28126.4 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172818
telemt_connections_bad_total 1587
telemt_handshake_timeouts_total 4173
telemt_upstream_connect_attempt_total 30554
telemt_upstream_connect_success_total 30342
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 30342
telemt_upstream_connect_attempts_per_request{bucket="2"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 10793
telemt_me_reconnect_success_total 10758
telemt_me_reader_eof_total 11227
telemt_me_idle_close_by_peer_total 11227
telemt_me_route_drop_no_conn_total 49941
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 322
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 11253
telemt_me_writer_restored_same_endpoint_total 10736
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 152944
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 1525240692 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 51038627836 (47.53 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 28123.0 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135619
telemt_connections_bad_total 9463
telemt_handshake_timeouts_total 6214
telemt_upstream_connect_attempt_total 20826
telemt_upstream_connect_success_total 20755
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 20755
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 4834
telemt_me_reconnect_success_total 4804
telemt_me_reader_eof_total 4972
telemt_me_idle_close_by_peer_total 4972
telemt_me_route_drop_no_conn_total 45719
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 331
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4973
telemt_me_writer_restored_same_endpoint_total 4797
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 114308
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 1736560740 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 40440291156 (37.66 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 28122.0 (7h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150098
telemt_connections_bad_total 2520
telemt_handshake_timeouts_total 873
telemt_upstream_connect_attempt_total 19483
telemt_upstream_connect_success_total 19438
telemt_upstream_connect_attempts_per_request{bucket="1"} 19438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 297
telemt_me_reconnect_attempts_total 3407
telemt_me_reconnect_success_total 3392
telemt_me_reader_eof_total 3500
telemt_me_idle_close_by_peer_total 3499
telemt_me_route_drop_no_conn_total 55694
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 306
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3515
telemt_me_writer_restored_same_endpoint_total 3385
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 143950
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 24018062832 (22.37 GB)
telemt_user_octets_to_client{user="hello"} 89595490668 (83.44 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 72
```