# Server Metrics 2026-03-15 04:33:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 22729.6 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286112
telemt_connections_bad_total 3881
telemt_handshake_timeouts_total 1383
telemt_upstream_connect_attempt_total 4852
telemt_upstream_connect_success_total 4834
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3694
telemt_me_reconnect_success_total 3674
telemt_me_reader_eof_total 3887
telemt_me_idle_close_by_peer_total 3887
telemt_me_route_drop_no_conn_total 90495
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253919
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 660
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3716
telemt_me_writer_restored_same_endpoint_total 3663
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 253890
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 2717068444 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 90221952008 (84.03 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 22730.2 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112876
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4366
telemt_upstream_connect_attempt_total 6820
telemt_upstream_connect_success_total 6792
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5343
telemt_me_reconnect_success_total 5317
telemt_me_reader_eof_total 5610
telemt_me_idle_close_by_peer_total 5610
telemt_me_route_drop_no_conn_total 23382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87661
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 166
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5321
telemt_me_writer_restored_same_endpoint_total 5309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 87956
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 1764984831 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 25398024388 (23.65 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 22730.5 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201658
telemt_connections_bad_total 3628
telemt_handshake_timeouts_total 22367
telemt_upstream_connect_attempt_total 5335
telemt_upstream_connect_success_total 5313
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 4167
telemt_me_reconnect_success_total 4148
telemt_me_reader_eof_total 4390
telemt_me_idle_close_by_peer_total 4390
telemt_me_route_drop_no_conn_total 44760
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171602
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4192
telemt_me_writer_restored_same_endpoint_total 4129
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 171476
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 1401540624 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 53644082668 (49.96 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 22730.1 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155533
telemt_connections_bad_total 33494
telemt_handshake_timeouts_total 8733
telemt_upstream_connect_attempt_total 8117
telemt_upstream_connect_success_total 7946
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 8117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11552
telemt_me_reconnect_success_total 6781
telemt_me_reader_eof_total 7159
telemt_me_idle_close_by_peer_total 7159
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 32591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111000
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6989
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6761
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 111003
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 931204044 (888.07 MB)
telemt_user_octets_to_client{user="hello"} 37297122092 (34.74 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 22731.0 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95894
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 1152
telemt_upstream_connect_attempt_total 5280
telemt_upstream_connect_success_total 5256
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4110
telemt_me_reconnect_success_total 4093
telemt_me_reader_eof_total 4367
telemt_me_idle_close_by_peer_total 4367
telemt_me_route_drop_no_conn_total 25434
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91700
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 402
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4132
telemt_me_writer_restored_same_endpoint_total 4085
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 91698
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 784749904 (748.40 MB)
telemt_user_octets_to_client{user="hello"} 28489535780 (26.53 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 40
```