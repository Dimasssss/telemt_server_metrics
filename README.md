# Server Metrics 2026-03-14 20:08:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 24674.2 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955405
telemt_connections_bad_total 40394
telemt_handshake_timeouts_total 14299
telemt_upstream_connect_attempt_total 4537
telemt_upstream_connect_success_total 4517
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 4537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 4034
telemt_me_reconnect_success_total 3229
telemt_me_reader_eof_total 3402
telemt_me_idle_close_by_peer_total 3402
telemt_me_route_drop_no_conn_total 366641
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847185
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2961
telemt_desync_full_logged_total 833
telemt_desync_suppressed_total 2128
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 1084
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3309
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3220
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 847132
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 15207190068 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 280064798864 (260.83 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 24679.3 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372340
telemt_connections_bad_total 26637
telemt_handshake_timeouts_total 11055
telemt_upstream_connect_attempt_total 5258
telemt_upstream_connect_success_total 5203
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 445
telemt_me_reconnect_attempts_total 4712
telemt_me_reconnect_success_total 3918
telemt_me_reader_eof_total 4098
telemt_me_idle_close_by_peer_total 4098
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 112926
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314007
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1501
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4027
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3896
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 313940
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 4744440596 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 110072257840 (102.51 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 24542.1 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796853
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 176627
telemt_upstream_connect_attempt_total 4745
telemt_upstream_connect_success_total 4729
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 7365
telemt_me_reconnect_success_total 3455
telemt_me_reader_eof_total 3709
telemt_me_idle_close_by_peer_total 3709
telemt_me_route_drop_no_conn_total 187090
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526535
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1923
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1164
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3613
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3422
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 526364
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 7764737784 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 189169560600 (176.18 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 24396.7 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433841
telemt_connections_bad_total 96254
telemt_handshake_timeouts_total 51737
telemt_upstream_connect_attempt_total 5708
telemt_upstream_connect_success_total 5707
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 5360
telemt_me_reconnect_success_total 4439
telemt_me_reader_eof_total 4644
telemt_me_idle_close_by_peer_total 4644
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 99127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278690
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 614
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4517
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4428
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 278607
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 3930921048 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 86821712124 (80.86 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 24692.1 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365897
telemt_connections_bad_total 1331
telemt_handshake_timeouts_total 3844
telemt_upstream_connect_attempt_total 5327
telemt_upstream_connect_success_total 5219
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 5327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 4624
telemt_me_reconnect_success_total 3951
telemt_me_reader_eof_total 4165
telemt_me_idle_close_by_peer_total 4165
telemt_me_route_drop_no_conn_total 115857
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338869
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4043
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3933
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 338841
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 5534010840 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 144255040640 (134.35 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 76
```