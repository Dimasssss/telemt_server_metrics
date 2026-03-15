# Server Metrics 2026-03-15 15:26:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 61929.9 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1993941
telemt_connections_bad_total 107747
telemt_handshake_timeouts_total 22616
telemt_upstream_connect_attempt_total 12342
telemt_upstream_connect_success_total 12290
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14082
telemt_me_reconnect_success_total 9189
telemt_me_reader_eof_total 9825
telemt_me_idle_close_by_peer_total 9825
telemt_me_route_drop_no_conn_total 686189
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688315
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6430
telemt_desync_full_logged_total 1780
telemt_desync_suppressed_total 4650
telemt_desync_frames_bucket_total{bucket="1_2"} 1588
telemt_desync_frames_bucket_total{bucket="3_10"} 2473
telemt_desync_frames_bucket_total{bucket="gt_10"} 2369
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9490
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9178
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 1687823
telemt_user_connections_current{user="hello"} 2356
telemt_user_octets_from_client{user="hello"} 24800055992 (23.10 GB)
telemt_user_octets_to_client{user="hello"} 653086280880 (608.23 GB)
telemt_user_unique_ips_current{user="hello"} 661
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 61930.7 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796305
telemt_connections_bad_total 42630
telemt_handshake_timeouts_total 59041
telemt_upstream_connect_attempt_total 15638
telemt_upstream_connect_success_total 15563
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 15638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12220
telemt_me_reconnect_success_total 12122
telemt_me_reader_eof_total 12810
telemt_me_idle_close_by_peer_total 12810
telemt_me_route_drop_no_conn_total 200042
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605039
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2006
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 741
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 527
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12279
telemt_me_writer_restored_same_endpoint_total 12110
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 605283
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 8440921663 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 228184870468 (212.51 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 61930.8 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1779036
telemt_connections_bad_total 47394
telemt_handshake_timeouts_total 177820
telemt_upstream_connect_attempt_total 13554
telemt_upstream_connect_success_total 13490
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 13554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11626
telemt_me_reconnect_success_total 10365
telemt_me_reader_eof_total 10983
telemt_me_idle_close_by_peer_total 10983
telemt_me_route_drop_no_conn_total 467488
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2659
telemt_desync_full_logged_total 977
telemt_desync_suppressed_total 1682
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 1008
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10548
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10346
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1070480
telemt_user_connections_current{user="hello"} 1438
telemt_user_octets_from_client{user="hello"} 15420138248 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 383773822788 (357.42 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 61930.7 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840887
telemt_connections_bad_total 75580
telemt_handshake_timeouts_total 42159
telemt_upstream_connect_attempt_total 167908
telemt_upstream_connect_success_total 167403
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 167908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52676
telemt_me_reconnect_success_total 12236
telemt_me_reader_eof_total 13836
telemt_me_idle_close_by_peer_total 13836
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 185455
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494542
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1343
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13621
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12202
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1385
telemt_user_connections_total{user="hello"} 646200
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 12837950158 (11.96 GB)
telemt_user_octets_to_client{user="hello"} 225692510661 (210.19 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 61931.7 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851562
telemt_connections_bad_total 9431
telemt_handshake_timeouts_total 18390
telemt_upstream_connect_attempt_total 13757
telemt_upstream_connect_success_total 13680
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14261
telemt_me_reconnect_success_total 10579
telemt_me_reader_eof_total 11284
telemt_me_idle_close_by_peer_total 11284
telemt_me_route_drop_no_conn_total 211938
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699908
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2432
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1608
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 940
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10818
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10571
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 699947
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 8675729932 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 254475377196 (237.00 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 108
```