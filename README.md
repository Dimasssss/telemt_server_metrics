# Server Metrics 2026-03-15 04:02:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 20897.2 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257835
telemt_connections_bad_total 3550
telemt_handshake_timeouts_total 1289
telemt_upstream_connect_attempt_total 4490
telemt_upstream_connect_success_total 4472
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3418
telemt_me_reconnect_success_total 3400
telemt_me_reader_eof_total 3594
telemt_me_idle_close_by_peer_total 3594
telemt_me_route_drop_no_conn_total 80324
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228146
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3439
telemt_me_writer_restored_same_endpoint_total 3389
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 228120
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 2450105572 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 81160075988 (75.59 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 20897.8 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103923
telemt_connections_bad_total 17648
telemt_handshake_timeouts_total 4093
telemt_upstream_connect_attempt_total 6256
telemt_upstream_connect_success_total 6229
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 4869
telemt_me_reconnect_success_total 4846
telemt_me_reader_eof_total 5120
telemt_me_idle_close_by_peer_total 5120
telemt_me_route_drop_no_conn_total 20536
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79625
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 131
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4843
telemt_me_writer_restored_same_endpoint_total 4838
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 79921
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 1707685611 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 23772066724 (22.14 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 20897.9 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180265
telemt_connections_bad_total 3605
telemt_handshake_timeouts_total 18810
telemt_upstream_connect_attempt_total 4877
telemt_upstream_connect_success_total 4856
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3796
telemt_me_reconnect_success_total 3777
telemt_me_reader_eof_total 3993
telemt_me_idle_close_by_peer_total 3993
telemt_me_route_drop_no_conn_total 39056
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154691
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3816
telemt_me_writer_restored_same_endpoint_total 3758
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 154574
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 1298010096 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 47364810068 (44.11 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 20897.9 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142096
telemt_connections_bad_total 32078
telemt_handshake_timeouts_total 6451
telemt_upstream_connect_attempt_total 7315
telemt_upstream_connect_success_total 7156
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 7315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9632
telemt_me_reconnect_success_total 6078
telemt_me_reader_eof_total 6389
telemt_me_idle_close_by_peer_total 6389
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 28826
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101554
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6246
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 6058
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 101559
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 814190416 (776.47 MB)
telemt_user_octets_to_client{user="hello"} 30392957800 (28.31 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 20898.8 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87100
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 4859
telemt_upstream_connect_success_total 4836
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3777
telemt_me_reconnect_success_total 3762
telemt_me_reader_eof_total 4014
telemt_me_idle_close_by_peer_total 4014
telemt_me_route_drop_no_conn_total 22868
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83288
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3797
telemt_me_writer_restored_same_endpoint_total 3754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 83286
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 706281068 (673.56 MB)
telemt_user_octets_to_client{user="hello"} 26560558816 (24.74 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 40
```