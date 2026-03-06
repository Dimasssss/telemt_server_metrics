# Server Metrics 2026-03-06 05:55:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 27212.1 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224703
telemt_connections_bad_total 16035
telemt_handshake_timeouts_total 3430
telemt_upstream_connect_attempt_total 27625
telemt_upstream_connect_success_total 27390
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 27390
telemt_upstream_connect_attempts_per_request{bucket="2"} 111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 278
telemt_me_reconnect_attempts_total 9907
telemt_me_reconnect_success_total 9869
telemt_me_reader_eof_total 10209
telemt_me_idle_close_by_peer_total 10209
telemt_me_route_drop_no_conn_total 70597
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 669
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 452
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10210
telemt_me_writer_restored_same_endpoint_total 9863
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 195606
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 5400459720 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 73550646864 (68.50 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 27207.5 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90790
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 5445
telemt_upstream_connect_attempt_total 24485
telemt_upstream_connect_success_total 24483
telemt_upstream_connect_attempts_per_request{bucket="1"} 24483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 6771
telemt_me_reconnect_success_total 6744
telemt_me_reader_eof_total 6895
telemt_me_idle_close_by_peer_total 6895
telemt_me_route_drop_no_conn_total 26530
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 118
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 322
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 9
telemt_pool_force_close_total 175
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6896
telemt_me_writer_restored_same_endpoint_total 6738
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 83520
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 817982732 (780.09 MB)
telemt_user_octets_to_client{user="hello"} 27282851108 (25.41 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 27204.8 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158850
telemt_connections_bad_total 1524
telemt_handshake_timeouts_total 3704
telemt_upstream_connect_attempt_total 28692
telemt_upstream_connect_success_total 28485
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 28485
telemt_upstream_connect_attempts_per_request{bucket="2"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 9816
telemt_me_reconnect_success_total 9784
telemt_me_reader_eof_total 10203
telemt_me_idle_close_by_peer_total 10203
telemt_me_route_drop_no_conn_total 45671
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 10208
telemt_me_writer_restored_same_endpoint_total 9776
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 141430
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 1409409428 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 46869576564 (43.65 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 27201.5 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121020
telemt_connections_bad_total 8005
telemt_handshake_timeouts_total 5813
telemt_upstream_connect_attempt_total 20728
telemt_upstream_connect_success_total 20660
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 20660
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 4831
telemt_me_reconnect_success_total 4802
telemt_me_reader_eof_total 4971
telemt_me_idle_close_by_peer_total 4971
telemt_me_route_drop_no_conn_total 42399
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 307
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4971
telemt_me_writer_restored_same_endpoint_total 4795
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 102231
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 1631673008 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 38367280532 (35.73 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 27200.5 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138599
telemt_connections_bad_total 1105
telemt_handshake_timeouts_total 809
telemt_upstream_connect_attempt_total 18502
telemt_upstream_connect_success_total 18459
telemt_upstream_connect_attempts_per_request{bucket="1"} 18459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 3152
telemt_me_reconnect_success_total 3137
telemt_me_reader_eof_total 3245
telemt_me_idle_close_by_peer_total 3244
telemt_me_route_drop_no_conn_total 50066
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 273
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3249
telemt_me_writer_restored_same_endpoint_total 3130
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 134189
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 23885506108 (22.25 GB)
telemt_user_octets_to_client{user="hello"} 82783145324 (77.10 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 77
```