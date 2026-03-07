# Server Metrics 2026-03-07 01:57:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 28142.0 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324385
telemt_connections_bad_total 3884
telemt_handshake_timeouts_total 9562
telemt_upstream_connect_attempt_total 90828
telemt_upstream_connect_success_total 88195
telemt_upstream_connect_fail_total 2495
telemt_upstream_connect_attempts_per_request{bucket="1"} 90690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 99
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2495
telemt_me_keepalive_timeout_total 1902
telemt_me_reconnect_attempts_total 56010
telemt_me_reconnect_success_total 53600
telemt_me_reader_eof_total 55728
telemt_me_idle_close_by_peer_total 55726
telemt_me_route_drop_no_conn_total 122290
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1082
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 14
telemt_pool_force_close_total 627
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 55841
telemt_me_writer_restored_same_endpoint_total 53447
telemt_me_writer_restored_fallback_total 147
telemt_me_async_recovery_trigger_total 48069
telemt_me_writer_removed_unexpected_minus_restored_total 2247
telemt_user_connections_total{user="hello"} 295037
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4414821004 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 127983817816 (119.19 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 28141.9 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141063
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 18136
telemt_upstream_connect_attempt_total 185971
telemt_upstream_connect_success_total 185969
telemt_upstream_connect_attempts_per_request{bucket="1"} 185969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 145380
telemt_me_reconnect_success_total 144992
telemt_me_reader_eof_total 131119
telemt_me_idle_close_by_peer_total 131114
telemt_me_route_drop_no_conn_total 43990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 247
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 835
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 611
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 21
telemt_pool_force_close_total 1379
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 131156
telemt_me_writer_restored_same_endpoint_total 144990
telemt_me_async_recovery_trigger_total 48062
telemt_user_connections_total{user="hello"} 115903
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 1591944132 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 39127761764 (36.44 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 28141.9 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252424
telemt_connections_bad_total 1443
telemt_handshake_timeouts_total 4137
telemt_upstream_connect_attempt_total 139094
telemt_upstream_connect_success_total 138876
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 138957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 2592
telemt_me_reconnect_attempts_total 103703
telemt_me_reconnect_success_total 103616
telemt_me_reader_eof_total 104735
telemt_me_idle_close_by_peer_total 104730
telemt_me_route_drop_no_conn_total 93618
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1077
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 16
telemt_pool_force_close_total 391
telemt_pool_stale_pick_total 127
telemt_me_writer_removed_unexpected_total 104925
telemt_me_writer_restored_same_endpoint_total 103609
telemt_me_async_recovery_trigger_total 143951
telemt_me_writer_removed_unexpected_minus_restored_total 1316
telemt_user_connections_total{user="hello"} 235823
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 22895147276 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 66641123672 (62.06 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 28142.1 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261847
telemt_connections_bad_total 80447
telemt_handshake_timeouts_total 16990
telemt_upstream_connect_attempt_total 55419
telemt_upstream_connect_success_total 55330
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 55372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1064
telemt_me_reconnect_attempts_total 19912
telemt_me_reconnect_success_total 19881
telemt_me_reader_eof_total 26967
telemt_me_idle_close_by_peer_total 26965
telemt_me_route_drop_no_conn_total 71261
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 238
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 249
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 14
telemt_pool_force_close_total 498
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 26972
telemt_me_writer_restored_same_endpoint_total 19876
telemt_me_writer_removed_unexpected_minus_restored_total 7096
telemt_user_connections_total{user="hello"} 160210
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1773431452 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 51077284300 (47.57 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 28140.5 (7h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220212
telemt_connections_bad_total 517
telemt_handshake_timeouts_total 2776
telemt_upstream_connect_attempt_total 47818
telemt_upstream_connect_success_total 47637
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 47661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 1297
telemt_me_reconnect_attempts_total 14279
telemt_me_reconnect_success_total 14238
telemt_me_reader_eof_total 19654
telemt_me_idle_close_by_peer_total 19652
telemt_me_route_drop_no_conn_total 72964
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 807
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 17
telemt_pool_force_close_total 477
telemt_pool_stale_pick_total 218
telemt_me_writer_removed_unexpected_total 19723
telemt_me_writer_restored_same_endpoint_total 14230
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5489
telemt_user_connections_total{user="hello"} 202206
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 10263351612 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 70834477588 (65.97 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 50
```