# Server Metrics 2026-03-15 05:19:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 25478.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334831
telemt_connections_bad_total 4932
telemt_handshake_timeouts_total 1521
telemt_upstream_connect_attempt_total 5486
telemt_upstream_connect_success_total 5465
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4195
telemt_me_reconnect_success_total 4174
telemt_me_reader_eof_total 4413
telemt_me_idle_close_by_peer_total 4413
telemt_me_route_drop_no_conn_total 107170
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298447
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 714
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4222
telemt_me_writer_restored_same_endpoint_total 4163
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 298465
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 3340786488 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 110095277724 (102.53 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 25479.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130243
telemt_connections_bad_total 18275
telemt_handshake_timeouts_total 4539
telemt_upstream_connect_attempt_total 7603
telemt_upstream_connect_success_total 7569
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 5989
telemt_me_reconnect_success_total 5960
telemt_me_reader_eof_total 6300
telemt_me_idle_close_by_peer_total 6300
telemt_me_route_drop_no_conn_total 29525
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104105
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 280
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5970
telemt_me_writer_restored_same_endpoint_total 5952
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 104402
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 1915478195 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 33856317468 (31.53 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 25479.9 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243140
telemt_connections_bad_total 4473
telemt_handshake_timeouts_total 26320
telemt_upstream_connect_attempt_total 5945
telemt_upstream_connect_success_total 5918
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4643
telemt_me_reconnect_success_total 4619
telemt_me_reader_eof_total 4893
telemt_me_idle_close_by_peer_total 4893
telemt_me_route_drop_no_conn_total 57621
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202094
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 335
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4667
telemt_me_writer_restored_same_endpoint_total 4600
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 201911
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 2706374104 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 76238604540 (71.00 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 25479.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178954
telemt_connections_bad_total 35908
telemt_handshake_timeouts_total 13045
telemt_upstream_connect_attempt_total 8789
telemt_upstream_connect_success_total 8603
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 8789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12079
telemt_me_reconnect_success_total 7307
telemt_me_reader_eof_total 7719
telemt_me_idle_close_by_peer_total 7719
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 38961
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126705
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 7516
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 7284
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 126708
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 1043331664 (995.00 MB)
telemt_user_octets_to_client{user="hello"} 45295249864 (42.18 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 25480.8 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114899
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1302
telemt_upstream_connect_attempt_total 5887
telemt_upstream_connect_success_total 5862
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4587
telemt_me_reconnect_success_total 4567
telemt_me_reader_eof_total 4875
telemt_me_idle_close_by_peer_total 4875
telemt_me_route_drop_no_conn_total 31653
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109705
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 446
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4612
telemt_me_writer_restored_same_endpoint_total 4559
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 109703
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 1056855816 (1007.90 MB)
telemt_user_octets_to_client{user="hello"} 37522607732 (34.95 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 57
```