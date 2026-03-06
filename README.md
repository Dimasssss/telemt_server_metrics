# Server Metrics 2026-03-06 20:48:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 9645.9 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202882
telemt_connections_bad_total 2199
telemt_handshake_timeouts_total 8674
telemt_upstream_connect_attempt_total 15059
telemt_upstream_connect_success_total 14913
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 14965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 4625
telemt_me_reconnect_success_total 4598
telemt_me_reader_eof_total 5929
telemt_me_idle_close_by_peer_total 5929
telemt_me_route_drop_no_conn_total 79704
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 698
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 2
telemt_pool_force_close_total 185
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 6036
telemt_me_writer_restored_same_endpoint_total 4592
telemt_me_writer_removed_unexpected_minus_restored_total 1444
telemt_user_connections_total{user="hello"} 179008
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 2759592452 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 64256196644 (59.84 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 9646.0 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76109
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 3946
telemt_upstream_connect_attempt_total 18412
telemt_upstream_connect_success_total 18410
telemt_upstream_connect_attempts_per_request{bucket="1"} 18410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 6701
telemt_me_reconnect_success_total 6693
telemt_me_reader_eof_total 9425
telemt_me_idle_close_by_peer_total 9423
telemt_me_route_drop_no_conn_total 27175
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 375
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 35
telemt_me_writer_removed_unexpected_total 9425
telemt_me_writer_restored_same_endpoint_total 6691
telemt_me_writer_removed_unexpected_minus_restored_total 2734
telemt_user_connections_total{user="hello"} 67263
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 1145707400 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 23205637604 (21.61 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 9645.8 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146900
telemt_connections_bad_total 360
telemt_handshake_timeouts_total 1865
telemt_upstream_connect_attempt_total 14414
telemt_upstream_connect_success_total 14292
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 14324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 887
telemt_me_reconnect_attempts_total 3850
telemt_me_reconnect_success_total 3826
telemt_me_reader_eof_total 5232
telemt_me_idle_close_by_peer_total 5229
telemt_me_route_drop_no_conn_total 60618
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 5332
telemt_me_writer_restored_same_endpoint_total 3819
telemt_me_writer_removed_unexpected_minus_restored_total 1513
telemt_user_connections_total{user="hello"} 135306
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 7270409008 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 38328996072 (35.70 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 9646.3 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155514
telemt_connections_bad_total 48528
telemt_handshake_timeouts_total 11733
telemt_upstream_connect_attempt_total 14088
telemt_upstream_connect_success_total 14049
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 14066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 4261
telemt_me_reconnect_success_total 4250
telemt_me_reader_eof_total 5408
telemt_me_idle_close_by_peer_total 5408
telemt_me_route_drop_no_conn_total 38073
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 116
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 5
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 5414
telemt_me_writer_restored_same_endpoint_total 4245
telemt_me_writer_removed_unexpected_minus_restored_total 1169
telemt_user_connections_total{user="hello"} 92376
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 1209750448 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 29794062072 (27.75 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 9644.7 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123805
telemt_connections_bad_total 452
telemt_handshake_timeouts_total 778
telemt_upstream_connect_attempt_total 14789
telemt_upstream_connect_success_total 14690
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 14706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 643
telemt_me_reconnect_attempts_total 4468
telemt_me_reconnect_success_total 4448
telemt_me_reader_eof_total 6123
telemt_me_idle_close_by_peer_total 6122
telemt_me_route_drop_no_conn_total 46334
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 618
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 156
telemt_me_writer_removed_unexpected_total 6182
telemt_me_writer_restored_same_endpoint_total 4446
telemt_me_writer_removed_unexpected_minus_restored_total 1736
telemt_user_connections_total{user="hello"} 117581
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 8805276964 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 40488737848 (37.71 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 55
```