# Server Metrics 2026-03-15 15:16:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 61316.7 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1959932
telemt_connections_bad_total 105165
telemt_handshake_timeouts_total 22334
telemt_upstream_connect_attempt_total 12254
telemt_upstream_connect_success_total 12202
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13994
telemt_me_reconnect_success_total 9102
telemt_me_reader_eof_total 9727
telemt_me_idle_close_by_peer_total 9727
telemt_me_route_drop_no_conn_total 674278
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660903
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6352
telemt_desync_full_logged_total 1754
telemt_desync_suppressed_total 4598
telemt_desync_frames_bucket_total{bucket="1_2"} 1569
telemt_desync_frames_bucket_total{bucket="3_10"} 2447
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9403
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9091
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 1660412
telemt_user_connections_current{user="hello"} 2334
telemt_user_octets_from_client{user="hello"} 24290827260 (22.62 GB)
telemt_user_octets_to_client{user="hello"} 643865847976 (599.65 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 61317.3 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784153
telemt_connections_bad_total 42093
telemt_handshake_timeouts_total 58910
telemt_upstream_connect_attempt_total 15544
telemt_upstream_connect_success_total 15469
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12126
telemt_me_reconnect_success_total 12030
telemt_me_reader_eof_total 12705
telemt_me_idle_close_by_peer_total 12705
telemt_me_route_drop_no_conn_total 196801
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595541
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12185
telemt_me_writer_restored_same_endpoint_total 12018
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 595788
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 8319108555 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 225014246040 (209.56 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 61317.5 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1749692
telemt_connections_bad_total 47312
telemt_handshake_timeouts_total 175786
telemt_upstream_connect_attempt_total 13470
telemt_upstream_connect_success_total 13406
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11542
telemt_me_reconnect_success_total 10282
telemt_me_reader_eof_total 10897
telemt_me_idle_close_by_peer_total 10897
telemt_me_route_drop_no_conn_total 458906
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055978
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2617
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 1655
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1014
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10464
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10263
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1051980
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 15252900136 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 378540488816 (352.54 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 61317.4 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828019
telemt_connections_bad_total 75038
telemt_handshake_timeouts_total 41910
telemt_upstream_connect_attempt_total 167741
telemt_upstream_connect_success_total 167236
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 167741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52510
telemt_me_reconnect_success_total 12070
telemt_me_reader_eof_total 13669
telemt_me_idle_close_by_peer_total 13669
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 181894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483739
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1312
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 430
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13453
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12037
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1383
telemt_user_connections_total{user="hello"} 635432
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 12698851722 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 218128299157 (203.15 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 61318.1 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839375
telemt_connections_bad_total 9431
telemt_handshake_timeouts_total 17959
telemt_upstream_connect_attempt_total 13562
telemt_upstream_connect_success_total 13485
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14066
telemt_me_reconnect_success_total 10384
telemt_me_reader_eof_total 11088
telemt_me_idle_close_by_peer_total 11088
telemt_me_route_drop_no_conn_total 208603
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689006
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2415
telemt_desync_full_logged_total 817
telemt_desync_suppressed_total 1598
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 755
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10621
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 689048
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 8600879448 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 252273720480 (234.95 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 125
```