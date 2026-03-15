# Server Metrics 2026-03-15 08:22:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 36487.6 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718730
telemt_connections_bad_total 28545
telemt_handshake_timeouts_total 5003
telemt_upstream_connect_attempt_total 7563
telemt_upstream_connect_success_total 7534
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5736
telemt_me_reconnect_success_total 5705
telemt_me_reader_eof_total 6035
telemt_me_idle_close_by_peer_total 6035
telemt_me_route_drop_no_conn_total 230312
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608913
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1821
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1257
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5781
telemt_me_writer_restored_same_endpoint_total 5694
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 608913
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 7713855744 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 228429158356 (212.74 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 36488.6 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280545
telemt_connections_bad_total 18438
telemt_handshake_timeouts_total 11584
telemt_upstream_connect_attempt_total 9906
telemt_upstream_connect_success_total 9857
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 9906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7754
telemt_me_reconnect_success_total 7707
telemt_me_reader_eof_total 8169
telemt_me_idle_close_by_peer_total 8169
telemt_me_route_drop_no_conn_total 70780
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222129
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 830
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 556
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7762
telemt_me_writer_restored_same_endpoint_total 7699
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 222407
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 3297663003 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 82248480436 (76.60 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 36488.6 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483981
telemt_connections_bad_total 14355
telemt_handshake_timeouts_total 43281
telemt_upstream_connect_attempt_total 8180
telemt_upstream_connect_success_total 8143
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6345
telemt_me_reconnect_success_total 6305
telemt_me_reader_eof_total 6679
telemt_me_idle_close_by_peer_total 6679
telemt_me_route_drop_no_conn_total 131170
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393093
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 746
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6382
telemt_me_writer_restored_same_endpoint_total 6286
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 392634
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 5861243196 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 165896886284 (154.50 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 36488.4 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309289
telemt_connections_bad_total 47797
telemt_handshake_timeouts_total 21109
telemt_upstream_connect_attempt_total 11672
telemt_upstream_connect_success_total 11402
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 11672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22214
telemt_me_reconnect_success_total 9573
telemt_me_reader_eof_total 10269
telemt_me_idle_close_by_peer_total 10269
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 80931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230764
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 351
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10045
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9544
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 230764
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 1999749092 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 77202300340 (71.90 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 36489.0 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262487
telemt_connections_bad_total 3627
telemt_handshake_timeouts_total 2581
telemt_upstream_connect_attempt_total 8084
telemt_upstream_connect_success_total 8051
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 6255
telemt_me_reconnect_success_total 6226
telemt_me_reader_eof_total 6636
telemt_me_idle_close_by_peer_total 6636
telemt_me_route_drop_no_conn_total 76150
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 954
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6288
telemt_me_writer_restored_same_endpoint_total 6218
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 234931
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 2528164668 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 92973633460 (86.59 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 115
```