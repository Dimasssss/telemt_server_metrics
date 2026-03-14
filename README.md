# Server Metrics 2026-03-14 00:57:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 154729.1 (42h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4616187
telemt_connections_bad_total 38869
telemt_handshake_timeouts_total 107913
telemt_upstream_connect_attempt_total 32655
telemt_upstream_connect_success_total 32437
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6670
telemt_me_reconnect_attempts_total 32537
telemt_me_reconnect_success_total 22404
telemt_me_reader_eof_total 24014
telemt_me_idle_close_by_peer_total 24013
telemt_me_route_drop_no_conn_total 1748569
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4231892
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16658
telemt_desync_full_logged_total 4492
telemt_desync_suppressed_total 12166
telemt_desync_frames_bucket_total{bucket="1_2"} 4150
telemt_desync_frames_bucket_total{bucket="3_10"} 6368
telemt_desync_frames_bucket_total{bucket="gt_10"} 6140
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 23042
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22391
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 4233757
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 62426270820 (58.14 GB)
telemt_user_octets_to_client{user="hello"} 1338113020313 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54392.7 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661886
telemt_connections_bad_total 49445
telemt_handshake_timeouts_total 12902
telemt_upstream_connect_attempt_total 15251
telemt_upstream_connect_success_total 15005
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 15251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 2020
telemt_me_reconnect_attempts_total 13687
telemt_me_reconnect_success_total 10245
telemt_me_reader_eof_total 10867
telemt_me_idle_close_by_peer_total 10866
telemt_me_route_drop_no_conn_total 227914
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540485
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10496
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10237
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 542436
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 5870054649 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 175955706032 (163.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 184349.5 (51h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3344429
telemt_connections_bad_total 34283
telemt_handshake_timeouts_total 222528
telemt_upstream_connect_attempt_total 41279
telemt_upstream_connect_success_total 41258
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10358
telemt_me_reconnect_attempts_total 36733
telemt_me_reconnect_success_total 31776
telemt_me_reader_eof_total 33731
telemt_me_idle_close_by_peer_total 33730
telemt_me_route_drop_no_conn_total 1147790
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2780014
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9147
telemt_desync_full_logged_total 3073
telemt_desync_suppressed_total 6074
telemt_desync_frames_bucket_total{bucket="1_2"} 1540
telemt_desync_frames_bucket_total{bucket="3_10"} 3313
telemt_desync_frames_bucket_total{bucket="gt_10"} 4294
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 32231
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31735
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2779259
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 44923470384 (41.84 GB)
telemt_user_octets_to_client{user="hello"} 988308442717 (920.43 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 184351.9 (51h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2221880
telemt_connections_bad_total 22921
telemt_handshake_timeouts_total 239329
telemt_upstream_connect_attempt_total 57378
telemt_upstream_connect_success_total 54920
telemt_upstream_connect_fail_total 2321
telemt_upstream_connect_attempts_per_request{bucket="1"} 57104
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2320
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20388
telemt_me_reconnect_attempts_total 47759
telemt_me_reconnect_success_total 38732
telemt_me_reader_eof_total 41550
telemt_me_idle_close_by_peer_total 41543
telemt_me_route_drop_no_conn_total 765940
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1784645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3800
telemt_desync_full_logged_total 1220
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39348
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38708
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 1790561
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 27398569175 (25.52 GB)
telemt_user_octets_to_client{user="hello"} 663611983794 (618.04 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53785.2 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678867
telemt_connections_bad_total 7883
telemt_handshake_timeouts_total 8614
telemt_upstream_connect_attempt_total 13176
telemt_upstream_connect_success_total 12801
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 13176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 1468
telemt_me_reconnect_attempts_total 42267
telemt_me_reconnect_success_total 10110
telemt_me_reader_eof_total 11340
telemt_me_idle_close_by_peer_total 11339
telemt_me_route_drop_no_conn_total 256367
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631450
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11203
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10105
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 631349
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 10549984896 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 207335748828 (193.10 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 28
```