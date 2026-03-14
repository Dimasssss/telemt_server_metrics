# Server Metrics 2026-03-14 05:13:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 170065.9 (47h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4812148
telemt_connections_bad_total 40015
telemt_handshake_timeouts_total 110266
telemt_upstream_connect_attempt_total 35803
telemt_upstream_connect_success_total 35568
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 34935
telemt_me_reconnect_success_total 24790
telemt_me_reader_eof_total 26605
telemt_me_idle_close_by_peer_total 26604
telemt_me_route_drop_no_conn_total 1822751
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4415245
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16976
telemt_desync_full_logged_total 4595
telemt_desync_suppressed_total 12381
telemt_desync_frames_bucket_total{bucket="1_2"} 4235
telemt_desync_frames_bucket_total{bucket="3_10"} 6477
telemt_desync_frames_bucket_total{bucket="gt_10"} 6264
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 25459
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24777
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 4416798
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 64518932796 (60.09 GB)
telemt_user_octets_to_client{user="hello"} 1392243039329 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69729.8 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761681
telemt_connections_bad_total 53055
telemt_handshake_timeouts_total 14093
telemt_upstream_connect_attempt_total 19178
telemt_upstream_connect_success_total 18912
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 19178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 2111
telemt_me_reconnect_attempts_total 16860
telemt_me_reconnect_success_total 13404
telemt_me_reader_eof_total 14241
telemt_me_idle_close_by_peer_total 14240
telemt_me_route_drop_no_conn_total 250237
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602855
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1799
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13693
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13396
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 604806
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 6458918533 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 203477444312 (189.50 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 199686.6 (55h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3460837
telemt_connections_bad_total 37726
telemt_handshake_timeouts_total 228967
telemt_upstream_connect_attempt_total 45121
telemt_upstream_connect_success_total 45100
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10629
telemt_me_reconnect_attempts_total 39841
telemt_me_reconnect_success_total 34871
telemt_me_reader_eof_total 37044
telemt_me_idle_close_by_peer_total 37043
telemt_me_route_drop_no_conn_total 1183154
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2883030
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9541
telemt_desync_full_logged_total 3204
telemt_desync_suppressed_total 6337
telemt_desync_frames_bucket_total{bucket="1_2"} 1654
telemt_desync_frames_bucket_total{bucket="3_10"} 3457
telemt_desync_frames_bucket_total{bucket="gt_10"} 4430
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 35356
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34830
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 2882242
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 46080434032 (42.92 GB)
telemt_user_octets_to_client{user="hello"} 1034233142245 (963.20 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 199689.1 (55h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2319659
telemt_connections_bad_total 23120
telemt_handshake_timeouts_total 264251
telemt_upstream_connect_attempt_total 62346
telemt_upstream_connect_success_total 59869
telemt_upstream_connect_fail_total 2340
telemt_upstream_connect_attempts_per_request{bucket="1"} 62072
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2339
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20470
telemt_me_reconnect_attempts_total 51968
telemt_me_reconnect_success_total 42927
telemt_me_reader_eof_total 46040
telemt_me_idle_close_by_peer_total 46033
telemt_me_route_drop_no_conn_total 786009
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1838012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43582
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42903
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 1843987
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 27939762359 (26.02 GB)
telemt_user_octets_to_client{user="hello"} 676205441670 (629.77 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 69122.7 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745791
telemt_connections_bad_total 8017
telemt_handshake_timeouts_total 8921
telemt_upstream_connect_attempt_total 17933
telemt_upstream_connect_success_total 17465
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 17933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_keepalive_timeout_total 1544
telemt_me_reconnect_attempts_total 52786
telemt_me_reconnect_success_total 14022
telemt_me_reader_eof_total 15586
telemt_me_idle_close_by_peer_total 15585
telemt_me_route_drop_no_conn_total 285050
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696131
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15356
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 14017
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1334
telemt_user_connections_total{user="hello"} 695996
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 12533948588 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 230645623548 (214.81 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 44
```