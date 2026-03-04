# Server Metrics 2026-03-04 12:33:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 55401.5 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955124
telemt_connections_bad_total 12159
telemt_handshake_timeouts_total 15013
telemt_upstream_connect_attempt_total 33109
telemt_upstream_connect_success_total 32965
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32965
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 7096
telemt_me_reconnect_success_total 7047
telemt_me_reader_eof_total 7266
telemt_me_idle_close_by_peer_total 7266
telemt_me_route_drop_no_conn_total 346510
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1541
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 439
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 514
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7266
telemt_me_writer_restored_same_endpoint_total 7025
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 750351
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 8052243980 (7.50 GB)
telemt_user_octets_to_client{user="hello"} 232473696712 (216.51 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 55398.0 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374384
telemt_connections_bad_total 3267
telemt_handshake_timeouts_total 28240
telemt_upstream_connect_attempt_total 102153
telemt_upstream_connect_success_total 100581
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 100575
telemt_upstream_connect_attempts_per_request{bucket="2"} 754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 1413
telemt_me_reconnect_attempts_total 57078
telemt_me_reconnect_success_total 56988
telemt_me_reader_eof_total 58426
telemt_me_idle_close_by_peer_total 58425
telemt_me_route_drop_no_conn_total 153472
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 714
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58506
telemt_me_writer_restored_same_endpoint_total 56963
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 283454
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 3769560080 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 90143314820 (83.95 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 55396.7 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715082
telemt_connections_bad_total 165460
telemt_handshake_timeouts_total 23485
telemt_upstream_connect_attempt_total 80587
telemt_upstream_connect_success_total 80094
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 80093
telemt_upstream_connect_attempts_per_request{bucket="2"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 1047
telemt_me_reconnect_attempts_total 37432
telemt_me_reconnect_success_total 37339
telemt_me_reader_eof_total 39321
telemt_me_idle_close_by_peer_total 39317
telemt_me_route_drop_no_conn_total 265923
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1247
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 803
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39333
telemt_me_writer_restored_same_endpoint_total 37317
telemt_me_writer_removed_unexpected_minus_restored_total 2016
telemt_user_connections_total{user="hello"} 497017
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 11448506844 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 164035111344 (152.77 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 2074.1 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23513
telemt_connections_bad_total 2662
telemt_handshake_timeouts_total 600
telemt_upstream_connect_attempt_total 796
telemt_upstream_connect_success_total 796
telemt_upstream_connect_attempts_per_request{bucket="1"} 796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 8176
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 19895
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 205906592 (196.37 MB)
telemt_user_octets_to_client{user="hello"} 13248884980 (12.34 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 2433.5 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42995
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 828
telemt_upstream_connect_attempt_total 774
telemt_upstream_connect_success_total 769
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 769
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 25
telemt_me_reconnect_success_total 40
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 12940
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 35483
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 415084628 (395.86 MB)
telemt_user_octets_to_client{user="hello"} 10655209468 (9.92 GB)
telemt_user_unique_ips_current{user="hello"} 48
```