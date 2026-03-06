# Server Metrics 2026-03-06 19:57:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 6556.1 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155086
telemt_connections_bad_total 1566
telemt_handshake_timeouts_total 6042
telemt_upstream_connect_attempt_total 10202
telemt_upstream_connect_success_total 10105
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 311
telemt_me_reconnect_attempts_total 3323
telemt_me_reconnect_success_total 3308
telemt_me_reader_eof_total 4324
telemt_me_idle_close_by_peer_total 4324
telemt_me_route_drop_no_conn_total 62029
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 581
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 2
telemt_pool_force_close_total 182
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4348
telemt_me_writer_restored_same_endpoint_total 3302
telemt_me_writer_removed_unexpected_minus_restored_total 1046
telemt_user_connections_total{user="hello"} 135516
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 2147306776 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 45818644784 (42.67 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 6556.0 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56089
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 2435
telemt_upstream_connect_attempt_total 12253
telemt_upstream_connect_success_total 12252
telemt_upstream_connect_attempts_per_request{bucket="1"} 12252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 4355
telemt_me_reconnect_success_total 4350
telemt_me_reader_eof_total 5843
telemt_me_idle_close_by_peer_total 5841
telemt_me_route_drop_no_conn_total 20327
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 241
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 5843
telemt_me_writer_restored_same_endpoint_total 4348
telemt_me_writer_removed_unexpected_minus_restored_total 1495
telemt_user_connections_total{user="hello"} 49598
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 982637616 (937.12 MB)
telemt_user_octets_to_client{user="hello"} 15116922680 (14.08 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 6556.0 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105543
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1171
telemt_upstream_connect_attempt_total 8512
telemt_upstream_connect_success_total 8454
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 528
telemt_me_reconnect_attempts_total 1880
telemt_me_reconnect_success_total 1870
telemt_me_reader_eof_total 2532
telemt_me_idle_close_by_peer_total 2531
telemt_me_route_drop_no_conn_total 34013
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 476
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2588
telemt_me_writer_restored_same_endpoint_total 1863
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 97852
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 4668025088 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 27410775184 (25.53 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 6556.5 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122326
telemt_connections_bad_total 44551
telemt_handshake_timeouts_total 7648
telemt_upstream_connect_attempt_total 9197
telemt_upstream_connect_success_total 9164
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 9179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 2739
telemt_me_reconnect_success_total 2730
telemt_me_reader_eof_total 3476
telemt_me_idle_close_by_peer_total 3476
telemt_me_route_drop_no_conn_total 23491
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_pool_stale_pick_total 447
telemt_me_writer_removed_unexpected_total 3478
telemt_me_writer_restored_same_endpoint_total 2726
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 67815
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 938806408 (895.32 MB)
telemt_user_octets_to_client{user="hello"} 23504093468 (21.89 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 6554.8 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93043
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 482
telemt_upstream_connect_attempt_total 9505
telemt_upstream_connect_success_total 9454
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 9466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 430
telemt_me_reconnect_attempts_total 2839
telemt_me_reconnect_success_total 2828
telemt_me_reader_eof_total 3837
telemt_me_idle_close_by_peer_total 3836
telemt_me_route_drop_no_conn_total 34894
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 495
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3873
telemt_me_writer_restored_same_endpoint_total 2826
telemt_me_writer_removed_unexpected_minus_restored_total 1047
telemt_user_connections_total{user="hello"} 88145
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 8436977344 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 32744749580 (30.50 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 47
```