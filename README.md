# Server Metrics 2026-03-15 07:57:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 34956.3 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656884
telemt_connections_bad_total 25577
telemt_handshake_timeouts_total 4482
telemt_upstream_connect_attempt_total 7234
telemt_upstream_connect_success_total 7207
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5499
telemt_me_reconnect_success_total 5471
telemt_me_reader_eof_total 5789
telemt_me_idle_close_by_peer_total 5789
telemt_me_route_drop_no_conn_total 206085
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553243
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1546
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1060
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5544
telemt_me_writer_restored_same_endpoint_total 5460
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 553238
telemt_user_connections_current{user="hello"} 1699
telemt_user_octets_from_client{user="hello"} 6991501772 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 205525262056 (191.41 GB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 34957.1 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249158
telemt_connections_bad_total 18361
telemt_handshake_timeouts_total 10092
telemt_upstream_connect_attempt_total 9590
telemt_upstream_connect_success_total 9543
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7526
telemt_me_reconnect_success_total 7480
telemt_me_reader_eof_total 7917
telemt_me_idle_close_by_peer_total 7917
telemt_me_route_drop_no_conn_total 64213
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202456
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 748
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7527
telemt_me_writer_restored_same_endpoint_total 7472
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 202736
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 3100794483 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 74322470684 (69.22 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 34957.2 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444737
telemt_connections_bad_total 12902
telemt_handshake_timeouts_total 41323
telemt_upstream_connect_attempt_total 7803
telemt_upstream_connect_success_total 7769
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6058
telemt_me_reconnect_success_total 6023
telemt_me_reader_eof_total 6380
telemt_me_idle_close_by_peer_total 6380
telemt_me_route_drop_no_conn_total 116165
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360807
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 688
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 416
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6094
telemt_me_writer_restored_same_endpoint_total 6004
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 360589
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 5523273112 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 151079879380 (140.70 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 34957.0 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285970
telemt_connections_bad_total 46358
telemt_handshake_timeouts_total 20024
telemt_upstream_connect_attempt_total 11262
telemt_upstream_connect_success_total 11002
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 11262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21901
telemt_me_reconnect_success_total 9263
telemt_me_reader_eof_total 9939
telemt_me_idle_close_by_peer_total 9939
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 72144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212804
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 386
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9733
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9237
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 212805
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 1852858748 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 71253981912 (66.36 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 34957.9 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226940
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 2241
telemt_upstream_connect_attempt_total 7721
telemt_upstream_connect_success_total 7689
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5981
telemt_me_reconnect_success_total 5952
telemt_me_reader_eof_total 6348
telemt_me_idle_close_by_peer_total 6348
telemt_me_route_drop_no_conn_total 68579
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210837
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6014
telemt_me_writer_restored_same_endpoint_total 5944
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 210852
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 2188533712 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 85779775548 (79.89 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 101
```