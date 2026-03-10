# Server Metrics 2026-03-10 17:53:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12399.8 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415007
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 1961
telemt_upstream_connect_attempt_total 2392
telemt_upstream_connect_success_total 2383
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 10981
telemt_me_reconnect_success_total 1714
telemt_me_reader_eof_total 1980
telemt_me_idle_close_by_peer_total 1980
telemt_me_route_drop_no_conn_total 175660
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393164
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1965
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 754
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2006
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 393089
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 5169512036 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 115053882864 (107.15 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 12456.5 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160892
telemt_connections_bad_total 1698
telemt_handshake_timeouts_total 10689
telemt_upstream_connect_attempt_total 2788
telemt_upstream_connect_success_total 2775
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 2138
telemt_me_reconnect_success_total 2126
telemt_me_reader_eof_total 2208
telemt_me_idle_close_by_peer_total 2208
telemt_me_route_drop_no_conn_total 46884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2139
telemt_me_writer_restored_same_endpoint_total 2105
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 140145
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 1768723800 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 37506969732 (34.93 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 12456.4 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308192
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 31174
telemt_upstream_connect_attempt_total 4095
telemt_upstream_connect_success_total 4029
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 3522
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2446
telemt_me_idle_close_by_peer_total 2446
telemt_me_route_drop_no_conn_total 100394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252959
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 807
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2401
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2317
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 253933
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 3482790241 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 75692821001 (70.49 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 12457.0 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197939
telemt_connections_bad_total 12117
telemt_handshake_timeouts_total 18997
telemt_upstream_connect_attempt_total 3221
telemt_upstream_connect_success_total 3221
telemt_upstream_connect_attempts_per_request{bucket="1"} 3221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1502
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2581
telemt_me_reconnect_success_total 2565
telemt_me_reader_eof_total 2650
telemt_me_idle_close_by_peer_total 2650
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 63948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158609
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 487
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2587
telemt_me_writer_restored_same_endpoint_total 2553
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 158439
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 2605138732 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 44593481724 (41.53 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 12456.6 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210186
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1620
telemt_upstream_connect_attempt_total 3713
telemt_upstream_connect_success_total 3703
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 3052
telemt_me_reconnect_success_total 3033
telemt_me_reader_eof_total 3115
telemt_me_idle_close_by_peer_total 3115
telemt_me_route_drop_no_conn_total 76900
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197765
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1058
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3062
telemt_me_writer_restored_same_endpoint_total 3033
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 197701
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 4416368016 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 57741534968 (53.78 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 84
```