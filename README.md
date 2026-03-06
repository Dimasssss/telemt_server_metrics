# Server Metrics 2026-03-06 04:02:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 20454.8 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143243
telemt_connections_bad_total 15927
telemt_handshake_timeouts_total 2849
telemt_upstream_connect_attempt_total 22852
telemt_upstream_connect_success_total 22675
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 22675
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 8672
telemt_me_reconnect_success_total 8644
telemt_me_reader_eof_total 8957
telemt_me_idle_close_by_peer_total 8957
telemt_me_route_drop_no_conn_total 39648
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 353
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8957
telemt_me_writer_restored_same_endpoint_total 8638
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 116816
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 1990919236 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 44496526156 (41.44 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 20450.2 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49141
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 674
telemt_upstream_connect_attempt_total 17485
telemt_upstream_connect_success_total 17483
telemt_upstream_connect_attempts_per_request{bucket="1"} 17483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 3743
telemt_me_reconnect_success_total 3728
telemt_me_reader_eof_total 3790
telemt_me_idle_close_by_peer_total 3790
telemt_me_route_drop_no_conn_total 14638
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 159
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 3791
telemt_me_writer_restored_same_endpoint_total 3722
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 47467
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 338867344 (323.17 MB)
telemt_user_octets_to_client{user="hello"} 11749942072 (10.94 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 20447.5 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85468
telemt_connections_bad_total 792
telemt_handshake_timeouts_total 1633
telemt_upstream_connect_attempt_total 19382
telemt_upstream_connect_success_total 19220
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 19220
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 5898
telemt_me_reconnect_success_total 5877
telemt_me_reader_eof_total 6148
telemt_me_idle_close_by_peer_total 6148
telemt_me_route_drop_no_conn_total 24010
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 178
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6152
telemt_me_writer_restored_same_endpoint_total 5869
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 80172
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 824671644 (786.47 MB)
telemt_user_octets_to_client{user="hello"} 26955609048 (25.10 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 20444.4 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72207
telemt_connections_bad_total 1774
telemt_handshake_timeouts_total 4204
telemt_upstream_connect_attempt_total 13768
telemt_upstream_connect_success_total 13721
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 13721
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 2726
telemt_me_reconnect_success_total 2707
telemt_me_reader_eof_total 2809
telemt_me_idle_close_by_peer_total 2809
telemt_me_route_drop_no_conn_total 25771
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2809
telemt_me_writer_restored_same_endpoint_total 2700
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 62401
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 668023096 (637.08 MB)
telemt_user_octets_to_client{user="hello"} 26533171728 (24.71 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 20443.3 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83993
telemt_connections_bad_total 874
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 14544
telemt_upstream_connect_success_total 14517
telemt_upstream_connect_attempts_per_request{bucket="1"} 14517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 2520
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2610
telemt_me_route_drop_no_conn_total 27805
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 2612
telemt_me_writer_restored_same_endpoint_total 2514
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 81265
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 15849379664 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 47588880068 (44.32 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 40
```