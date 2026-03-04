# Server Metrics 2026-03-04 04:42:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 27102.8 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185883
telemt_connections_bad_total 1634
telemt_handshake_timeouts_total 3454
telemt_upstream_connect_attempt_total 19721
telemt_upstream_connect_success_total 19633
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 19633
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 4516
telemt_me_reconnect_success_total 4499
telemt_me_reader_eof_total 4604
telemt_me_idle_close_by_peer_total 4604
telemt_me_route_drop_no_conn_total 61592
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 506
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4604
telemt_me_writer_restored_same_endpoint_total 4479
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 176246
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 1873508788 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 56484811968 (52.61 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 27099.4 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86189
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 20722
telemt_upstream_connect_attempt_total 62887
telemt_upstream_connect_success_total 62229
telemt_upstream_connect_fail_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 62223
telemt_upstream_connect_attempts_per_request{bucket="2"} 319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 313
telemt_me_keepalive_timeout_total 962
telemt_me_reconnect_attempts_total 38855
telemt_me_reconnect_success_total 38828
telemt_me_reader_eof_total 39811
telemt_me_idle_close_by_peer_total 39810
telemt_me_route_drop_no_conn_total 27537
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 194
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39872
telemt_me_writer_restored_same_endpoint_total 38807
telemt_me_writer_removed_unexpected_minus_restored_total 1065
telemt_user_connections_total{user="hello"} 63754
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 598492476 (570.77 MB)
telemt_user_octets_to_client{user="hello"} 28844955148 (26.86 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 27098.2 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197567
telemt_connections_bad_total 71849
telemt_handshake_timeouts_total 4308
telemt_upstream_connect_attempt_total 35222
telemt_upstream_connect_success_total 34993
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 34993
telemt_upstream_connect_attempts_per_request{bucket="2"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 14153
telemt_me_reconnect_success_total 14116
telemt_me_reader_eof_total 14855
telemt_me_idle_close_by_peer_total 14852
telemt_me_route_drop_no_conn_total 39451
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 309
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14863
telemt_me_writer_restored_same_endpoint_total 14095
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 117390
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 754567848 (719.61 MB)
telemt_user_octets_to_client{user="hello"} 30278721152 (28.20 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 27097.1 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99206
telemt_connections_bad_total 5155
telemt_handshake_timeouts_total 1099
telemt_upstream_connect_attempt_total 18328
telemt_upstream_connect_success_total 18248
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18248
telemt_upstream_connect_attempts_per_request{bucket="2"} 39
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 2854
telemt_me_reconnect_success_total 2854
telemt_me_reader_eof_total 2876
telemt_me_idle_close_by_peer_total 2876
telemt_me_route_drop_no_conn_total 32224
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 114
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 111
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2876
telemt_me_writer_restored_same_endpoint_total 2833
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 88620
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 741219020 (706.88 MB)
telemt_user_octets_to_client{user="hello"} 29916527616 (27.86 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 27095.8 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216201
telemt_connections_bad_total 4570
telemt_handshake_timeouts_total 98266
telemt_upstream_connect_attempt_total 39904
telemt_upstream_connect_success_total 39630
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 39630
telemt_upstream_connect_attempts_per_request{bucket="2"} 127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 552
telemt_me_reconnect_attempts_total 19461
telemt_me_reconnect_success_total 19453
telemt_me_reader_eof_total 20574
telemt_me_idle_close_by_peer_total 20573
telemt_me_route_drop_no_conn_total 51364
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20586
telemt_me_writer_restored_same_endpoint_total 19429
telemt_me_writer_removed_unexpected_minus_restored_total 1157
telemt_user_connections_total{user="hello"} 109550
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 710893100 (677.96 MB)
telemt_user_octets_to_client{user="hello"} 25423231872 (23.68 GB)
telemt_user_unique_ips_current{user="hello"} 34
```