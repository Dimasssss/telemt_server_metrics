# Server Metrics 2026-03-14 22:01:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 31421.1 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113230
telemt_connections_bad_total 42895
telemt_handshake_timeouts_total 14950
telemt_upstream_connect_attempt_total 5698
telemt_upstream_connect_success_total 5675
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 4891
telemt_me_reconnect_success_total 4082
telemt_me_reader_eof_total 4310
telemt_me_idle_close_by_peer_total 4310
telemt_me_route_drop_no_conn_total 424249
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993350
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3258
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2299
telemt_desync_frames_bucket_total{bucket="1_2"} 766
telemt_desync_frames_bucket_total{bucket="3_10"} 1237
telemt_desync_frames_bucket_total{bucket="gt_10"} 1255
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4173
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 4073
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 993318
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 21059006688 (19.61 GB)
telemt_user_octets_to_client{user="hello"} 334111691708 (311.17 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 31426.3 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440617
telemt_connections_bad_total 34752
telemt_handshake_timeouts_total 13573
telemt_upstream_connect_attempt_total 6696
telemt_upstream_connect_success_total 6631
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 6696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 5839
telemt_me_reconnect_success_total 5035
telemt_me_reader_eof_total 5278
telemt_me_idle_close_by_peer_total 5278
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 128434
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368178
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5165
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 5012
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 368122
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 5870776680 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 128898566376 (120.05 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 31289.2 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964942
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 249794
telemt_upstream_connect_attempt_total 6113
telemt_upstream_connect_success_total 6094
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 6113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 8428
telemt_me_reconnect_success_total 4513
telemt_me_reader_eof_total 4833
telemt_me_idle_close_by_peer_total 4833
telemt_me_route_drop_no_conn_total 211674
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610788
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2246
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4686
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4480
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 610610
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 9719088996 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 227120052472 (211.52 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 31143.8 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505882
telemt_connections_bad_total 102852
telemt_handshake_timeouts_total 56511
telemt_upstream_connect_attempt_total 7130
telemt_upstream_connect_success_total 7128
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 6480
telemt_me_reconnect_success_total 5555
telemt_me_reader_eof_total 5842
telemt_me_idle_close_by_peer_total 5842
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 118637
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338131
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 743
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5649
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5542
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 338045
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 4637079280 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 104761979308 (97.57 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 31439.0 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424863
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4184
telemt_upstream_connect_attempt_total 6611
telemt_upstream_connect_success_total 6483
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 5588
telemt_me_reconnect_success_total 4909
telemt_me_reader_eof_total 5187
telemt_me_idle_close_by_peer_total 5187
telemt_me_route_drop_no_conn_total 132924
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394667
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1197
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5014
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4891
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 394632
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 6403174028 (5.96 GB)
telemt_user_octets_to_client{user="hello"} 164554698128 (153.25 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 50
```