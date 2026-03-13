# Server Metrics 2026-03-13 03:30:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77514.6 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2140429
telemt_connections_bad_total 28003
telemt_handshake_timeouts_total 22894
telemt_upstream_connect_attempt_total 15359
telemt_upstream_connect_success_total 15272
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1295
telemt_me_reconnect_attempts_total 20248
telemt_me_reconnect_success_total 11386
telemt_me_reader_eof_total 12296
telemt_me_idle_close_by_peer_total 12295
telemt_me_route_drop_no_conn_total 820668
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1968511
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8782
telemt_desync_full_logged_total 2284
telemt_desync_suppressed_total 6498
telemt_desync_frames_bucket_total{bucket="1_2"} 2314
telemt_desync_frames_bucket_total{bucket="3_10"} 3167
telemt_desync_frames_bucket_total{bucket="gt_10"} 3301
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11822
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11373
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 1967958
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 28624178024 (26.66 GB)
telemt_user_octets_to_client{user="hello"} 679682685988 (633.00 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107135.1 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872082
telemt_connections_bad_total 11845
telemt_handshake_timeouts_total 37720
telemt_upstream_connect_attempt_total 27287
telemt_upstream_connect_success_total 27258
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3462
telemt_me_reconnect_attempts_total 20398
telemt_me_reconnect_success_total 20287
telemt_me_reader_eof_total 21617
telemt_me_idle_close_by_peer_total 21617
telemt_me_route_drop_no_conn_total 279439
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786843
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3115
telemt_desync_full_logged_total 979
telemt_desync_suppressed_total 2136
telemt_desync_frames_bucket_total{bucket="1_2"} 1264
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20484
telemt_me_writer_restored_same_endpoint_total 20278
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 788747
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 12578229328 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 303039673043 (282.23 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107134.9 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1803548
telemt_connections_bad_total 11482
telemt_handshake_timeouts_total 119948
telemt_upstream_connect_attempt_total 24965
telemt_upstream_connect_success_total 24955
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20544
telemt_me_reconnect_success_total 19279
telemt_me_reader_eof_total 20421
telemt_me_idle_close_by_peer_total 20420
telemt_me_route_drop_no_conn_total 585619
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1421897
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5058
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 3512
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 1828
telemt_desync_frames_bucket_total{bucket="gt_10"} 2422
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19459
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19238
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1421491
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 24737856420 (23.04 GB)
telemt_user_octets_to_client{user="hello"} 509766917821 (474.76 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107135.3 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123166
telemt_connections_bad_total 13147
telemt_handshake_timeouts_total 74128
telemt_upstream_connect_attempt_total 37236
telemt_upstream_connect_success_total 34956
telemt_upstream_connect_fail_total 2143
telemt_upstream_connect_attempts_per_request{bucket="1"} 36962
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2142
telemt_me_keepalive_timeout_total 11375
telemt_me_reconnect_attempts_total 32699
telemt_me_reconnect_success_total 23771
telemt_me_reader_eof_total 25659
telemt_me_idle_close_by_peer_total 25652
telemt_me_route_drop_no_conn_total 398539
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 964054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24204
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23747
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 969224
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 14825625521 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 382017375174 (355.78 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 107135.1 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244061
telemt_connections_bad_total 12861
telemt_handshake_timeouts_total 9797
telemt_upstream_connect_attempt_total 33644
telemt_upstream_connect_success_total 33235
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 33644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_keepalive_timeout_total 1907
telemt_me_reconnect_attempts_total 41650
telemt_me_reconnect_success_total 27920
telemt_me_reader_eof_total 29381
telemt_me_idle_close_by_peer_total 29381
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 463725
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1150432
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4261
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 2740
telemt_desync_frames_bucket_total{bucket="1_2"} 1290
telemt_desync_frames_bucket_total{bucket="3_10"} 1398
telemt_desync_frames_bucket_total{bucket="gt_10"} 1573
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28669
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27871
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 749
telemt_user_connections_total{user="hello"} 1150287
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 14198065352 (13.22 GB)
telemt_user_octets_to_client{user="hello"} 396750657984 (369.50 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 54
```