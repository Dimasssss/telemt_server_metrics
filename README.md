# Server Metrics 2026-03-15 09:08:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 39245.2 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839727
telemt_connections_bad_total 38303
telemt_handshake_timeouts_total 6169
telemt_upstream_connect_attempt_total 7949
telemt_upstream_connect_success_total 7916
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5989
telemt_me_reconnect_success_total 5957
telemt_me_reader_eof_total 6305
telemt_me_idle_close_by_peer_total 6305
telemt_me_route_drop_no_conn_total 274464
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711347
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2297
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1592
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6039
telemt_me_writer_restored_same_endpoint_total 5946
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 711334
telemt_user_connections_current{user="hello"} 1958
telemt_user_octets_from_client{user="hello"} 9634444812 (8.97 GB)
telemt_user_octets_to_client{user="hello"} 267973693136 (249.57 GB)
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 39246.1 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331552
telemt_connections_bad_total 18572
telemt_handshake_timeouts_total 13014
telemt_upstream_connect_attempt_total 10511
telemt_upstream_connect_success_total 10459
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 10511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8223
telemt_me_reconnect_success_total 8172
telemt_me_reader_eof_total 8660
telemt_me_idle_close_by_peer_total 8660
telemt_me_route_drop_no_conn_total 83840
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262449
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 964
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 300
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8241
telemt_me_writer_restored_same_endpoint_total 8164
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 262723
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 3794038955 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 98317175612 (91.57 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 39246.0 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576284
telemt_connections_bad_total 18987
telemt_handshake_timeouts_total 53625
telemt_upstream_connect_attempt_total 8714
telemt_upstream_connect_success_total 8676
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 6703
telemt_me_reader_eof_total 7097
telemt_me_idle_close_by_peer_total 7097
telemt_me_route_drop_no_conn_total 162974
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458820
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 949
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 588
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6785
telemt_me_writer_restored_same_endpoint_total 6684
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 458352
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 6809523216 (6.34 GB)
telemt_user_octets_to_client{user="hello"} 187142235728 (174.29 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 39245.9 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355487
telemt_connections_bad_total 51514
telemt_handshake_timeouts_total 23517
telemt_upstream_connect_attempt_total 12516
telemt_upstream_connect_success_total 12220
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 12516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 25379
telemt_me_reconnect_success_total 10254
telemt_me_reader_eof_total 11037
telemt_me_idle_close_by_peer_total 11037
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 94669
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264544
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10815
telemt_me_refill_failed_total 472
telemt_me_writer_restored_same_endpoint_total 10224
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 264547
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 2496846028 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 85770758188 (79.88 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 39246.8 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327415
telemt_connections_bad_total 3831
telemt_handshake_timeouts_total 3643
telemt_upstream_connect_attempt_total 8761
telemt_upstream_connect_success_total 8723
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6763
telemt_me_reader_eof_total 7194
telemt_me_idle_close_by_peer_total 7194
telemt_me_route_drop_no_conn_total 90025
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278009
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1106
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6831
telemt_me_writer_restored_same_endpoint_total 6755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 278014
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 3201233136 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 105298213488 (98.07 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 122
```