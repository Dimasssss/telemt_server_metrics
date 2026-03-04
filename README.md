# Server Metrics 2026-03-04 05:07:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 28638.8 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206411
telemt_connections_bad_total 2279
telemt_handshake_timeouts_total 3860
telemt_upstream_connect_attempt_total 20128
telemt_upstream_connect_success_total 20038
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 20038
telemt_upstream_connect_attempts_per_request{bucket="2"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 4522
telemt_me_reconnect_success_total 4504
telemt_me_reader_eof_total 4609
telemt_me_idle_close_by_peer_total 4609
telemt_me_route_drop_no_conn_total 66667
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 116
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 544
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4609
telemt_me_writer_restored_same_endpoint_total 4484
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 195184
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 2057947052 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 63667685664 (59.30 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 28635.5 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97943
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 21087
telemt_upstream_connect_attempt_total 65024
telemt_upstream_connect_success_total 64318
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 64312
telemt_upstream_connect_attempts_per_request{bucket="2"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 986
telemt_me_reconnect_attempts_total 39558
telemt_me_reconnect_success_total 39530
telemt_me_reader_eof_total 40525
telemt_me_idle_close_by_peer_total 40524
telemt_me_route_drop_no_conn_total 30479
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 124
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 197
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 40586
telemt_me_writer_restored_same_endpoint_total 39509
telemt_me_writer_removed_unexpected_minus_restored_total 1077
telemt_user_connections_total{user="hello"} 70900
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 637702864 (608.16 MB)
telemt_user_octets_to_client{user="hello"} 30504733576 (28.41 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 28634.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216726
telemt_connections_bad_total 79685
telemt_handshake_timeouts_total 4440
telemt_upstream_connect_attempt_total 37385
telemt_upstream_connect_success_total 37140
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 37140
telemt_upstream_connect_attempts_per_request{bucket="2"} 114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 493
telemt_me_reconnect_attempts_total 14996
telemt_me_reconnect_success_total 14957
telemt_me_reader_eof_total 15749
telemt_me_idle_close_by_peer_total 15746
telemt_me_route_drop_no_conn_total 44274
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 15757
telemt_me_writer_restored_same_endpoint_total 14936
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 128279
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 846031300 (806.84 MB)
telemt_user_octets_to_client{user="hello"} 32920136436 (30.66 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 28633.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108982
telemt_connections_bad_total 6806
telemt_handshake_timeouts_total 1341
telemt_upstream_connect_attempt_total 19910
telemt_upstream_connect_success_total 19827
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 19827
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 3262
telemt_me_reconnect_success_total 3260
telemt_me_reader_eof_total 3288
telemt_me_idle_close_by_peer_total 3288
telemt_me_route_drop_no_conn_total 34663
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 114
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3288
telemt_me_writer_restored_same_endpoint_total 3239
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 96343
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 799844868 (762.79 MB)
telemt_user_octets_to_client{user="hello"} 33089063676 (30.82 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 28631.9 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234638
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 105466
telemt_upstream_connect_attempt_total 42131
telemt_upstream_connect_success_total 41846
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 41846
telemt_upstream_connect_attempts_per_request{bucket="2"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 576
telemt_me_reconnect_attempts_total 20315
telemt_me_reconnect_success_total 20305
telemt_me_reader_eof_total 21453
telemt_me_idle_close_by_peer_total 21452
telemt_me_route_drop_no_conn_total 54529
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 21465
telemt_me_writer_restored_same_endpoint_total 20281
telemt_me_writer_removed_unexpected_minus_restored_total 1184
telemt_user_connections_total{user="hello"} 120020
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 912785528 (870.50 MB)
telemt_user_octets_to_client{user="hello"} 27896091676 (25.98 GB)
telemt_user_unique_ips_current{user="hello"} 21
```