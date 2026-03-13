# Server Metrics 2026-03-13 05:38:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85167.9 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2291593
telemt_connections_bad_total 34087
telemt_handshake_timeouts_total 24097
telemt_upstream_connect_attempt_total 16761
telemt_upstream_connect_success_total 16668
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1315
telemt_me_reconnect_attempts_total 21298
telemt_me_reconnect_success_total 12429
telemt_me_reader_eof_total 13409
telemt_me_idle_close_by_peer_total 13408
telemt_me_route_drop_no_conn_total 871570
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2107645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9343
telemt_desync_full_logged_total 2408
telemt_desync_suppressed_total 6935
telemt_desync_frames_bucket_total{bucket="1_2"} 2428
telemt_desync_frames_bucket_total{bucket="3_10"} 3416
telemt_desync_frames_bucket_total{bucket="gt_10"} 3499
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12878
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12416
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 2107004
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 30528519396 (28.43 GB)
telemt_user_octets_to_client{user="hello"} 724097637624 (674.37 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 114788.4 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928750
telemt_connections_bad_total 12383
telemt_handshake_timeouts_total 40476
telemt_upstream_connect_attempt_total 29033
telemt_upstream_connect_success_total 29002
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3542
telemt_me_reconnect_attempts_total 21767
telemt_me_reconnect_success_total 21650
telemt_me_reader_eof_total 23085
telemt_me_idle_close_by_peer_total 23085
telemt_me_route_drop_no_conn_total 295529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3351
telemt_desync_full_logged_total 1054
telemt_desync_suppressed_total 2297
telemt_desync_frames_bucket_total{bucket="1_2"} 1320
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 21865
telemt_me_writer_restored_same_endpoint_total 21641
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 839476
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 13320486940 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 320190770179 (298.20 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 114788.3 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1917264
telemt_connections_bad_total 21024
telemt_handshake_timeouts_total 125916
telemt_upstream_connect_attempt_total 26703
telemt_upstream_connect_success_total 26693
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1659
telemt_me_reconnect_attempts_total 21900
telemt_me_reconnect_success_total 20629
telemt_me_reader_eof_total 21853
telemt_me_idle_close_by_peer_total 21852
telemt_me_route_drop_no_conn_total 615484
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1510870
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5258
telemt_desync_full_logged_total 1601
telemt_desync_suppressed_total 3657
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1903
telemt_desync_frames_bucket_total{bucket="gt_10"} 2487
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20828
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20588
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 1510368
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 25955711124 (24.17 GB)
telemt_user_octets_to_client{user="hello"} 539274979897 (502.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 114788.8 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1174595
telemt_connections_bad_total 13984
telemt_handshake_timeouts_total 76478
telemt_upstream_connect_attempt_total 39214
telemt_upstream_connect_success_total 36927
telemt_upstream_connect_fail_total 2150
telemt_upstream_connect_attempts_per_request{bucket="1"} 38940
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2149
telemt_me_keepalive_timeout_total 11401
telemt_me_reconnect_attempts_total 34284
telemt_me_reconnect_success_total 25350
telemt_me_reader_eof_total 27338
telemt_me_idle_close_by_peer_total 27331
telemt_me_route_drop_no_conn_total 418671
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011319
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1982
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25801
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25326
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 1016453
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 15477055097 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 405122783098 (377.30 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 114788.4 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1317731
telemt_connections_bad_total 14037
telemt_handshake_timeouts_total 10785
telemt_upstream_connect_attempt_total 36251
telemt_upstream_connect_success_total 35816
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 36251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 1970
telemt_me_reconnect_attempts_total 43839
telemt_me_reconnect_success_total 30105
telemt_me_reader_eof_total 31632
telemt_me_idle_close_by_peer_total 31632
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 486648
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1219207
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4403
telemt_desync_full_logged_total 1584
telemt_desync_suppressed_total 2819
telemt_desync_frames_bucket_total{bucket="1_2"} 1338
telemt_desync_frames_bucket_total{bucket="3_10"} 1428
telemt_desync_frames_bucket_total{bucket="gt_10"} 1637
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30868
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30053
telemt_me_writer_restored_fallback_total 52
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1219054
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 14744969624 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 413188027996 (384.81 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 80
```