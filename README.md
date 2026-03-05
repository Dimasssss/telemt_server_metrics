# Server Metrics 2026-03-05 00:07:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 11619.8 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99505
telemt_connections_bad_total 1398
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 15124
telemt_upstream_connect_success_total 14966
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 14965
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 523
telemt_me_reconnect_attempts_total 6830
telemt_me_reconnect_success_total 6824
telemt_me_reader_eof_total 7054
telemt_me_idle_close_by_peer_total 7053
telemt_me_route_drop_no_conn_total 26655
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 7113
telemt_me_writer_restored_same_endpoint_total 6804
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 86459
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 2856064248 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 48607669300 (45.27 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 11614.4 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38601
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 12173
telemt_upstream_connect_success_total 11885
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11875
telemt_upstream_connect_attempts_per_request{bucket="2"} 56
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1012
telemt_me_reconnect_attempts_total 4626
telemt_me_reconnect_success_total 4600
telemt_me_reader_eof_total 4661
telemt_me_idle_close_by_peer_total 4660
telemt_me_route_drop_no_conn_total 11913
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4765
telemt_me_writer_restored_same_endpoint_total 4575
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 35046
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 306067272 (291.89 MB)
telemt_user_octets_to_client{user="hello"} 10087122836 (9.39 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 11611.0 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89770
telemt_connections_bad_total 1303
telemt_handshake_timeouts_total 624
telemt_upstream_connect_attempt_total 4817
telemt_upstream_connect_success_total 4765
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4765
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 257
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 25820
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 82468
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1025400456 (977.90 MB)
telemt_user_octets_to_client{user="hello"} 27464999660 (25.58 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 43659.4 (12h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547384
telemt_connections_bad_total 78668
telemt_handshake_timeouts_total 14724
telemt_upstream_connect_attempt_total 19262
telemt_upstream_connect_success_total 19260
telemt_upstream_connect_attempts_per_request{bucket="1"} 19260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 241
telemt_me_reconnect_attempts_total 2547
telemt_me_reconnect_success_total 2530
telemt_me_reader_eof_total 2582
telemt_me_idle_close_by_peer_total 2582
telemt_me_route_drop_no_conn_total 185054
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2583
telemt_me_writer_restored_same_endpoint_total 2503
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 425519
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 5817678468 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 158801409128 (147.90 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 44018.5 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534627
telemt_connections_bad_total 3840
telemt_handshake_timeouts_total 5871
telemt_upstream_connect_attempt_total 28560
telemt_upstream_connect_success_total 28405
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 28405
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 6499
telemt_me_reconnect_success_total 6479
telemt_me_reader_eof_total 6723
telemt_me_idle_close_by_peer_total 6722
telemt_me_route_drop_no_conn_total 235527
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 9
telemt_pool_force_close_total 409
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6728
telemt_me_writer_restored_same_endpoint_total 6457
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 484166
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 7371863936 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 162205255616 (151.07 GB)
telemt_user_unique_ips_current{user="hello"} 23
```