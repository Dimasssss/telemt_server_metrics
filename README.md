# Server Metrics 2026-03-04 16:04:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 68007.1 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1294969
telemt_connections_bad_total 17859
telemt_handshake_timeouts_total 22671
telemt_upstream_connect_attempt_total 39513
telemt_upstream_connect_success_total 39328
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 39328
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 8359
telemt_me_reconnect_success_total 8292
telemt_me_reader_eof_total 8562
telemt_me_idle_close_by_peer_total 8561
telemt_me_route_drop_no_conn_total 482397
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 266
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2685
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 1827
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 1004
telemt_desync_frames_bucket_total{bucket="gt_10"} 904
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8562
telemt_me_writer_restored_same_endpoint_total 8270
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1049512
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 13919610192 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 352520540748 (328.31 GB)
telemt_user_unique_ips_current{user="hello"} 131
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 68003.6 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491885
telemt_connections_bad_total 4208
telemt_handshake_timeouts_total 30605
telemt_upstream_connect_attempt_total 123959
telemt_upstream_connect_success_total 122205
telemt_upstream_connect_fail_total 839
telemt_upstream_connect_attempts_per_request{bucket="1"} 122199
telemt_upstream_connect_attempts_per_request{bucket="2"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 839
telemt_me_keepalive_timeout_total 1629
telemt_me_reconnect_attempts_total 67699
telemt_me_reconnect_success_total 67593
telemt_me_reader_eof_total 69329
telemt_me_idle_close_by_peer_total 69328
telemt_me_route_drop_no_conn_total 201311
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 285
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1261
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 884
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 75
telemt_me_writer_removed_unexpected_total 69409
telemt_me_writer_restored_same_endpoint_total 67567
telemt_me_writer_removed_unexpected_minus_restored_total 1842
telemt_user_connections_total{user="hello"} 393216
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 5980317900 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 123936542072 (115.42 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 68002.4 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995085
telemt_connections_bad_total 201293
telemt_handshake_timeouts_total 30247
telemt_upstream_connect_attempt_total 90004
telemt_upstream_connect_success_total 89388
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 89387
telemt_upstream_connect_attempts_per_request{bucket="2"} 299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1173
telemt_me_reconnect_attempts_total 40242
telemt_me_reconnect_success_total 40136
telemt_me_reader_eof_total 42260
telemt_me_idle_close_by_peer_total 42255
telemt_me_route_drop_no_conn_total 362507
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2094
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 791
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42273
telemt_me_writer_restored_same_endpoint_total 40114
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 717344
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 14217289136 (13.24 GB)
telemt_user_octets_to_client{user="hello"} 243416004628 (226.70 GB)
telemt_user_unique_ips_current{user="hello"} 85
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 14679.7 (4h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238948
telemt_connections_bad_total 28156
telemt_handshake_timeouts_total 6362
telemt_upstream_connect_attempt_total 5931
telemt_upstream_connect_success_total 5931
telemt_upstream_connect_attempts_per_request{bucket="1"} 5931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2556
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 868
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 73531
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 233
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 887
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 195911
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 2604322476 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 75254064428 (70.09 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 15039.1 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259233
telemt_connections_bad_total 2520
telemt_handshake_timeouts_total 3881
telemt_upstream_connect_attempt_total 7489
telemt_upstream_connect_success_total 7452
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7452
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1331
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1364
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 99424
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 526
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 222548
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 3666578200 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 66076808716 (61.54 GB)
telemt_user_unique_ips_current{user="hello"} 47
```