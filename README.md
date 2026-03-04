# Server Metrics 2026-03-04 05:43:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 30789.4 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236470
telemt_connections_bad_total 2413
telemt_handshake_timeouts_total 4820
telemt_upstream_connect_attempt_total 20966
telemt_upstream_connect_success_total 20869
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 20869
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 4602
telemt_me_reconnect_success_total 4582
telemt_me_reader_eof_total 4687
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 79722
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4687
telemt_me_writer_restored_same_endpoint_total 4562
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 223436
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 2332370744 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 73381348176 (68.34 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 30786.0 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109760
telemt_connections_bad_total 361
telemt_handshake_timeouts_total 21923
telemt_upstream_connect_attempt_total 69190
telemt_upstream_connect_success_total 68398
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 68392
telemt_upstream_connect_attempts_per_request{bucket="2"} 385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_keepalive_timeout_total 1012
telemt_me_reconnect_attempts_total 41628
telemt_me_reconnect_success_total 41599
telemt_me_reader_eof_total 42637
telemt_me_idle_close_by_peer_total 42636
telemt_me_route_drop_no_conn_total 35552
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 238
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 42698
telemt_me_writer_restored_same_endpoint_total 41578
telemt_me_writer_removed_unexpected_minus_restored_total 1120
telemt_user_connections_total{user="hello"} 81440
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 718545752 (685.26 MB)
telemt_user_octets_to_client{user="hello"} 34785128028 (32.40 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 30784.9 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246707
telemt_connections_bad_total 88266
telemt_handshake_timeouts_total 5159
telemt_upstream_connect_attempt_total 40869
telemt_upstream_connect_success_total 40614
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 40614
telemt_upstream_connect_attempts_per_request{bucket="2"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 530
telemt_me_reconnect_attempts_total 16535
telemt_me_reconnect_success_total 16490
telemt_me_reader_eof_total 17363
telemt_me_idle_close_by_peer_total 17360
telemt_me_route_drop_no_conn_total 52295
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 360
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 17371
telemt_me_writer_restored_same_endpoint_total 16469
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 146884
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 1073849164 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 38535165716 (35.89 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 30783.8 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125625
telemt_connections_bad_total 9137
telemt_handshake_timeouts_total 2259
telemt_upstream_connect_attempt_total 22854
telemt_upstream_connect_success_total 22765
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 22765
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 4361
telemt_me_reconnect_success_total 4357
telemt_me_reader_eof_total 4417
telemt_me_idle_close_by_peer_total 4417
telemt_me_route_drop_no_conn_total 38472
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 4417
telemt_me_writer_restored_same_endpoint_total 4336
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 108438
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 957321708 (912.97 MB)
telemt_user_octets_to_client{user="hello"} 40746908540 (37.95 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 30782.2 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262758
telemt_connections_bad_total 5434
telemt_handshake_timeouts_total 118867
telemt_upstream_connect_attempt_total 44679
telemt_upstream_connect_success_total 44374
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 44374
telemt_upstream_connect_attempts_per_request{bucket="2"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 614
telemt_me_reconnect_attempts_total 21378
telemt_me_reconnect_success_total 21367
telemt_me_reader_eof_total 22550
telemt_me_idle_close_by_peer_total 22549
telemt_me_route_drop_no_conn_total 59118
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 193
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22563
telemt_me_writer_restored_same_endpoint_total 21342
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 133855
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 1921243076 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 31214129756 (29.07 GB)
telemt_user_unique_ips_current{user="hello"} 22
```