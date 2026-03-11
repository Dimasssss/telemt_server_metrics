# Server Metrics 2026-03-11 04:09:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49342.8 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946840
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 26578
telemt_upstream_connect_attempt_total 10625
telemt_upstream_connect_success_total 10616
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 527
telemt_me_reconnect_attempts_total 19781
telemt_me_reconnect_success_total 8108
telemt_me_reader_eof_total 8842
telemt_me_idle_close_by_peer_total 8842
telemt_me_route_drop_no_conn_total 362244
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865222
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3930
telemt_desync_full_logged_total 1099
telemt_desync_suppressed_total 2831
telemt_desync_frames_bucket_total{bucket="1_2"} 1118
telemt_desync_frames_bucket_total{bucket="3_10"} 1474
telemt_desync_frames_bucket_total{bucket="gt_10"} 1338
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8547
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8102
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 864943
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 11391718108 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 255930955736 (238.35 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49399.3 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382237
telemt_connections_bad_total 2531
telemt_handshake_timeouts_total 18814
telemt_upstream_connect_attempt_total 18751
telemt_upstream_connect_success_total 15856
telemt_upstream_connect_fail_total 2895
telemt_upstream_connect_attempts_per_request{bucket="1"} 18751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2895
telemt_me_keepalive_timeout_total 1773
telemt_me_reconnect_attempts_total 11251
telemt_me_reconnect_success_total 10433
telemt_me_reader_eof_total 11024
telemt_me_idle_close_by_peer_total 11022
telemt_me_route_drop_no_conn_total 183577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327796
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1836
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10556
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10412
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 330072
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 3136456598 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 77564356516 (72.24 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49399.2 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642670
telemt_connections_bad_total 5372
telemt_handshake_timeouts_total 35704
telemt_upstream_connect_attempt_total 13345
telemt_upstream_connect_success_total 13173
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 13345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 20691
telemt_me_reconnect_success_total 9621
telemt_me_reader_eof_total 10417
telemt_me_idle_close_by_peer_total 10417
telemt_me_route_drop_no_conn_total 217558
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572241
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 10095
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9610
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 573132
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 7235371905 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 173566714241 (161.65 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49399.5 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488342
telemt_connections_bad_total 46555
telemt_handshake_timeouts_total 50326
telemt_upstream_connect_attempt_total 14341
telemt_upstream_connect_success_total 14341
telemt_upstream_connect_attempts_per_request{bucket="1"} 14341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 12908
telemt_me_reconnect_success_total 11868
telemt_me_reader_eof_total 12602
telemt_me_idle_close_by_peer_total 12602
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 145285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377385
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 813
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 12007
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11848
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 377055
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 4562903828 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 100819869128 (93.90 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49399.4 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513509
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 3202
telemt_upstream_connect_attempt_total 14346
telemt_upstream_connect_success_total 14288
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 549
telemt_me_reconnect_attempts_total 15552
telemt_me_reconnect_success_total 11771
telemt_me_reader_eof_total 12428
telemt_me_idle_close_by_peer_total 12428
telemt_me_route_drop_no_conn_total 165931
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467265
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2375
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 12039
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11771
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 466894
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 8711095552 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 165969440040 (154.57 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 49
```