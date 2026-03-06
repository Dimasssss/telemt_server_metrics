# Server Metrics 2026-03-06 21:45:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 13046.4 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237905
telemt_connections_bad_total 2208
telemt_handshake_timeouts_total 8976
telemt_upstream_connect_attempt_total 20510
telemt_upstream_connect_success_total 20350
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 20410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 995
telemt_me_reconnect_attempts_total 6202
telemt_me_reconnect_success_total 6169
telemt_me_reader_eof_total 8052
telemt_me_idle_close_by_peer_total 8052
telemt_me_route_drop_no_conn_total 90896
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 803
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 152
telemt_me_writer_removed_unexpected_total 8159
telemt_me_writer_restored_same_endpoint_total 6163
telemt_me_writer_removed_unexpected_minus_restored_total 1996
telemt_user_connections_total{user="hello"} 213252
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3201901036 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 82145073708 (76.50 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 13046.3 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92702
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 6587
telemt_upstream_connect_attempt_total 23950
telemt_upstream_connect_success_total 23949
telemt_upstream_connect_attempts_per_request{bucket="1"} 23949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 7930
telemt_me_reconnect_success_total 7919
telemt_me_reader_eof_total 11049
telemt_me_idle_close_by_peer_total 11047
telemt_me_route_drop_no_conn_total 33684
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 583
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 6
telemt_pool_force_close_total 254
telemt_pool_stale_pick_total 36
telemt_me_writer_removed_unexpected_total 11049
telemt_me_writer_restored_same_endpoint_total 7917
telemt_me_writer_removed_unexpected_minus_restored_total 3132
telemt_user_connections_total{user="hello"} 80829
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 1286997536 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 26303693628 (24.50 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 13046.3 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179265
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 2877
telemt_upstream_connect_attempt_total 20022
telemt_upstream_connect_success_total 19883
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 19921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 982
telemt_me_reconnect_attempts_total 5657
telemt_me_reconnect_success_total 5631
telemt_me_reader_eof_total 7504
telemt_me_idle_close_by_peer_total 7501
telemt_me_route_drop_no_conn_total 70009
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 810
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 6
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 7605
telemt_me_writer_restored_same_endpoint_total 5624
telemt_me_writer_removed_unexpected_minus_restored_total 1981
telemt_user_connections_total{user="hello"} 165814
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 10109649132 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 47636286412 (44.36 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 13046.8 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182202
telemt_connections_bad_total 51703
telemt_handshake_timeouts_total 13849
telemt_upstream_connect_attempt_total 20600
telemt_upstream_connect_success_total 20551
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 6401
telemt_me_reconnect_success_total 6386
telemt_me_reader_eof_total 8343
telemt_me_idle_close_by_peer_total 8343
telemt_me_route_drop_no_conn_total 45743
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 7
telemt_pool_force_close_total 271
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 8348
telemt_me_writer_restored_same_endpoint_total 6381
telemt_me_writer_removed_unexpected_minus_restored_total 1967
telemt_user_connections_total{user="hello"} 113466
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 1560692032 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 35675576216 (33.23 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 13045.1 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152822
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 1078
telemt_upstream_connect_attempt_total 20235
telemt_upstream_connect_success_total 20113
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 745
telemt_me_reconnect_attempts_total 6332
telemt_me_reconnect_success_total 6305
telemt_me_reader_eof_total 8578
telemt_me_idle_close_by_peer_total 8577
telemt_me_route_drop_no_conn_total 53056
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 719
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 6
telemt_pool_force_close_total 261
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 8640
telemt_me_writer_restored_same_endpoint_total 6303
telemt_me_writer_removed_unexpected_minus_restored_total 2337
telemt_user_connections_total{user="hello"} 141031
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 9215622376 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 48412852672 (45.09 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 39
```