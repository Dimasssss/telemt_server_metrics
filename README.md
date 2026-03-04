# Server Metrics 2026-03-04 04:27:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 26181.6 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175787
telemt_connections_bad_total 1618
telemt_handshake_timeouts_total 3028
telemt_upstream_connect_attempt_total 19039
telemt_upstream_connect_success_total 18956
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 18956
telemt_upstream_connect_attempts_per_request{bucket="2"} 37
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 4350
telemt_me_reconnect_success_total 4334
telemt_me_reader_eof_total 4437
telemt_me_idle_close_by_peer_total 4437
telemt_me_route_drop_no_conn_total 58396
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 459
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4437
telemt_me_writer_restored_same_endpoint_total 4314
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 167063
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 1699039480 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 53878808096 (50.18 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 26178.2 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82446
telemt_connections_bad_total 303
telemt_handshake_timeouts_total 20700
telemt_upstream_connect_attempt_total 61865
telemt_upstream_connect_success_total 61231
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 61225
telemt_upstream_connect_attempts_per_request{bucket="2"} 307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 38559
telemt_me_reconnect_success_total 38532
telemt_me_reader_eof_total 39510
telemt_me_idle_close_by_peer_total 39509
telemt_me_route_drop_no_conn_total 26062
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39571
telemt_me_writer_restored_same_endpoint_total 38511
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 60173
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 566820216 (540.56 MB)
telemt_user_octets_to_client{user="hello"} 27866394280 (25.95 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 26177.0 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188120
telemt_connections_bad_total 68725
telemt_handshake_timeouts_total 4212
telemt_upstream_connect_attempt_total 34332
telemt_upstream_connect_success_total 34107
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 34107
telemt_upstream_connect_attempts_per_request{bucket="2"} 104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 458
telemt_me_reconnect_attempts_total 13939
telemt_me_reconnect_success_total 13905
telemt_me_reader_eof_total 14643
telemt_me_idle_close_by_peer_total 14640
telemt_me_route_drop_no_conn_total 37647
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 304
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14648
telemt_me_writer_restored_same_endpoint_total 13884
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 111467
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 708943524 (676.10 MB)
telemt_user_octets_to_client{user="hello"} 28513346652 (26.56 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 26176.0 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93484
telemt_connections_bad_total 4341
telemt_handshake_timeouts_total 977
telemt_upstream_connect_attempt_total 17784
telemt_upstream_connect_success_total 17707
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 17707
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 2817
telemt_me_reader_eof_total 2839
telemt_me_idle_close_by_peer_total 2839
telemt_me_route_drop_no_conn_total 30421
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 108
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 2839
telemt_me_writer_restored_same_endpoint_total 2796
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 84136
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 713478944 (680.43 MB)
telemt_user_octets_to_client{user="hello"} 28338536092 (26.39 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 26174.7 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206817
telemt_connections_bad_total 3845
telemt_handshake_timeouts_total 94661
telemt_upstream_connect_attempt_total 38721
telemt_upstream_connect_success_total 38452
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 38452
telemt_upstream_connect_attempts_per_request{bucket="2"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 545
telemt_me_reconnect_attempts_total 19048
telemt_me_reconnect_success_total 19040
telemt_me_reader_eof_total 20150
telemt_me_idle_close_by_peer_total 20149
telemt_me_route_drop_no_conn_total 49797
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 149
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 20161
telemt_me_writer_restored_same_endpoint_total 19016
telemt_me_writer_removed_unexpected_minus_restored_total 1145
telemt_user_connections_total{user="hello"} 104579
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 670820664 (639.74 MB)
telemt_user_octets_to_client{user="hello"} 23715233784 (22.09 GB)
telemt_user_unique_ips_current{user="hello"} 17
```