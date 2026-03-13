# Server Metrics 2026-03-13 08:01:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93742.6 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2598689
telemt_connections_bad_total 36174
telemt_handshake_timeouts_total 27411
telemt_upstream_connect_attempt_total 18260
telemt_upstream_connect_success_total 18159
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 22357
telemt_me_reconnect_success_total 13484
telemt_me_reader_eof_total 14534
telemt_me_idle_close_by_peer_total 14533
telemt_me_route_drop_no_conn_total 970487
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2377049
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10728
telemt_desync_full_logged_total 2769
telemt_desync_suppressed_total 7959
telemt_desync_frames_bucket_total{bucket="1_2"} 2729
telemt_desync_frames_bucket_total{bucket="3_10"} 3987
telemt_desync_frames_bucket_total{bucket="gt_10"} 4012
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 13950
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13471
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 2376533
telemt_user_connections_current{user="hello"} 1688
telemt_user_octets_from_client{user="hello"} 33776128540 (31.46 GB)
telemt_user_octets_to_client{user="hello"} 795755934432 (741.11 GB)
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 123363.0 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059257
telemt_connections_bad_total 13455
telemt_handshake_timeouts_total 79682
telemt_upstream_connect_attempt_total 30860
telemt_upstream_connect_success_total 30829
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3625
telemt_me_reconnect_attempts_total 23182
telemt_me_reconnect_success_total 23062
telemt_me_reader_eof_total 24578
telemt_me_idle_close_by_peer_total 24578
telemt_me_route_drop_no_conn_total 327469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 925768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4086
telemt_desync_full_logged_total 1250
telemt_desync_suppressed_total 2836
telemt_desync_frames_bucket_total{bucket="1_2"} 1531
telemt_desync_frames_bucket_total{bucket="3_10"} 1321
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23289
telemt_me_writer_restored_same_endpoint_total 23053
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 927694
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 14238158160 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 346213394147 (322.44 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 123362.9 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2090433
telemt_connections_bad_total 23558
telemt_handshake_timeouts_total 140210
telemt_upstream_connect_attempt_total 28306
telemt_upstream_connect_success_total 28296
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 23093
telemt_me_reconnect_success_total 21813
telemt_me_reader_eof_total 23109
telemt_me_idle_close_by_peer_total 23108
telemt_me_route_drop_no_conn_total 674150
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660136
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5616
telemt_desync_full_logged_total 1758
telemt_desync_suppressed_total 3858
telemt_desync_frames_bucket_total{bucket="1_2"} 924
telemt_desync_frames_bucket_total{bucket="3_10"} 2044
telemt_desync_frames_bucket_total{bucket="gt_10"} 2648
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22027
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21772
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 1659603
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 27610837220 (25.71 GB)
telemt_user_octets_to_client{user="hello"} 603127452705 (561.71 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 123363.4 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304518
telemt_connections_bad_total 14148
telemt_handshake_timeouts_total 82172
telemt_upstream_connect_attempt_total 41420
telemt_upstream_connect_success_total 39122
telemt_upstream_connect_fail_total 2161
telemt_upstream_connect_attempts_per_request{bucket="1"} 41146
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2160
telemt_me_keepalive_timeout_total 11441
telemt_me_reconnect_attempts_total 36069
telemt_me_reconnect_success_total 27131
telemt_me_reader_eof_total 29212
telemt_me_idle_close_by_peer_total 29205
telemt_me_route_drop_no_conn_total 465212
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105137
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2169
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27599
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27107
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 1109880
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 16805755121 (15.65 GB)
telemt_user_octets_to_client{user="hello"} 440938308006 (410.66 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 123363.2 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1458731
telemt_connections_bad_total 27438
telemt_handshake_timeouts_total 12195
telemt_upstream_connect_attempt_total 38849
telemt_upstream_connect_success_total 38378
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2125
telemt_me_reconnect_attempts_total 45994
telemt_me_reconnect_success_total 32255
telemt_me_reader_eof_total 33858
telemt_me_idle_close_by_peer_total 33858
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 535114
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1340583
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4734
telemt_desync_full_logged_total 1689
telemt_desync_suppressed_total 3045
telemt_desync_frames_bucket_total{bucket="1_2"} 1444
telemt_desync_frames_bucket_total{bucket="3_10"} 1524
telemt_desync_frames_bucket_total{bucket="gt_10"} 1766
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33037
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32199
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1340391
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 17092936880 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 461090785208 (429.42 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 117
```