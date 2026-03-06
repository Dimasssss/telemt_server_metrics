# Server Metrics 2026-03-06 06:30:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 29361.9 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261801
telemt_connections_bad_total 16089
telemt_handshake_timeouts_total 3709
telemt_upstream_connect_attempt_total 29347
telemt_upstream_connect_success_total 29090
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 29090
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 10316
telemt_me_reconnect_success_total 10277
telemt_me_reader_eof_total 10626
telemt_me_idle_close_by_peer_total 10626
telemt_me_route_drop_no_conn_total 90284
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 562
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10628
telemt_me_writer_restored_same_endpoint_total 10271
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 230755
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 7376280024 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 84056395076 (78.28 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 29357.4 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109923
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 10225
telemt_upstream_connect_attempt_total 25015
telemt_upstream_connect_success_total 25013
telemt_upstream_connect_attempts_per_request{bucket="1"} 25013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 6777
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 6901
telemt_me_idle_close_by_peer_total 6901
telemt_me_route_drop_no_conn_total 31501
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 359
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6902
telemt_me_writer_restored_same_endpoint_total 6743
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 97590
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 1016427968 (969.34 MB)
telemt_user_octets_to_client{user="hello"} 32702419440 (30.46 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 29354.8 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187055
telemt_connections_bad_total 1756
telemt_handshake_timeouts_total 4611
telemt_upstream_connect_attempt_total 33080
telemt_upstream_connect_success_total 32841
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 32841
telemt_upstream_connect_attempts_per_request{bucket="2"} 109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 458
telemt_me_reconnect_attempts_total 12134
telemt_me_reconnect_success_total 12097
telemt_me_reader_eof_total 12652
telemt_me_idle_close_by_peer_total 12651
telemt_me_route_drop_no_conn_total 55843
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 353
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 12678
telemt_me_writer_restored_same_endpoint_total 12075
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 166418
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 1679635800 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 54570917248 (50.82 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 29351.3 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149479
telemt_connections_bad_total 13386
telemt_handshake_timeouts_total 6417
telemt_upstream_connect_attempt_total 21342
telemt_upstream_connect_success_total 21269
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21269
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 4849
telemt_me_reconnect_success_total 4818
telemt_me_reader_eof_total 4988
telemt_me_idle_close_by_peer_total 4988
telemt_me_route_drop_no_conn_total 49506
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 355
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4989
telemt_me_writer_restored_same_endpoint_total 4811
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 123596
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 1858432268 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 42406114472 (39.49 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 29350.1 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162708
telemt_connections_bad_total 3275
telemt_handshake_timeouts_total 916
telemt_upstream_connect_attempt_total 20499
telemt_upstream_connect_success_total 20452
telemt_upstream_connect_attempts_per_request{bucket="1"} 20452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 60964
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 352
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 9
telemt_pool_force_close_total 196
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 3818
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 155520
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 24136775852 (22.48 GB)
telemt_user_octets_to_client{user="hello"} 96367719820 (89.75 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 87
```