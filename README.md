# Server Metrics 2026-03-06 20:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 8408.8 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185729
telemt_connections_bad_total 1990
telemt_handshake_timeouts_total 7970
telemt_upstream_connect_attempt_total 12345
telemt_upstream_connect_success_total 12231
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 3684
telemt_me_reconnect_success_total 3667
telemt_me_reader_eof_total 4741
telemt_me_idle_close_by_peer_total 4741
telemt_me_route_drop_no_conn_total 73062
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 621
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4765
telemt_me_writer_restored_same_endpoint_total 3661
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 163004
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 2571051300 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 58964287184 (54.91 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 8408.8 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68321
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 2953
telemt_upstream_connect_attempt_total 17212
telemt_upstream_connect_success_total 17211
telemt_upstream_connect_attempts_per_request{bucket="1"} 17211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 6482
telemt_me_reconnect_success_total 6476
telemt_me_reader_eof_total 9190
telemt_me_idle_close_by_peer_total 9188
telemt_me_route_drop_no_conn_total 24962
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 279
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 3
telemt_pool_force_close_total 166
telemt_pool_stale_pick_total 15
telemt_me_writer_removed_unexpected_total 9190
telemt_me_writer_restored_same_endpoint_total 6474
telemt_me_writer_removed_unexpected_minus_restored_total 2716
telemt_user_connections_total{user="hello"} 60807
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 1092471152 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 20751030932 (19.33 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 8408.8 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133192
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 1337
telemt_upstream_connect_attempt_total 11613
telemt_upstream_connect_success_total 11553
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 11577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 2839
telemt_me_reconnect_success_total 2828
telemt_me_reader_eof_total 3749
telemt_me_idle_close_by_peer_total 3746
telemt_me_route_drop_no_conn_total 54589
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 649
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 3805
telemt_me_writer_restored_same_endpoint_total 2821
telemt_me_writer_removed_unexpected_minus_restored_total 984
telemt_user_connections_total{user="hello"} 122452
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 6309162892 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 34576153980 (32.20 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 8409.2 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143237
telemt_connections_bad_total 47428
telemt_handshake_timeouts_total 10194
telemt_upstream_connect_attempt_total 11932
telemt_upstream_connect_success_total 11898
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 11914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 3566
telemt_me_reconnect_success_total 3556
telemt_me_reader_eof_total 4538
telemt_me_idle_close_by_peer_total 4538
telemt_me_route_drop_no_conn_total 33134
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 87
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 4
telemt_pool_force_close_total 155
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4540
telemt_me_writer_restored_same_endpoint_total 3552
telemt_me_writer_removed_unexpected_minus_restored_total 988
telemt_user_connections_total{user="hello"} 82981
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1098043504 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 27349861932 (25.47 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 8407.6 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113049
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 12809
telemt_upstream_connect_success_total 12749
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 12761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 479
telemt_me_reconnect_attempts_total 3804
telemt_me_reconnect_success_total 3791
telemt_me_reader_eof_total 5151
telemt_me_idle_close_by_peer_total 5150
telemt_me_route_drop_no_conn_total 42835
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 535
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 5187
telemt_me_writer_restored_same_endpoint_total 3789
telemt_me_writer_removed_unexpected_minus_restored_total 1398
telemt_user_connections_total{user="hello"} 107270
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 8724455420 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 37688682764 (35.10 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 58
```