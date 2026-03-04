# Server Metrics 2026-03-04 05:38:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 30482.1 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231986
telemt_connections_bad_total 2406
telemt_handshake_timeouts_total 4698
telemt_upstream_connect_attempt_total 20866
telemt_upstream_connect_success_total 20773
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20773
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 4602
telemt_me_reconnect_success_total 4582
telemt_me_reader_eof_total 4687
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 75415
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 607
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4687
telemt_me_writer_restored_same_endpoint_total 4562
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 219090
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 2289319692 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 72457213032 (67.48 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 30478.7 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107952
telemt_connections_bad_total 357
telemt_handshake_timeouts_total 21878
telemt_upstream_connect_attempt_total 68527
telemt_upstream_connect_success_total 67743
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 67737
telemt_upstream_connect_attempts_per_request{bucket="2"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_keepalive_timeout_total 1010
telemt_me_reconnect_attempts_total 41260
telemt_me_reconnect_success_total 41231
telemt_me_reader_eof_total 42263
telemt_me_idle_close_by_peer_total 42262
telemt_me_route_drop_no_conn_total 34714
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 234
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 42324
telemt_me_writer_restored_same_endpoint_total 41210
telemt_me_writer_removed_unexpected_minus_restored_total 1114
telemt_user_connections_total{user="hello"} 79769
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 703115364 (670.54 MB)
telemt_user_octets_to_client{user="hello"} 33874626424 (31.55 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 30477.5 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242130
telemt_connections_bad_total 87475
telemt_handshake_timeouts_total 5083
telemt_upstream_connect_attempt_total 40333
telemt_upstream_connect_success_total 40082
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40082
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 522
telemt_me_reconnect_attempts_total 16302
telemt_me_reconnect_success_total 16259
telemt_me_reader_eof_total 17119
telemt_me_idle_close_by_peer_total 17116
telemt_me_route_drop_no_conn_total 50986
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 350
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 17127
telemt_me_writer_restored_same_endpoint_total 16238
telemt_me_writer_removed_unexpected_minus_restored_total 889
telemt_user_connections_total{user="hello"} 144166
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1045131724 (996.72 MB)
telemt_user_octets_to_client{user="hello"} 37912636868 (35.31 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 30476.3 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122893
telemt_connections_bad_total 8861
telemt_handshake_timeouts_total 2036
telemt_upstream_connect_attempt_total 22347
telemt_upstream_connect_success_total 22258
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 22258
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4142
telemt_me_reconnect_success_total 4138
telemt_me_reader_eof_total 4190
telemt_me_idle_close_by_peer_total 4190
telemt_me_route_drop_no_conn_total 37815
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 137
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 4190
telemt_me_writer_restored_same_endpoint_total 4117
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 106223
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 932078956 (888.90 MB)
telemt_user_octets_to_client{user="hello"} 39385144572 (36.68 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 30475.2 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259311
telemt_connections_bad_total 5433
telemt_handshake_timeouts_total 117264
telemt_upstream_connect_attempt_total 44550
telemt_upstream_connect_success_total 44255
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 44255
telemt_upstream_connect_attempts_per_request{bucket="2"} 138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 613
telemt_me_reconnect_attempts_total 21378
telemt_me_reconnect_success_total 21367
telemt_me_reader_eof_total 22550
telemt_me_idle_close_by_peer_total 22549
telemt_me_route_drop_no_conn_total 58547
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 191
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22563
telemt_me_writer_restored_same_endpoint_total 21342
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 131975
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 1895002012 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 30591718792 (28.49 GB)
telemt_user_unique_ips_current{user="hello"} 32
```