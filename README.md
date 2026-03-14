# Server Metrics 2026-03-14 18:21:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 18222.9 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736047
telemt_connections_bad_total 39079
telemt_handshake_timeouts_total 9904
telemt_upstream_connect_attempt_total 3582
telemt_upstream_connect_success_total 3567
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 3387
telemt_me_reconnect_success_total 2586
telemt_me_reader_eof_total 2713
telemt_me_idle_close_by_peer_total 2713
telemt_me_route_drop_no_conn_total 282531
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653991
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2290
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1634
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 888
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2650
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 653925
telemt_user_connections_current{user="hello"} 1872
telemt_user_octets_from_client{user="hello"} 11470331388 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 213856186888 (199.17 GB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 18228.3 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288470
telemt_connections_bad_total 22774
telemt_handshake_timeouts_total 8850
telemt_upstream_connect_attempt_total 3786
telemt_upstream_connect_success_total 3738
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 3548
telemt_me_reconnect_success_total 2757
telemt_me_reader_eof_total 2890
telemt_me_idle_close_by_peer_total 2890
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 90077
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238757
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 948
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 651
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2842
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2742
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 238698
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 3326674128 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 88158500876 (82.10 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 18091.3 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614781
telemt_connections_bad_total 2171
telemt_handshake_timeouts_total 129262
telemt_upstream_connect_attempt_total 3599
telemt_upstream_connect_success_total 3586
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6531
telemt_me_reconnect_success_total 2626
telemt_me_reader_eof_total 2823
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 148166
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410961
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1341
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 846
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2773
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2593
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 410850
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 5978386992 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 146287160136 (136.24 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 17945.6 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332522
telemt_connections_bad_total 78503
telemt_handshake_timeouts_total 41954
telemt_upstream_connect_attempt_total 4271
telemt_upstream_connect_success_total 4270
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 4270
telemt_me_reconnect_success_total 3355
telemt_me_reader_eof_total 3503
telemt_me_idle_close_by_peer_total 3503
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 73533
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206944
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 8
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 423
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3416
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3347
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 206895
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 3073081000 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 64987033944 (60.52 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 18241.6 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281049
telemt_connections_bad_total 1109
telemt_handshake_timeouts_total 3320
telemt_upstream_connect_attempt_total 3829
telemt_upstream_connect_success_total 3752
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 3460
telemt_me_reconnect_success_total 2792
telemt_me_reader_eof_total 2945
telemt_me_idle_close_by_peer_total 2945
telemt_me_route_drop_no_conn_total 89151
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259731
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 636
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 386
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2870
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2774
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 259719
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 4038706856 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 111089340544 (103.46 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 87
```