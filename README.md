# Server Metrics 2026-03-15 06:10:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 28534.5 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421367
telemt_connections_bad_total 6509
telemt_handshake_timeouts_total 2092
telemt_upstream_connect_attempt_total 6056
telemt_upstream_connect_success_total 6032
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4630
telemt_me_reconnect_success_total 4606
telemt_me_reader_eof_total 4861
telemt_me_idle_close_by_peer_total 4861
telemt_me_route_drop_no_conn_total 132633
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367207
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4657
telemt_me_writer_restored_same_endpoint_total 4595
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 367221
telemt_user_connections_current{user="hello"} 1481
telemt_user_octets_from_client{user="hello"} 4167560544 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 133272851500 (124.12 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 28534.3 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157456
telemt_connections_bad_total 18312
telemt_handshake_timeouts_total 5318
telemt_upstream_connect_attempt_total 8222
telemt_upstream_connect_success_total 8183
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 6473
telemt_me_reconnect_success_total 6441
telemt_me_reader_eof_total 6816
telemt_me_idle_close_by_peer_total 6816
telemt_me_route_drop_no_conn_total 38140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129277
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6461
telemt_me_writer_restored_same_endpoint_total 6433
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 129572
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 2199251295 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 43880393260 (40.87 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 28534.3 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292954
telemt_connections_bad_total 7354
telemt_handshake_timeouts_total 29669
telemt_upstream_connect_attempt_total 6647
telemt_upstream_connect_success_total 6618
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 5210
telemt_me_reconnect_success_total 5184
telemt_me_reader_eof_total 5479
telemt_me_idle_close_by_peer_total 5479
telemt_me_route_drop_no_conn_total 73302
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243895
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5239
telemt_me_writer_restored_same_endpoint_total 5165
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 243699
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 3962490168 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 101266795396 (94.31 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 28534.0 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205629
telemt_connections_bad_total 38343
telemt_handshake_timeouts_total 13863
telemt_upstream_connect_attempt_total 9822
telemt_upstream_connect_success_total 9610
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14173
telemt_me_reconnect_success_total 8180
telemt_me_reader_eof_total 8636
telemt_me_idle_close_by_peer_total 8636
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 48208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149331
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 174
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8434
telemt_me_refill_failed_total 186
telemt_me_writer_restored_same_endpoint_total 8154
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 149334
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 1293122396 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 52848587784 (49.22 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 28535.0 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142088
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 1498
telemt_upstream_connect_attempt_total 6469
telemt_upstream_connect_success_total 6442
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5038
telemt_me_reconnect_success_total 5016
telemt_me_reader_eof_total 5353
telemt_me_idle_close_by_peer_total 5353
telemt_me_route_drop_no_conn_total 40097
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134443
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5066
telemt_me_writer_restored_same_endpoint_total 5008
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 134461
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 1281411064 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 46570276688 (43.37 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 70
```