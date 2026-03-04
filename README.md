# Server Metrics 2026-03-04 16:09:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 68314.7 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304982
telemt_connections_bad_total 18148
telemt_handshake_timeouts_total 22754
telemt_upstream_connect_attempt_total 39673
telemt_upstream_connect_success_total 39488
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 39488
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 8393
telemt_me_reconnect_success_total 8326
telemt_me_reader_eof_total 8598
telemt_me_idle_close_by_peer_total 8597
telemt_me_route_drop_no_conn_total 492643
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 266
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2736
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1862
telemt_desync_frames_bucket_total{bucket="1_2"} 786
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8598
telemt_me_writer_restored_same_endpoint_total 8304
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 1058665
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 14023310612 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 355015406628 (330.63 GB)
telemt_user_unique_ips_current{user="hello"} 94
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 68311.2 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495436
telemt_connections_bad_total 4209
telemt_handshake_timeouts_total 30620
telemt_upstream_connect_attempt_total 123985
telemt_upstream_connect_success_total 122231
telemt_upstream_connect_fail_total 839
telemt_upstream_connect_attempts_per_request{bucket="1"} 122225
telemt_upstream_connect_attempts_per_request{bucket="2"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 839
telemt_me_keepalive_timeout_total 1631
telemt_me_reconnect_attempts_total 67699
telemt_me_reconnect_success_total 67593
telemt_me_reader_eof_total 69329
telemt_me_idle_close_by_peer_total 69328
telemt_me_route_drop_no_conn_total 202931
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 285
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1277
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 103
telemt_me_writer_removed_unexpected_total 69409
telemt_me_writer_restored_same_endpoint_total 67567
telemt_me_writer_removed_unexpected_minus_restored_total 1842
telemt_user_connections_total{user="hello"} 396664
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 6013911288 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 125235197472 (116.63 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 68310.0 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1001889
telemt_connections_bad_total 202154
telemt_handshake_timeouts_total 30269
telemt_upstream_connect_attempt_total 90033
telemt_upstream_connect_success_total 89417
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 89416
telemt_upstream_connect_attempts_per_request{bucket="2"} 299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1174
telemt_me_reconnect_attempts_total 40244
telemt_me_reconnect_success_total 40137
telemt_me_reader_eof_total 42261
telemt_me_idle_close_by_peer_total 42256
telemt_me_route_drop_no_conn_total 365621
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2096
telemt_desync_full_logged_total 692
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 791
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42274
telemt_me_writer_restored_same_endpoint_total 40115
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 723106
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 14288942444 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 246764016104 (229.82 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 14987.4 (4h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244723
telemt_connections_bad_total 28461
telemt_handshake_timeouts_total 6400
telemt_upstream_connect_attempt_total 6068
telemt_upstream_connect_success_total 6068
telemt_upstream_connect_attempts_per_request{bucket="1"} 6068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2626
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 868
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 77921
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 235
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 887
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 201139
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 2658746988 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 76793551144 (71.52 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 15346.7 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264240
telemt_connections_bad_total 2521
telemt_handshake_timeouts_total 3956
telemt_upstream_connect_attempt_total 7525
telemt_upstream_connect_success_total 7488
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7488
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 1331
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1364
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 102152
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 532
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 227088
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 3709618960 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 67991391048 (63.32 GB)
telemt_user_unique_ips_current{user="hello"} 52
```