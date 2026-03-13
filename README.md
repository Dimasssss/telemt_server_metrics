# Server Metrics 2026-03-13 04:31:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 81188.8 (22h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2203174
telemt_connections_bad_total 30385
telemt_handshake_timeouts_total 23239
telemt_upstream_connect_attempt_total 16058
telemt_upstream_connect_success_total 15969
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 16058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1303
telemt_me_reconnect_attempts_total 20773
telemt_me_reconnect_success_total 11908
telemt_me_reader_eof_total 12854
telemt_me_idle_close_by_peer_total 12853
telemt_me_route_drop_no_conn_total 840917
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2026103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8918
telemt_desync_full_logged_total 2313
telemt_desync_suppressed_total 6605
telemt_desync_frames_bucket_total{bucket="1_2"} 2350
telemt_desync_frames_bucket_total{bucket="3_10"} 3216
telemt_desync_frames_bucket_total{bucket="gt_10"} 3352
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12351
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11895
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 2025528
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 29392930488 (27.37 GB)
telemt_user_octets_to_client{user="hello"} 698989190084 (650.98 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110809.3 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895328
telemt_connections_bad_total 11880
telemt_handshake_timeouts_total 39427
telemt_upstream_connect_attempt_total 28136
telemt_upstream_connect_success_total 28107
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 28136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3487
telemt_me_reconnect_attempts_total 21042
telemt_me_reconnect_success_total 20930
telemt_me_reader_eof_total 22306
telemt_me_idle_close_by_peer_total 22306
telemt_me_route_drop_no_conn_total 285814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807426
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3226
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2214
telemt_desync_frames_bucket_total{bucket="1_2"} 1289
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 21136
telemt_me_writer_restored_same_endpoint_total 20921
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 809325
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 12817556972 (11.94 GB)
telemt_user_octets_to_client{user="hello"} 312196870431 (290.76 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110809.2 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1850460
telemt_connections_bad_total 15743
telemt_handshake_timeouts_total 122159
telemt_upstream_connect_attempt_total 25821
telemt_upstream_connect_success_total 25811
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1640
telemt_me_reconnect_attempts_total 21192
telemt_me_reconnect_success_total 19925
telemt_me_reader_eof_total 21104
telemt_me_idle_close_by_peer_total 21103
telemt_me_route_drop_no_conn_total 597876
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1460563
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1558
telemt_desync_suppressed_total 3548
telemt_desync_frames_bucket_total{bucket="1_2"} 817
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 2444
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20115
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19884
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1460156
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 25260896236 (23.53 GB)
telemt_user_octets_to_client{user="hello"} 519898720865 (484.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110809.4 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145691
telemt_connections_bad_total 13194
telemt_handshake_timeouts_total 74776
telemt_upstream_connect_attempt_total 38195
telemt_upstream_connect_success_total 35912
telemt_upstream_connect_fail_total 2146
telemt_upstream_connect_attempts_per_request{bucket="1"} 37921
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2145
telemt_me_keepalive_timeout_total 11385
telemt_me_reconnect_attempts_total 33443
telemt_me_reconnect_success_total 24512
telemt_me_reader_eof_total 26453
telemt_me_idle_close_by_peer_total 26446
telemt_me_route_drop_no_conn_total 407469
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985385
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 24955
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24488
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 990562
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 15185116101 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 391257959110 (364.39 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 110809.4 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1272837
telemt_connections_bad_total 12881
telemt_handshake_timeouts_total 10211
telemt_upstream_connect_attempt_total 34942
telemt_upstream_connect_success_total 34517
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 34942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 1925
telemt_me_reconnect_attempts_total 42727
telemt_me_reconnect_success_total 28995
telemt_me_reader_eof_total 30494
telemt_me_idle_close_by_peer_total 30494
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 472399
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1177598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4302
telemt_desync_full_logged_total 1543
telemt_desync_suppressed_total 2759
telemt_desync_frames_bucket_total{bucket="1_2"} 1302
telemt_desync_frames_bucket_total{bucket="3_10"} 1406
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29756
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28945
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1177453
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 14377396676 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 402413607932 (374.78 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 61
```