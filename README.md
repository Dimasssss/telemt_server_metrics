# Server Metrics 2026-03-13 06:59:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90067.2 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2445870
telemt_connections_bad_total 36048
telemt_handshake_timeouts_total 25911
telemt_upstream_connect_attempt_total 17619
telemt_upstream_connect_success_total 17520
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1328
telemt_me_reconnect_attempts_total 21909
telemt_me_reconnect_success_total 13038
telemt_me_reader_eof_total 14061
telemt_me_idle_close_by_peer_total 14060
telemt_me_route_drop_no_conn_total 922451
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2246267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10056
telemt_desync_full_logged_total 2590
telemt_desync_suppressed_total 7466
telemt_desync_frames_bucket_total{bucket="1_2"} 2563
telemt_desync_frames_bucket_total{bucket="3_10"} 3703
telemt_desync_frames_bucket_total{bucket="gt_10"} 3790
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13498
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13025
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 2245799
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 32400014360 (30.17 GB)
telemt_user_octets_to_client{user="hello"} 762033428952 (709.70 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 119687.7 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 978080
telemt_connections_bad_total 12571
telemt_handshake_timeouts_total 42400
telemt_upstream_connect_attempt_total 30029
telemt_upstream_connect_success_total 29998
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3578
telemt_me_reconnect_attempts_total 22546
telemt_me_reconnect_success_total 22427
telemt_me_reader_eof_total 23912
telemt_me_idle_close_by_peer_total 23912
telemt_me_route_drop_no_conn_total 311673
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3731
telemt_desync_full_logged_total 1158
telemt_desync_suppressed_total 2573
telemt_desync_frames_bucket_total{bucket="1_2"} 1429
telemt_desync_frames_bucket_total{bucket="3_10"} 1208
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22648
telemt_me_writer_restored_same_endpoint_total 22418
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 885783
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 13760271492 (12.82 GB)
telemt_user_octets_to_client{user="hello"} 335499196423 (312.46 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 119687.7 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2015354
telemt_connections_bad_total 23000
telemt_handshake_timeouts_total 135754
telemt_upstream_connect_attempt_total 27626
telemt_upstream_connect_success_total 27616
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1699
telemt_me_reconnect_attempts_total 22605
telemt_me_reconnect_success_total 21330
telemt_me_reader_eof_total 22593
telemt_me_idle_close_by_peer_total 22592
telemt_me_route_drop_no_conn_total 644948
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1591478
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5449
telemt_desync_full_logged_total 1668
telemt_desync_suppressed_total 3781
telemt_desync_frames_bucket_total{bucket="1_2"} 896
telemt_desync_frames_bucket_total{bucket="3_10"} 1981
telemt_desync_frames_bucket_total{bucket="gt_10"} 2572
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 21536
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21289
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 1590968
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 26902683188 (25.06 GB)
telemt_user_octets_to_client{user="hello"} 570108256885 (530.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 119687.9 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1229445
telemt_connections_bad_total 14049
telemt_handshake_timeouts_total 78977
telemt_upstream_connect_attempt_total 40468
telemt_upstream_connect_success_total 38176
telemt_upstream_connect_fail_total 2155
telemt_upstream_connect_attempts_per_request{bucket="1"} 40194
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2154
telemt_me_keepalive_timeout_total 11426
telemt_me_reconnect_attempts_total 35315
telemt_me_reconnect_success_total 26378
telemt_me_reader_eof_total 28427
telemt_me_idle_close_by_peer_total 28420
telemt_me_route_drop_no_conn_total 442508
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058409
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2089
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 26839
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26354
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1063238
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 16338219221 (15.22 GB)
telemt_user_octets_to_client{user="hello"} 422229179854 (393.23 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 119687.8 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1389412
telemt_connections_bad_total 21756
telemt_handshake_timeouts_total 11418
telemt_upstream_connect_attempt_total 37897
telemt_upstream_connect_success_total 37436
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 37897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2052
telemt_me_reconnect_attempts_total 45243
telemt_me_reconnect_success_total 31506
telemt_me_reader_eof_total 33061
telemt_me_idle_close_by_peer_total 33061
telemt_me_seq_mismatch_total 43
telemt_me_route_drop_no_conn_total 509461
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1279960
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 47
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4593
telemt_desync_full_logged_total 1641
telemt_desync_suppressed_total 2952
telemt_desync_frames_bucket_total{bucket="1_2"} 1397
telemt_desync_frames_bucket_total{bucket="3_10"} 1481
telemt_desync_frames_bucket_total{bucket="gt_10"} 1715
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 32279
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31451
telemt_me_writer_restored_fallback_total 55
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 1279800
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 16345657116 (15.22 GB)
telemt_user_octets_to_client{user="hello"} 439737047020 (409.54 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 89
```