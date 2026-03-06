# Server Metrics 2026-03-06 05:08:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 24448.1 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187686
telemt_connections_bad_total 16002
telemt_handshake_timeouts_total 3156
telemt_upstream_connect_attempt_total 25803
telemt_upstream_connect_success_total 25590
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 25590
telemt_upstream_connect_attempts_per_request{bucket="2"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 9366
telemt_me_reconnect_success_total 9332
telemt_me_reader_eof_total 9656
telemt_me_idle_close_by_peer_total 9656
telemt_me_route_drop_no_conn_total 57304
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 580
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 397
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 9657
telemt_me_writer_restored_same_endpoint_total 9326
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 160047
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 3567176048 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 61910072420 (57.66 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 24443.5 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69781
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 984
telemt_upstream_connect_attempt_total 23626
telemt_upstream_connect_success_total 23624
telemt_upstream_connect_attempts_per_request{bucket="1"} 23624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 6747
telemt_me_reconnect_success_total 6726
telemt_me_reader_eof_total 6876
telemt_me_idle_close_by_peer_total 6876
telemt_me_route_drop_no_conn_total 20911
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 277
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 1470
telemt_me_writer_removed_unexpected_total 6877
telemt_me_writer_restored_same_endpoint_total 6720
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 67341
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 640973236 (611.28 MB)
telemt_user_octets_to_client{user="hello"} 18010967468 (16.77 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 24440.8 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121291
telemt_connections_bad_total 1385
telemt_handshake_timeouts_total 2800
telemt_upstream_connect_attempt_total 23783
telemt_upstream_connect_success_total 23597
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 23597
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 7464
telemt_me_reconnect_success_total 7437
telemt_me_reader_eof_total 7762
telemt_me_idle_close_by_peer_total 7762
telemt_me_route_drop_no_conn_total 34884
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 232
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 7767
telemt_me_writer_restored_same_endpoint_total 7429
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 113481
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 1082933512 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 38144227192 (35.52 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 24437.7 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98770
telemt_connections_bad_total 5528
telemt_handshake_timeouts_total 5568
telemt_upstream_connect_attempt_total 16839
telemt_upstream_connect_success_total 16780
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 16780
telemt_upstream_connect_attempts_per_request{bucket="2"} 29
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 3276
telemt_me_reconnect_success_total 3249
telemt_me_reader_eof_total 3360
telemt_me_idle_close_by_peer_total 3360
telemt_me_route_drop_no_conn_total 34036
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 3360
telemt_me_writer_restored_same_endpoint_total 3242
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 83112
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 1473268164 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 31705358376 (29.53 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 24436.5 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112684
telemt_connections_bad_total 1014
telemt_handshake_timeouts_total 652
telemt_upstream_connect_attempt_total 16513
telemt_upstream_connect_success_total 16474
telemt_upstream_connect_attempts_per_request{bucket="1"} 16474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 2843
telemt_me_reconnect_success_total 2830
telemt_me_reader_eof_total 2930
telemt_me_idle_close_by_peer_total 2929
telemt_me_route_drop_no_conn_total 38716
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 2934
telemt_me_writer_restored_same_endpoint_total 2823
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 109096
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 23572169728 (21.95 GB)
telemt_user_octets_to_client{user="hello"} 64767589160 (60.32 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 49
```