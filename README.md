# Server Metrics 2026-03-04 13:14:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 57861.8 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025511
telemt_connections_bad_total 13641
telemt_handshake_timeouts_total 15973
telemt_upstream_connect_attempt_total 34210
telemt_upstream_connect_success_total 34059
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 34059
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 7145
telemt_me_reconnect_success_total 7094
telemt_me_reader_eof_total 7314
telemt_me_idle_close_by_peer_total 7314
telemt_me_route_drop_no_conn_total 368725
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 229
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1655
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7314
telemt_me_writer_restored_same_endpoint_total 7072
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 806839
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 9116802124 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 266331824276 (248.04 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 57858.1 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399437
telemt_connections_bad_total 3274
telemt_handshake_timeouts_total 28869
telemt_upstream_connect_attempt_total 104512
telemt_upstream_connect_success_total 102910
telemt_upstream_connect_fail_total 763
telemt_upstream_connect_attempts_per_request{bucket="1"} 102904
telemt_upstream_connect_attempts_per_request{bucket="2"} 769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 763
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 57702
telemt_me_reconnect_success_total 57611
telemt_me_reader_eof_total 59061
telemt_me_idle_close_by_peer_total 59060
telemt_me_route_drop_no_conn_total 162493
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 243
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 787
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59141
telemt_me_writer_restored_same_endpoint_total 57586
telemt_me_writer_removed_unexpected_minus_restored_total 1555
telemt_user_connections_total{user="hello"} 305784
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 4016914460 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 97103927420 (90.44 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 57857.0 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774803
telemt_connections_bad_total 172391
telemt_handshake_timeouts_total 26964
telemt_upstream_connect_attempt_total 81917
telemt_upstream_connect_success_total 81404
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 81403
telemt_upstream_connect_attempts_per_request{bucket="2"} 248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 1066
telemt_me_reconnect_attempts_total 37689
telemt_me_reconnect_success_total 37593
telemt_me_reader_eof_total 39583
telemt_me_idle_close_by_peer_total 39579
telemt_me_route_drop_no_conn_total 285689
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1444
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39595
telemt_me_writer_restored_same_endpoint_total 37571
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 539207
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 11903786180 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 180903547776 (168.48 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 4534.4 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55633
telemt_connections_bad_total 5209
telemt_handshake_timeouts_total 990
telemt_upstream_connect_attempt_total 1622
telemt_upstream_connect_success_total 1622
telemt_upstream_connect_attempts_per_request{bucket="1"} 1622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 100
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 19732
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 100
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 48679
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 948490260 (904.55 MB)
telemt_user_octets_to_client{user="hello"} 32330763272 (30.11 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 4893.6 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89311
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 1349
telemt_upstream_connect_attempt_total 2596
telemt_upstream_connect_success_total 2581
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2581
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 327
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 28188
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 328
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 76921
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 815922980 (778.12 MB)
telemt_user_octets_to_client{user="hello"} 20869185164 (19.44 GB)
telemt_user_unique_ips_current{user="hello"} 38
```