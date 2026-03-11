# Server Metrics 2026-03-11 15:22:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89703.8 (24h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2199121
telemt_connections_bad_total 36704
telemt_handshake_timeouts_total 52549
telemt_upstream_connect_attempt_total 18842
telemt_upstream_connect_success_total 18830
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4892
telemt_me_reconnect_attempts_total 32158
telemt_me_reconnect_success_total 14292
telemt_me_reader_eof_total 15514
telemt_me_idle_close_by_peer_total 15514
telemt_me_route_drop_no_conn_total 814349
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2012285
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10511
telemt_desync_full_logged_total 2854
telemt_desync_suppressed_total 7657
telemt_desync_frames_bucket_total{bucket="1_2"} 2611
telemt_desync_frames_bucket_total{bucket="3_10"} 4047
telemt_desync_frames_bucket_total{bucket="gt_10"} 3853
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15007
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14286
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 2010749
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 27019133692 (25.16 GB)
telemt_user_octets_to_client{user="hello"} 571196357640 (531.97 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89760.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816924
telemt_connections_bad_total 13251
telemt_handshake_timeouts_total 55238
telemt_upstream_connect_attempt_total 28439
telemt_upstream_connect_success_total 25483
telemt_upstream_connect_fail_total 2956
telemt_upstream_connect_attempts_per_request{bucket="1"} 28439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2956
telemt_me_keepalive_timeout_total 2550
telemt_me_reconnect_attempts_total 20123
telemt_me_reconnect_success_total 18030
telemt_me_reader_eof_total 19089
telemt_me_idle_close_by_peer_total 19086
telemt_me_route_drop_no_conn_total 320206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694368
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2884
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18292
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18007
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 696843
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 8047560602 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 197004325556 (183.47 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89760.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1419577
telemt_connections_bad_total 8647
telemt_handshake_timeouts_total 124012
telemt_upstream_connect_attempt_total 23701
telemt_upstream_connect_success_total 23418
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 23701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 36175
telemt_me_reconnect_success_total 17820
telemt_me_reader_eof_total 19197
telemt_me_idle_close_by_peer_total 19197
telemt_me_route_drop_no_conn_total 516292
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1234902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3259
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2294
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 1234
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18637
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 17809
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 1234641
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 14866443353 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 371387428977 (345.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89760.7 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017294
telemt_connections_bad_total 77856
telemt_handshake_timeouts_total 98635
telemt_upstream_connect_attempt_total 24019
telemt_upstream_connect_success_total 24019
telemt_upstream_connect_attempts_per_request{bucket="1"} 24019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1008
telemt_me_reconnect_attempts_total 20618
telemt_me_reconnect_success_total 19543
telemt_me_reader_eof_total 20732
telemt_me_idle_close_by_peer_total 20731
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 332584
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813039
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1713
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1055
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19784
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19514
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 812362
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 9660083856 (9.00 GB)
telemt_user_octets_to_client{user="hello"} 240296466256 (223.79 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89760.6 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124553
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11340
telemt_upstream_connect_attempt_total 24288
telemt_upstream_connect_success_total 24182
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 24288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1948
telemt_me_reconnect_attempts_total 23654
telemt_me_reconnect_success_total 19566
telemt_me_reader_eof_total 20635
telemt_me_idle_close_by_peer_total 20635
telemt_me_route_drop_no_conn_total 400734
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022284
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3946
telemt_desync_full_logged_total 1436
telemt_desync_suppressed_total 2510
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 1475
telemt_desync_frames_bucket_total{bucket="gt_10"} 1119
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19946
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19566
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 1021998
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 14481571655 (13.49 GB)
telemt_user_octets_to_client{user="hello"} 358435384178 (333.82 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 122
```