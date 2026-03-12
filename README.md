# Server Metrics 2026-03-12 04:53:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25704.7 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254751
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 3891
telemt_upstream_connect_attempt_total 5828
telemt_upstream_connect_success_total 5828
telemt_upstream_connect_attempts_per_request{bucket="1"} 5828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4550
telemt_me_reconnect_success_total 4533
telemt_me_reader_eof_total 4792
telemt_me_idle_close_by_peer_total 4792
telemt_me_route_drop_no_conn_total 91108
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242690
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4579
telemt_me_writer_restored_same_endpoint_total 4517
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 242421
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 2365224464 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 75021891108 (69.87 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 25705.4 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85000
telemt_connections_bad_total 639
telemt_handshake_timeouts_total 1637
telemt_upstream_connect_attempt_total 7100
telemt_upstream_connect_success_total 7097
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 5637
telemt_me_reconnect_success_total 5605
telemt_me_reader_eof_total 5956
telemt_me_idle_close_by_peer_total 5956
telemt_me_route_drop_no_conn_total 24982
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5649
telemt_me_writer_restored_same_endpoint_total 5596
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 76991
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 1236575923 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 28730203754 (26.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 25705.2 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369867
telemt_connections_bad_total 1816
telemt_handshake_timeouts_total 24036
telemt_upstream_connect_attempt_total 7390
telemt_upstream_connect_success_total 7388
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 5784
telemt_me_reconnect_success_total 5723
telemt_me_reader_eof_total 5982
telemt_me_idle_close_by_peer_total 5982
telemt_me_route_drop_no_conn_total 46925
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143498
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 509
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5694
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5682
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 143814
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1419355156 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 44018611513 (41.00 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 25705.6 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124626
telemt_connections_bad_total 1672
telemt_handshake_timeouts_total 8015
telemt_upstream_connect_attempt_total 7643
telemt_upstream_connect_success_total 7609
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 6327
telemt_me_reconnect_success_total 6305
telemt_me_reader_eof_total 6696
telemt_me_idle_close_by_peer_total 6696
telemt_me_route_drop_no_conn_total 41857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113303
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6345
telemt_me_writer_restored_same_endpoint_total 6284
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 113284
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 878584048 (837.88 MB)
telemt_user_octets_to_client{user="hello"} 32792018788 (30.54 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25705.4 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144649
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 859
telemt_upstream_connect_attempt_total 9514
telemt_upstream_connect_success_total 9409
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 9514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 9598
telemt_me_reconnect_success_total 8094
telemt_me_reader_eof_total 8419
telemt_me_idle_close_by_peer_total 8419
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 40932
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138308
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 516
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8208
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8076
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 138287
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 957545464 (913.19 MB)
telemt_user_octets_to_client{user="hello"} 30566175168 (28.47 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 51
```