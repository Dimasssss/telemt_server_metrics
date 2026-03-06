# Server Metrics 2026-03-06 05:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 26904.8 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220037
telemt_connections_bad_total 16023
telemt_handshake_timeouts_total 3403
telemt_upstream_connect_attempt_total 27447
telemt_upstream_connect_success_total 27222
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 27222
telemt_upstream_connect_attempts_per_request{bucket="2"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 9895
telemt_me_reconnect_success_total 9857
telemt_me_reader_eof_total 10197
telemt_me_idle_close_by_peer_total 10197
telemt_me_route_drop_no_conn_total 69036
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 661
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 448
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10198
telemt_me_writer_restored_same_endpoint_total 9851
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 191156
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 5348618708 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 72415206224 (67.44 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 26900.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88112
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 4870
telemt_upstream_connect_attempt_total 24375
telemt_upstream_connect_success_total 24373
telemt_upstream_connect_attempts_per_request{bucket="1"} 24373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 6767
telemt_me_reconnect_success_total 6742
telemt_me_reader_eof_total 6893
telemt_me_idle_close_by_peer_total 6893
telemt_me_route_drop_no_conn_total 25763
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 8
telemt_pool_force_close_total 150
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6894
telemt_me_writer_restored_same_endpoint_total 6736
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 81449
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 800094404 (763.03 MB)
telemt_user_octets_to_client{user="hello"} 26461755088 (24.64 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 26897.7 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155064
telemt_connections_bad_total 1459
telemt_handshake_timeouts_total 3631
telemt_upstream_connect_attempt_total 28113
telemt_upstream_connect_success_total 27918
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 27918
telemt_upstream_connect_attempts_per_request{bucket="2"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 9528
telemt_me_reconnect_success_total 9497
telemt_me_reader_eof_total 9902
telemt_me_idle_close_by_peer_total 9902
telemt_me_route_drop_no_conn_total 44475
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 295
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 9907
telemt_me_writer_restored_same_endpoint_total 9489
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 137896
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 1265161064 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 45819001596 (42.67 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 26894.3 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118190
telemt_connections_bad_total 7723
telemt_handshake_timeouts_total 5793
telemt_upstream_connect_attempt_total 20394
telemt_upstream_connect_success_total 20326
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 20326
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 4691
telemt_me_reconnect_success_total 4662
telemt_me_reader_eof_total 4825
telemt_me_idle_close_by_peer_total 4825
telemt_me_route_drop_no_conn_total 41284
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 299
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 8
telemt_pool_force_close_total 170
telemt_me_writer_removed_unexpected_total 4825
telemt_me_writer_restored_same_endpoint_total 4655
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 99775
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 1619807720 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 37669593124 (35.08 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 26893.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135577
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 762
telemt_upstream_connect_attempt_total 18172
telemt_upstream_connect_success_total 18129
telemt_upstream_connect_attempts_per_request{bucket="1"} 18129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 3082
telemt_me_reconnect_success_total 3068
telemt_me_reader_eof_total 3172
telemt_me_idle_close_by_peer_total 3171
telemt_me_route_drop_no_conn_total 48704
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 259
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3176
telemt_me_writer_restored_same_endpoint_total 3061
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 131356
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 23845813512 (22.21 GB)
telemt_user_octets_to_client{user="hello"} 81073628800 (75.51 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 61
```