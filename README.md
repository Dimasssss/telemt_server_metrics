# Server Metrics 2026-03-15 02:51:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 16621.7 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202004
telemt_connections_bad_total 2705
telemt_handshake_timeouts_total 621
telemt_upstream_connect_attempt_total 3553
telemt_upstream_connect_success_total 3541
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2703
telemt_me_reconnect_success_total 2690
telemt_me_reader_eof_total 2838
telemt_me_idle_close_by_peer_total 2838
telemt_me_route_drop_no_conn_total 62408
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178482
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2719
telemt_me_writer_restored_same_endpoint_total 2679
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 178462
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 1933595716 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 64192962812 (59.78 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 16622.3 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83189
telemt_connections_bad_total 14430
telemt_handshake_timeouts_total 3681
telemt_upstream_connect_attempt_total 4916
telemt_upstream_connect_success_total 4893
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 3751
telemt_me_reconnect_success_total 3730
telemt_me_reader_eof_total 3919
telemt_me_idle_close_by_peer_total 3919
telemt_me_route_drop_no_conn_total 16005
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62980
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3716
telemt_me_writer_restored_same_endpoint_total 3722
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 63276
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1582525911 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 19481223752 (18.14 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 16622.5 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138718
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 12921
telemt_upstream_connect_attempt_total 3927
telemt_upstream_connect_success_total 3909
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3068
telemt_me_reconnect_success_total 3056
telemt_me_reader_eof_total 3228
telemt_me_idle_close_by_peer_total 3228
telemt_me_route_drop_no_conn_total 29954
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120288
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3088
telemt_me_writer_restored_same_endpoint_total 3037
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 120198
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1083525908 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 37796788136 (35.20 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 16622.3 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115173
telemt_connections_bad_total 28767
telemt_handshake_timeouts_total 3039
telemt_upstream_connect_attempt_total 6052
telemt_upstream_connect_success_total 5924
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8618
telemt_me_reconnect_success_total 5068
telemt_me_reader_eof_total 5336
telemt_me_idle_close_by_peer_total 5336
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 22014
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81622
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5223
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5049
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 81634
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 477106432 (455.00 MB)
telemt_user_octets_to_client{user="hello"} 21601150436 (20.12 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 16623.2 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69334
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 960
telemt_upstream_connect_attempt_total 3834
telemt_upstream_connect_success_total 3817
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 2974
telemt_me_reconnect_success_total 2962
telemt_me_reader_eof_total 3148
telemt_me_idle_close_by_peer_total 3148
telemt_me_route_drop_no_conn_total 17827
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66254
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2986
telemt_me_writer_restored_same_endpoint_total 2954
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 66254
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 576912900 (550.19 MB)
telemt_user_octets_to_client{user="hello"} 21776732616 (20.28 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 35
```