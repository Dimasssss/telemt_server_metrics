# Server Metrics 2026-03-15 05:34:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 26395.4 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354929
telemt_connections_bad_total 5340
telemt_handshake_timeouts_total 1636
telemt_upstream_connect_attempt_total 5657
telemt_upstream_connect_success_total 5636
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4321
telemt_me_reconnect_success_total 4300
telemt_me_reader_eof_total 4548
telemt_me_idle_close_by_peer_total 4548
telemt_me_route_drop_no_conn_total 113696
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316538
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 749
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 522
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4349
telemt_me_writer_restored_same_endpoint_total 4289
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 316556
telemt_user_connections_current{user="hello"} 1194
telemt_user_octets_from_client{user="hello"} 3592255560 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 115728034456 (107.78 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 26396.0 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137915
telemt_connections_bad_total 18306
telemt_handshake_timeouts_total 4766
telemt_upstream_connect_attempt_total 7795
telemt_upstream_connect_success_total 7759
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 7795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6137
telemt_me_reconnect_success_total 6106
telemt_me_reader_eof_total 6460
telemt_me_idle_close_by_peer_total 6460
telemt_me_route_drop_no_conn_total 31611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111322
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6123
telemt_me_writer_restored_same_endpoint_total 6098
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 111618
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 1969574307 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 36623325620 (34.11 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 26396.2 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256944
telemt_connections_bad_total 5251
telemt_handshake_timeouts_total 27246
telemt_upstream_connect_attempt_total 6141
telemt_upstream_connect_success_total 6114
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4794
telemt_me_reconnect_success_total 4769
telemt_me_reader_eof_total 5046
telemt_me_idle_close_by_peer_total 5046
telemt_me_route_drop_no_conn_total 61882
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213371
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4820
telemt_me_writer_restored_same_endpoint_total 4750
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 213188
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 3259224280 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 85482347116 (79.61 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 26396.0 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186756
telemt_connections_bad_total 36608
telemt_handshake_timeouts_total 13448
telemt_upstream_connect_attempt_total 9023
telemt_upstream_connect_success_total 8831
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 9023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12264
telemt_me_reconnect_success_total 7490
telemt_me_reader_eof_total 7902
telemt_me_idle_close_by_peer_total 7902
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 41341
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133162
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 216
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7699
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7467
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 133165
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1089231936 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 47059105376 (43.83 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 26396.7 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122041
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 1326
telemt_upstream_connect_attempt_total 6073
telemt_upstream_connect_success_total 6047
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4729
telemt_me_reconnect_success_total 4709
telemt_me_reader_eof_total 5026
telemt_me_idle_close_by_peer_total 5026
telemt_me_route_drop_no_conn_total 33972
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116570
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 487
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4756
telemt_me_writer_restored_same_endpoint_total 4701
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 116568
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 1105264004 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 39830380712 (37.09 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 45
```