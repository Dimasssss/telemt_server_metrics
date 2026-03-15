# Server Metrics 2026-03-15 04:23:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 22118.8 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277173
telemt_connections_bad_total 3764
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 4710
telemt_upstream_connect_success_total 4692
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3595
telemt_me_reconnect_success_total 3576
telemt_me_reader_eof_total 3780
telemt_me_idle_close_by_peer_total 3780
telemt_me_route_drop_no_conn_total 87245
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245737
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3617
telemt_me_writer_restored_same_endpoint_total 3565
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 245708
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 2590919536 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 87446713396 (81.44 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 22119.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110331
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4336
telemt_upstream_connect_attempt_total 6595
telemt_upstream_connect_success_total 6568
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5165
telemt_me_reconnect_success_total 5139
telemt_me_reader_eof_total 5431
telemt_me_idle_close_by_peer_total 5431
telemt_me_route_drop_no_conn_total 22565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85184
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5142
telemt_me_writer_restored_same_endpoint_total 5131
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 85480
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1749443863 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 24896879216 (23.19 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 22119.8 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194480
telemt_connections_bad_total 3611
telemt_handshake_timeouts_total 20903
telemt_upstream_connect_attempt_total 5187
telemt_upstream_connect_success_total 5166
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4063
telemt_me_reconnect_success_total 4044
telemt_me_reader_eof_total 4274
telemt_me_idle_close_by_peer_total 4274
telemt_me_route_drop_no_conn_total 42215
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 291
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4086
telemt_me_writer_restored_same_endpoint_total 4025
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 166058
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 1373279224 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 51833350592 (48.27 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 22119.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151084
telemt_connections_bad_total 33027
telemt_handshake_timeouts_total 7910
telemt_upstream_connect_attempt_total 7886
telemt_upstream_connect_success_total 7715
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11364
telemt_me_reconnect_success_total 6594
telemt_me_reader_eof_total 6945
telemt_me_idle_close_by_peer_total 6945
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 31231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108029
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6802
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6574
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 108032
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 909629048 (867.49 MB)
telemt_user_octets_to_client{user="hello"} 36459365636 (33.96 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 22120.3 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92969
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1096
telemt_upstream_connect_attempt_total 5126
telemt_upstream_connect_success_total 5102
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 3999
telemt_me_reconnect_success_total 3983
telemt_me_reader_eof_total 4245
telemt_me_idle_close_by_peer_total 4245
telemt_me_route_drop_no_conn_total 24624
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88921
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 384
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4020
telemt_me_writer_restored_same_endpoint_total 3975
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 88919
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 754822184 (719.85 MB)
telemt_user_octets_to_client{user="hello"} 27966872576 (26.05 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 33
```