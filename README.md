# Server Metrics 2026-03-06 06:15:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 28440.4 (7h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245889
telemt_connections_bad_total 16058
telemt_handshake_timeouts_total 3603
telemt_upstream_connect_attempt_total 28593
telemt_upstream_connect_success_total 28346
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 28346
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 10166
telemt_me_reconnect_success_total 10127
telemt_me_reader_eof_total 10474
telemt_me_idle_close_by_peer_total 10474
telemt_me_route_drop_no_conn_total 83183
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 717
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10475
telemt_me_writer_restored_same_endpoint_total 10121
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 215872
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 6384116792 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 79289879192 (73.84 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 28435.8 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102081
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 8112
telemt_upstream_connect_attempt_total 24761
telemt_upstream_connect_success_total 24759
telemt_upstream_connect_attempts_per_request{bucket="1"} 24759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6772
telemt_me_reconnect_success_total 6745
telemt_me_reader_eof_total 6896
telemt_me_idle_close_by_peer_total 6896
telemt_me_route_drop_no_conn_total 29733
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 329
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 9
telemt_pool_force_close_total 175
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6897
telemt_me_writer_restored_same_endpoint_total 6739
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 91940
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 910481740 (868.30 MB)
telemt_user_octets_to_client{user="hello"} 31300844144 (29.15 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 28433.3 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176232
telemt_connections_bad_total 1587
telemt_handshake_timeouts_total 4339
telemt_upstream_connect_attempt_total 31188
telemt_upstream_connect_success_total 30975
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 30975
telemt_upstream_connect_attempts_per_request{bucket="2"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 11151
telemt_me_reconnect_success_total 11116
telemt_me_reader_eof_total 11607
telemt_me_idle_close_by_peer_total 11606
telemt_me_route_drop_no_conn_total 51398
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 328
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 11633
telemt_me_writer_restored_same_endpoint_total 11094
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 156159
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1551375120 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 52160001148 (48.58 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 28430.0 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139259
telemt_connections_bad_total 10448
telemt_handshake_timeouts_total 6289
telemt_upstream_connect_attempt_total 20912
telemt_upstream_connect_success_total 20841
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 20841
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 4836
telemt_me_reconnect_success_total 4805
telemt_me_reader_eof_total 4974
telemt_me_idle_close_by_peer_total 4974
telemt_me_route_drop_no_conn_total 46733
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
telemt_me_writer_removed_unexpected_total 4975
telemt_me_writer_restored_same_endpoint_total 4798
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 116769
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 1757489068 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 40981774444 (38.17 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 28428.9 (7h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153471
telemt_connections_bad_total 2991
telemt_handshake_timeouts_total 883
telemt_upstream_connect_attempt_total 19848
telemt_upstream_connect_success_total 19802
telemt_upstream_connect_attempts_per_request{bucket="1"} 19802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3524
telemt_me_reconnect_success_total 3508
telemt_me_reader_eof_total 3621
telemt_me_idle_close_by_peer_total 3620
telemt_me_route_drop_no_conn_total 57129
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 312
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 184
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3636
telemt_me_writer_restored_same_endpoint_total 3501
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 146798
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 24041943524 (22.39 GB)
telemt_user_octets_to_client{user="hello"} 91463173228 (85.18 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 70
```