# Server Metrics 2026-03-04 03:56:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 24338.9 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158592
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2866
telemt_upstream_connect_attempt_total 18118
telemt_upstream_connect_success_total 18043
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 18043
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 4281
telemt_me_reconnect_success_total 4267
telemt_me_reader_eof_total 4368
telemt_me_idle_close_by_peer_total 4368
telemt_me_route_drop_no_conn_total 53298
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 378
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4368
telemt_me_writer_restored_same_endpoint_total 4247
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 150606
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 1484503592 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 46963213392 (43.74 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 24335.5 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75149
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 19798
telemt_upstream_connect_attempt_total 60661
telemt_upstream_connect_success_total 60071
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 60065
telemt_upstream_connect_attempts_per_request{bucket="2"} 285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 944
telemt_me_reconnect_attempts_total 38382
telemt_me_reconnect_success_total 38357
telemt_me_reader_eof_total 39331
telemt_me_idle_close_by_peer_total 39330
telemt_me_route_drop_no_conn_total 23549
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 186
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39392
telemt_me_writer_restored_same_endpoint_total 38336
telemt_me_writer_removed_unexpected_minus_restored_total 1056
telemt_user_connections_total{user="hello"} 54175
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 449535512 (428.71 MB)
telemt_user_octets_to_client{user="hello"} 26474234592 (24.66 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 24334.4 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170783
telemt_connections_bad_total 62066
telemt_handshake_timeouts_total 4094
telemt_upstream_connect_attempt_total 33083
telemt_upstream_connect_success_total 32870
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 32870
telemt_upstream_connect_attempts_per_request{bucket="2"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 438
telemt_me_reconnect_attempts_total 13837
telemt_me_reconnect_success_total 13806
telemt_me_reader_eof_total 14538
telemt_me_idle_close_by_peer_total 14535
telemt_me_route_drop_no_conn_total 32931
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 299
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14543
telemt_me_writer_restored_same_endpoint_total 13785
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 101047
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 621303388 (592.52 MB)
telemt_user_octets_to_client{user="hello"} 26701129064 (24.87 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 24333.2 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83080
telemt_connections_bad_total 2721
telemt_handshake_timeouts_total 842
telemt_upstream_connect_attempt_total 16117
telemt_upstream_connect_success_total 16042
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 16042
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 2328
telemt_me_reconnect_success_total 2330
telemt_me_reader_eof_total 2347
telemt_me_idle_close_by_peer_total 2347
telemt_me_route_drop_no_conn_total 27145
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2347
telemt_me_writer_restored_same_endpoint_total 2309
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 76184
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 666115184 (635.26 MB)
telemt_user_octets_to_client{user="hello"} 26132503076 (24.34 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 24331.9 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186393
telemt_connections_bad_total 306
telemt_handshake_timeouts_total 86190
telemt_upstream_connect_attempt_total 36928
telemt_upstream_connect_success_total 36705
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 36705
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 18620
telemt_me_reconnect_success_total 18612
telemt_me_reader_eof_total 19710
telemt_me_idle_close_by_peer_total 19709
telemt_me_route_drop_no_conn_total 47057
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 129
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19721
telemt_me_writer_restored_same_endpoint_total 18588
telemt_me_writer_removed_unexpected_minus_restored_total 1133
telemt_user_connections_total{user="hello"} 96400
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 567289744 (541.01 MB)
telemt_user_octets_to_client{user="hello"} 22118292256 (20.60 GB)
telemt_user_unique_ips_current{user="hello"} 26
```