# Server Metrics 2026-03-13 12:27:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109718.1 (30h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3265566
telemt_connections_bad_total 36553
telemt_handshake_timeouts_total 56779
telemt_upstream_connect_attempt_total 21669
telemt_upstream_connect_success_total 21551
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2083
telemt_me_reconnect_attempts_total 26181
telemt_me_reconnect_success_total 16100
telemt_me_reader_eof_total 17308
telemt_me_idle_close_by_peer_total 17307
telemt_me_route_drop_no_conn_total 1210866
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2992437
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12681
telemt_desync_full_logged_total 3285
telemt_desync_suppressed_total 9396
telemt_desync_frames_bucket_total{bucket="1_2"} 3230
telemt_desync_frames_bucket_total{bucket="3_10"} 4784
telemt_desync_frames_bucket_total{bucket="gt_10"} 4667
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16637
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16087
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 2992351
telemt_user_connections_current{user="hello"} 1761
telemt_user_octets_from_client{user="hello"} 41447391608 (38.60 GB)
telemt_user_octets_to_client{user="hello"} 965628404180 (899.31 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9381.8 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127406
telemt_connections_bad_total 7194
telemt_handshake_timeouts_total 2917
telemt_upstream_connect_attempt_total 2365
telemt_upstream_connect_success_total 2292
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 2365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2989
telemt_me_reconnect_success_total 1763
telemt_me_reader_eof_total 1847
telemt_me_idle_close_by_peer_total 1847
telemt_me_route_drop_no_conn_total 45024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1812
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1756
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 114129
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 1115470020 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 30118635872 (28.05 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 139338.6 (38h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2480171
telemt_connections_bad_total 26142
telemt_handshake_timeouts_total 163849
telemt_upstream_connect_attempt_total 31738
telemt_upstream_connect_success_total 31728
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3161
telemt_me_reconnect_attempts_total 26999
telemt_me_reconnect_success_total 24454
telemt_me_reader_eof_total 25921
telemt_me_idle_close_by_peer_total 25920
telemt_me_route_drop_no_conn_total 827347
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2012322
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6738
telemt_desync_full_logged_total 2168
telemt_desync_suppressed_total 4570
telemt_desync_frames_bucket_total{bucket="1_2"} 1065
telemt_desync_frames_bucket_total{bucket="3_10"} 2467
telemt_desync_frames_bucket_total{bucket="gt_10"} 3206
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 24736
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24413
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 2011735
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 34134621144 (31.79 GB)
telemt_user_octets_to_client{user="hello"} 722609532365 (672.98 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 139339.0 (38h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581603
telemt_connections_bad_total 17866
telemt_handshake_timeouts_total 110973
telemt_upstream_connect_attempt_total 45055
telemt_upstream_connect_success_total 42736
telemt_upstream_connect_fail_total 2182
telemt_upstream_connect_attempts_per_request{bucket="1"} 44781
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2181
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11824
telemt_me_reconnect_attempts_total 38914
telemt_me_reconnect_success_total 29950
telemt_me_reader_eof_total 32207
telemt_me_idle_close_by_peer_total 32200
telemt_me_route_drop_no_conn_total 561307
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1317859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2518
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1683
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 855
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 30449
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29926
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 1322584
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 19688432133 (18.34 GB)
telemt_user_octets_to_client{user="hello"} 516028483374 (480.59 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8774.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127358
telemt_connections_bad_total 731
telemt_handshake_timeouts_total 1023
telemt_upstream_connect_attempt_total 1735
telemt_upstream_connect_success_total 1669
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 1735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 9263
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1422
telemt_me_idle_close_by_peer_total 1422
telemt_me_route_drop_no_conn_total 49821
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121381
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1438
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1189
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 121376
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 1369113980 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 40241329368 (37.48 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 83
```