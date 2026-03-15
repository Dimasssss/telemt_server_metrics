# Server Metrics 2026-03-15 09:23:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 40164.3 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881901
telemt_connections_bad_total 43835
telemt_handshake_timeouts_total 6426
telemt_upstream_connect_attempt_total 8100
telemt_upstream_connect_success_total 8065
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6094
telemt_me_reconnect_success_total 6062
telemt_me_reader_eof_total 6413
telemt_me_idle_close_by_peer_total 6413
telemt_me_route_drop_no_conn_total 289847
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745345
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2499
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1744
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6147
telemt_me_writer_restored_same_endpoint_total 6051
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 745333
telemt_user_connections_current{user="hello"} 1917
telemt_user_octets_from_client{user="hello"} 10705869200 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 284889794236 (265.32 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 40164.9 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349076
telemt_connections_bad_total 19303
telemt_handshake_timeouts_total 13478
telemt_upstream_connect_attempt_total 10688
telemt_upstream_connect_success_total 10634
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 10688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8355
telemt_me_reconnect_success_total 8303
telemt_me_reader_eof_total 8799
telemt_me_idle_close_by_peer_total 8799
telemt_me_route_drop_no_conn_total 88277
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276367
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 998
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8372
telemt_me_writer_restored_same_endpoint_total 8295
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 276642
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 3999217259 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 103301489576 (96.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 40164.9 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616015
telemt_connections_bad_total 20448
telemt_handshake_timeouts_total 60612
telemt_upstream_connect_attempt_total 8980
telemt_upstream_connect_success_total 8942
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6967
telemt_me_reconnect_success_total 6921
telemt_me_reader_eof_total 7317
telemt_me_idle_close_by_peer_total 7317
telemt_me_route_drop_no_conn_total 182968
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 981
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7005
telemt_me_writer_restored_same_endpoint_total 6902
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 483745
telemt_user_connections_current{user="hello"} 1101
telemt_user_octets_from_client{user="hello"} 7298709204 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 195515806976 (182.09 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 40164.8 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371027
telemt_connections_bad_total 52229
telemt_handshake_timeouts_total 23912
telemt_upstream_connect_attempt_total 12664
telemt_upstream_connect_success_total 12362
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 12664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 26693
telemt_me_reconnect_success_total 10352
telemt_me_reader_eof_total 11174
telemt_me_idle_close_by_peer_total 11174
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 99410
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276842
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 664
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 500
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10952
telemt_me_refill_failed_total 510
telemt_me_writer_restored_same_endpoint_total 10322
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 276850
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 2655306072 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 89128904160 (83.01 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 40165.6 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344000
telemt_connections_bad_total 3835
telemt_handshake_timeouts_total 3713
telemt_upstream_connect_attempt_total 8972
telemt_upstream_connect_success_total 8933
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6959
telemt_me_reconnect_success_total 6927
telemt_me_reader_eof_total 7375
telemt_me_idle_close_by_peer_total 7375
telemt_me_route_drop_no_conn_total 94254
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292389
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1170
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 796
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6997
telemt_me_writer_restored_same_endpoint_total 6919
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 292394
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 3411855464 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 110227344288 (102.66 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 106
```