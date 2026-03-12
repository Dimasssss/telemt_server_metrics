# Server Metrics 2026-03-12 18:55:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46601.8 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1661109
telemt_connections_bad_total 20515
telemt_handshake_timeouts_total 15502
telemt_upstream_connect_attempt_total 9227
telemt_upstream_connect_success_total 9174
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 569
telemt_me_reconnect_attempts_total 15660
telemt_me_reconnect_success_total 6813
telemt_me_reader_eof_total 7377
telemt_me_idle_close_by_peer_total 7376
telemt_me_route_drop_no_conn_total 649151
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1552825
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7919
telemt_desync_full_logged_total 2010
telemt_desync_suppressed_total 5909
telemt_desync_frames_bucket_total{bucket="1_2"} 2061
telemt_desync_frames_bucket_total{bucket="3_10"} 2865
telemt_desync_frames_bucket_total{bucket="gt_10"} 2993
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7185
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6800
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 1552310
telemt_user_connections_current{user="hello"} 1422
telemt_user_octets_from_client{user="hello"} 23925458508 (22.28 GB)
telemt_user_octets_to_client{user="hello"} 528405859788 (492.12 GB)
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76222.4 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711005
telemt_connections_bad_total 9416
telemt_handshake_timeouts_total 29551
telemt_upstream_connect_attempt_total 19459
telemt_upstream_connect_success_total 19430
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3367
telemt_me_reconnect_attempts_total 14049
telemt_me_reconnect_success_total 13964
telemt_me_reader_eof_total 14847
telemt_me_idle_close_by_peer_total 14847
telemt_me_route_drop_no_conn_total 226883
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640300
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2820
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1956
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 922
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14114
telemt_me_writer_restored_same_endpoint_total 13955
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 642179
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 9826748828 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 241343387119 (224.77 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76222.3 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1472754
telemt_connections_bad_total 7176
telemt_handshake_timeouts_total 101498
telemt_upstream_connect_attempt_total 18107
telemt_upstream_connect_success_total 18102
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15164
telemt_me_reconnect_success_total 13920
telemt_me_reader_eof_total 14679
telemt_me_idle_close_by_peer_total 14678
telemt_me_route_drop_no_conn_total 485669
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125790
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4716
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 3263
telemt_desync_frames_bucket_total{bucket="1_2"} 742
telemt_desync_frames_bucket_total{bucket="3_10"} 1708
telemt_desync_frames_bucket_total{bucket="gt_10"} 2266
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14045
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13879
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1125653
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 17679801296 (16.47 GB)
telemt_user_octets_to_client{user="hello"} 411391203981 (383.14 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76222.9 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899094
telemt_connections_bad_total 12953
telemt_handshake_timeouts_total 66378
telemt_upstream_connect_attempt_total 19675
telemt_upstream_connect_success_total 19598
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 23507
telemt_me_reconnect_success_total 15782
telemt_me_reader_eof_total 16858
telemt_me_idle_close_by_peer_total 16858
telemt_me_route_drop_no_conn_total 317000
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1739
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1156
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 16150
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15761
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 776721
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 9694290020 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 320150137436 (298.16 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76222.6 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007149
telemt_connections_bad_total 11491
telemt_handshake_timeouts_total 8291
telemt_upstream_connect_attempt_total 23875
telemt_upstream_connect_success_total 23588
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 23875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 1389
telemt_me_reconnect_attempts_total 30790
telemt_me_reconnect_success_total 19756
telemt_me_reader_eof_total 20757
telemt_me_idle_close_by_peer_total 20757
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 375584
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924266
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3501
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20322
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19712
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 924138
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 11445800512 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 310801159336 (289.46 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 84
```