# Server Metrics 2026-03-04 15:58:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 67699.8 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283822
telemt_connections_bad_total 17568
telemt_handshake_timeouts_total 22593
telemt_upstream_connect_attempt_total 39301
telemt_upstream_connect_success_total 39117
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 39117
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 8308
telemt_me_reconnect_success_total 8242
telemt_me_reader_eof_total 8512
telemt_me_idle_close_by_peer_total 8511
telemt_me_route_drop_no_conn_total 473364
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 265
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2625
telemt_desync_full_logged_total 843
telemt_desync_suppressed_total 1782
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8512
telemt_me_writer_restored_same_endpoint_total 8220
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1039505
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 13728345048 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 349722431556 (325.70 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 67696.5 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487679
telemt_connections_bad_total 4201
telemt_handshake_timeouts_total 30549
telemt_upstream_connect_attempt_total 123624
telemt_upstream_connect_success_total 121877
telemt_upstream_connect_fail_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 121871
telemt_upstream_connect_attempts_per_request{bucket="2"} 841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 835
telemt_me_keepalive_timeout_total 1614
telemt_me_reconnect_attempts_total 67550
telemt_me_reconnect_success_total 67443
telemt_me_reader_eof_total 69180
telemt_me_idle_close_by_peer_total 69179
telemt_me_route_drop_no_conn_total 199026
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 282
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1251
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 69260
telemt_me_writer_restored_same_endpoint_total 67418
telemt_me_writer_removed_unexpected_minus_restored_total 1842
telemt_user_connections_total{user="hello"} 389153
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 5943475572 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 122958001460 (114.51 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 67695.1 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987835
telemt_connections_bad_total 200422
telemt_handshake_timeouts_total 30245
telemt_upstream_connect_attempt_total 89967
telemt_upstream_connect_success_total 89351
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 89350
telemt_upstream_connect_attempts_per_request{bucket="2"} 299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1171
telemt_me_reconnect_attempts_total 40242
telemt_me_reconnect_success_total 40136
telemt_me_reader_eof_total 42260
telemt_me_idle_close_by_peer_total 42255
telemt_me_route_drop_no_conn_total 359449
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 278
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2083
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 785
telemt_pool_swap_total 8
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 42273
telemt_me_writer_restored_same_endpoint_total 40114
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 711076
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 14142321860 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 240211248024 (223.71 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 14372.6 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232062
telemt_connections_bad_total 26970
telemt_handshake_timeouts_total 6276
telemt_upstream_connect_attempt_total 5760
telemt_upstream_connect_success_total 5759
telemt_upstream_connect_attempts_per_request{bucket="1"} 5759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2472
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 866
telemt_me_reconnect_success_total 876
telemt_me_reader_eof_total 884
telemt_me_idle_close_by_peer_total 884
telemt_me_route_drop_no_conn_total 69674
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 190549
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 2538738408 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 73910841664 (68.83 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 14731.8 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253911
telemt_connections_bad_total 2510
telemt_handshake_timeouts_total 3823
telemt_upstream_connect_attempt_total 7465
telemt_upstream_connect_success_total 7428
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7428
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 1331
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1364
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 96697
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 523
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 217743
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 3620120792 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 64463076864 (60.04 GB)
telemt_user_unique_ips_current{user="hello"} 64
```