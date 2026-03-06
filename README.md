# Server Metrics 2026-03-06 03:11:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 17383.1 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118700
telemt_connections_bad_total 15912
telemt_handshake_timeouts_total 2146
telemt_upstream_connect_attempt_total 17158
telemt_upstream_connect_success_total 16998
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 16998
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 5521
telemt_me_reconnect_success_total 5500
telemt_me_reader_eof_total 5681
telemt_me_idle_close_by_peer_total 5681
telemt_me_route_drop_no_conn_total 32041
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 326
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 2
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 5681
telemt_me_writer_restored_same_endpoint_total 5494
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 94093
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 1086491600 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 37080772944 (34.53 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 17378.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39128
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 12918
telemt_upstream_connect_success_total 12916
telemt_upstream_connect_attempts_per_request{bucket="1"} 12916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 2082
telemt_me_reconnect_success_total 2072
telemt_me_reader_eof_total 2098
telemt_me_idle_close_by_peer_total 2098
telemt_me_route_drop_no_conn_total 11526
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2099
telemt_me_writer_restored_same_endpoint_total 2066
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 37953
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 256509232 (244.63 MB)
telemt_user_octets_to_client{user="hello"} 9334239204 (8.69 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 17376.0 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71143
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 16111
telemt_upstream_connect_success_total 15971
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15971
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 4662
telemt_me_reconnect_success_total 4644
telemt_me_reader_eof_total 4855
telemt_me_idle_close_by_peer_total 4855
telemt_me_route_drop_no_conn_total 19798
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4859
telemt_me_writer_restored_same_endpoint_total 4637
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 66357
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 662464776 (631.78 MB)
telemt_user_octets_to_client{user="hello"} 23063559292 (21.48 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 17372.5 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56462
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 3192
telemt_upstream_connect_attempt_total 11638
telemt_upstream_connect_success_total 11601
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 11601
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 2365
telemt_me_reconnect_success_total 2350
telemt_me_reader_eof_total 2447
telemt_me_idle_close_by_peer_total 2447
telemt_me_route_drop_no_conn_total 21913
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 161
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2447
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 49922
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 440290340 (419.89 MB)
telemt_user_octets_to_client{user="hello"} 23735738776 (22.11 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 17371.6 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69718
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 10478
telemt_upstream_connect_success_total 10454
telemt_upstream_connect_attempts_per_request{bucket="1"} 10454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 1153
telemt_me_reconnect_success_total 1148
telemt_me_reader_eof_total 1172
telemt_me_idle_close_by_peer_total 1172
telemt_me_route_drop_no_conn_total 21815
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1172
telemt_me_writer_restored_same_endpoint_total 1142
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 67443
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 12096666824 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 34881478108 (32.49 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 31
```