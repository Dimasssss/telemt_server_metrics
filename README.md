# Server Metrics 2026-03-04 11:52:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 52941.6 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869980
telemt_connections_bad_total 12089
telemt_handshake_timeouts_total 12597
telemt_upstream_connect_attempt_total 32490
telemt_upstream_connect_success_total 32353
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32353
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 362
telemt_me_reconnect_attempts_total 7086
telemt_me_reconnect_success_total 7038
telemt_me_reader_eof_total 7258
telemt_me_idle_close_by_peer_total 7258
telemt_me_route_drop_no_conn_total 327764
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1386
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 912
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 457
telemt_pool_swap_total 14
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7258
telemt_me_writer_restored_same_endpoint_total 7017
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 697339
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 7502207140 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 212032402528 (197.47 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 52934.5 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348803
telemt_connections_bad_total 3083
telemt_handshake_timeouts_total 27473
telemt_upstream_connect_attempt_total 101009
telemt_upstream_connect_success_total 99483
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 99477
telemt_upstream_connect_attempts_per_request{bucket="2"} 731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1404
telemt_me_reconnect_attempts_total 56966
telemt_me_reconnect_success_total 56878
telemt_me_reader_eof_total 58315
telemt_me_idle_close_by_peer_total 58314
telemt_me_route_drop_no_conn_total 144719
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58395
telemt_me_writer_restored_same_endpoint_total 56853
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 261768
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 3444994208 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 83069999280 (77.36 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 52933.4 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660318
telemt_connections_bad_total 158589
telemt_handshake_timeouts_total 21191
telemt_upstream_connect_attempt_total 78786
telemt_upstream_connect_success_total 78323
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 78322
telemt_upstream_connect_attempts_per_request{bucket="2"} 223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 36957
telemt_me_reconnect_success_total 36867
telemt_me_reader_eof_total 38837
telemt_me_idle_close_by_peer_total 38833
telemt_me_route_drop_no_conn_total 247509
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1153
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 741
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38849
telemt_me_writer_restored_same_endpoint_total 36845
telemt_me_writer_removed_unexpected_minus_restored_total 2004
telemt_user_connections_total{user="hello"} 459244
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 5965183088 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 152949641920 (142.45 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 52932.4 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425955
telemt_connections_bad_total 29763
telemt_handshake_timeouts_total 67179
telemt_upstream_connect_attempt_total 38910
telemt_upstream_connect_success_total 38755
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 38755
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 8280
telemt_me_reconnect_success_total 8251
telemt_me_reader_eof_total 8435
telemt_me_idle_close_by_peer_total 8435
telemt_me_route_drop_no_conn_total 122418
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8435
telemt_me_writer_restored_same_endpoint_total 8230
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 306423
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 3805624388 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 113194901176 (105.42 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 52930.3 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 574735
telemt_connections_bad_total 6821
telemt_handshake_timeouts_total 132524
telemt_upstream_connect_attempt_total 75420
telemt_upstream_connect_success_total 74883
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 74883
telemt_upstream_connect_attempts_per_request{bucket="2"} 256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 980
telemt_me_reconnect_attempts_total 36167
telemt_me_reconnect_success_total 36131
telemt_me_reader_eof_total 37895
telemt_me_idle_close_by_peer_total 37894
telemt_me_route_drop_no_conn_total 186123
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 844
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 37906
telemt_me_writer_restored_same_endpoint_total 36106
telemt_me_writer_removed_unexpected_minus_restored_total 1800
telemt_user_connections_total{user="hello"} 409741
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 5243959240 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 114307273256 (106.46 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 54
```