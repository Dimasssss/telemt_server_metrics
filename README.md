# Server Metrics 2026-03-12 11:56:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21483.0 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728650
telemt_connections_bad_total 1500
telemt_handshake_timeouts_total 4160
telemt_upstream_connect_attempt_total 4219
telemt_upstream_connect_success_total 4191
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 323
telemt_me_reconnect_attempts_total 6987
telemt_me_reconnect_success_total 3094
telemt_me_reader_eof_total 3318
telemt_me_idle_close_by_peer_total 3318
telemt_me_route_drop_no_conn_total 256322
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703112
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3503
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 2612
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1279
telemt_desync_frames_bucket_total{bucket="gt_10"} 1332
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3247
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3081
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 702962
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 12106904932 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 195851336348 (182.40 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51103.6 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377571
telemt_connections_bad_total 4541
telemt_handshake_timeouts_total 18687
telemt_upstream_connect_attempt_total 12509
telemt_upstream_connect_success_total 12502
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1036
telemt_me_reconnect_attempts_total 9829
telemt_me_reconnect_success_total 9772
telemt_me_reader_eof_total 10385
telemt_me_idle_close_by_peer_total 10385
telemt_me_route_drop_no_conn_total 107323
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333258
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 996
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9861
telemt_me_writer_restored_same_endpoint_total 9763
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 333722
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4583047015 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 116959848050 (108.93 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51103.3 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867985
telemt_connections_bad_total 4582
telemt_handshake_timeouts_total 64989
telemt_upstream_connect_attempt_total 12569
telemt_upstream_connect_success_total 12564
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 857
telemt_me_reconnect_attempts_total 9746
telemt_me_reconnect_success_total 9664
telemt_me_reader_eof_total 10156
telemt_me_idle_close_by_peer_total 10156
telemt_me_route_drop_no_conn_total 208433
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582932
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2702
telemt_desync_full_logged_total 799
telemt_desync_suppressed_total 1903
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 1392
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9686
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9623
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 583166
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 7743150516 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 185743611229 (172.99 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51103.7 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480166
telemt_connections_bad_total 7615
telemt_handshake_timeouts_total 44506
telemt_upstream_connect_attempt_total 13619
telemt_upstream_connect_success_total 13565
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1262
telemt_me_reconnect_attempts_total 11063
telemt_me_reconnect_success_total 11017
telemt_me_reader_eof_total 11670
telemt_me_idle_close_by_peer_total 11670
telemt_me_route_drop_no_conn_total 156558
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398145
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 793
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11097
telemt_me_writer_restored_same_endpoint_total 10996
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 397968
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 4540726572 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 150148297848 (139.84 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51103.5 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537262
telemt_connections_bad_total 1693
telemt_handshake_timeouts_total 4198
telemt_upstream_connect_attempt_total 16700
telemt_upstream_connect_success_total 16504
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 16700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 949
telemt_me_reconnect_attempts_total 17235
telemt_me_reconnect_success_total 13949
telemt_me_reader_eof_total 14526
telemt_me_idle_close_by_peer_total 14526
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 177846
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502811
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2110
telemt_desync_full_logged_total 710
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 755
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14189
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 13923
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 502732
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 5881538348 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 124521459980 (115.97 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 94
```