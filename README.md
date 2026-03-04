# Server Metrics 2026-03-04 12:08:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 53863.3 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901246
telemt_connections_bad_total 12090
telemt_handshake_timeouts_total 13584
telemt_upstream_connect_attempt_total 32716
telemt_upstream_connect_success_total 32577
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32577
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 7088
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 7260
telemt_me_idle_close_by_peer_total 7260
telemt_me_route_drop_no_conn_total 334945
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1467
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 969
telemt_desync_frames_bucket_total{bucket="1_2"} 414
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 14
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7260
telemt_me_writer_restored_same_endpoint_total 7019
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 717477
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 7668007004 (7.14 GB)
telemt_user_octets_to_client{user="hello"} 219100262928 (204.05 GB)
telemt_user_unique_ips_current{user="hello"} 92
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 53859.9 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359445
telemt_connections_bad_total 3116
telemt_handshake_timeouts_total 27712
telemt_upstream_connect_attempt_total 101326
telemt_upstream_connect_success_total 99762
telemt_upstream_connect_fail_total 744
telemt_upstream_connect_attempts_per_request{bucket="1"} 99756
telemt_upstream_connect_attempts_per_request{bucket="2"} 750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 744
telemt_me_keepalive_timeout_total 1408
telemt_me_reconnect_attempts_total 56967
telemt_me_reconnect_success_total 56879
telemt_me_reader_eof_total 58316
telemt_me_idle_close_by_peer_total 58315
telemt_me_route_drop_no_conn_total 147792
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58396
telemt_me_writer_restored_same_endpoint_total 56854
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 269628
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 3530609204 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 85103717524 (79.26 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 53858.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682190
telemt_connections_bad_total 161159
telemt_handshake_timeouts_total 22162
telemt_upstream_connect_attempt_total 79355
telemt_upstream_connect_success_total 78886
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 78885
telemt_upstream_connect_attempts_per_request{bucket="2"} 226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1033
telemt_me_reconnect_attempts_total 37082
telemt_me_reconnect_success_total 36991
telemt_me_reader_eof_total 38963
telemt_me_idle_close_by_peer_total 38959
telemt_me_route_drop_no_conn_total 255317
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1193
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38975
telemt_me_writer_restored_same_endpoint_total 36969
telemt_me_writer_removed_unexpected_minus_restored_total 2006
telemt_user_connections_total{user="hello"} 474464
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 11273520040 (10.50 GB)
telemt_user_octets_to_client{user="hello"} 158769966688 (147.87 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 536.0 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6551
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 143
telemt_upstream_connect_attempt_total 167
telemt_upstream_connect_success_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_me_reconnect_success_total 21
telemt_me_route_drop_no_conn_total 2269
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_force_close_total 1
telemt_user_connections_total{user="hello"} 5792
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 98584152 (94.02 MB)
telemt_user_octets_to_client{user="hello"} 4038782948 (3.76 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 895.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15551
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 147
telemt_upstream_connect_success_total 144
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 144
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 4519
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 43
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 13696
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 143822984 (137.16 MB)
telemt_user_octets_to_client{user="hello"} 4801012108 (4.47 GB)
telemt_user_unique_ips_current{user="hello"} 55
```