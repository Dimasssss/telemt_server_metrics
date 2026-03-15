# Server Metrics 2026-03-15 17:24:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 68980.3 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2407615
telemt_connections_bad_total 148185
telemt_handshake_timeouts_total 30517
telemt_upstream_connect_attempt_total 13458
telemt_upstream_connect_success_total 13400
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14845
telemt_me_reconnect_success_total 9948
telemt_me_reader_eof_total 10633
telemt_me_idle_close_by_peer_total 10633
telemt_me_route_drop_no_conn_total 828398
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2009351
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7869
telemt_desync_full_logged_total 2132
telemt_desync_suppressed_total 5737
telemt_desync_frames_bucket_total{bucket="1_2"} 1911
telemt_desync_frames_bucket_total{bucket="3_10"} 3023
telemt_desync_frames_bucket_total{bucket="gt_10"} 2935
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10267
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9937
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 2008834
telemt_user_connections_current{user="hello"} 2337
telemt_user_octets_from_client{user="hello"} 29625785964 (27.59 GB)
telemt_user_octets_to_client{user="hello"} 761885966872 (709.56 GB)
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 68981.1 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928120
telemt_connections_bad_total 49637
telemt_handshake_timeouts_total 62003
telemt_upstream_connect_attempt_total 17308
telemt_upstream_connect_success_total 17216
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 17308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14613
telemt_me_reconnect_success_total 13406
telemt_me_reader_eof_total 14182
telemt_me_idle_close_by_peer_total 14182
telemt_me_route_drop_no_conn_total 240136
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717713
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2181
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1448
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13619
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13394
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 717948
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 10415027599 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 271830552884 (253.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 68981.1 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2081547
telemt_connections_bad_total 49612
telemt_handshake_timeouts_total 211709
telemt_upstream_connect_attempt_total 14964
telemt_upstream_connect_success_total 14894
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12679
telemt_me_reconnect_success_total 11410
telemt_me_reader_eof_total 12089
telemt_me_idle_close_by_peer_total 12089
telemt_me_route_drop_no_conn_total 539314
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1279397
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3274
telemt_desync_full_logged_total 1181
telemt_desync_suppressed_total 2093
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 1258
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11612
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11391
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 1275328
telemt_user_connections_current{user="hello"} 1402
telemt_user_octets_from_client{user="hello"} 19744367872 (18.39 GB)
telemt_user_octets_to_client{user="hello"} 455612257748 (424.32 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 68980.8 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999117
telemt_connections_bad_total 82043
telemt_handshake_timeouts_total 48333
telemt_upstream_connect_attempt_total 170383
telemt_upstream_connect_success_total 169814
telemt_upstream_connect_fail_total 569
telemt_upstream_connect_attempts_per_request{bucket="1"} 170383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 569
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 60094
telemt_me_reconnect_success_total 13390
telemt_me_reader_eof_total 15209
telemt_me_idle_close_by_peer_total 15209
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 232472
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618595
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1286
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14991
telemt_me_refill_failed_total 1461
telemt_me_writer_restored_same_endpoint_total 13354
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1601
telemt_user_connections_total{user="hello"} 771117
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 14365793589 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 275885856692 (256.94 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 68981.9 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007875
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22725
telemt_upstream_connect_attempt_total 15262
telemt_upstream_connect_success_total 15179
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15412
telemt_me_reconnect_success_total 11717
telemt_me_reader_eof_total 12498
telemt_me_idle_close_by_peer_total 12498
telemt_me_route_drop_no_conn_total 251457
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833683
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2802
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 1856
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11974
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11709
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 833713
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 10416219188 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 294798908064 (274.55 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 115
```