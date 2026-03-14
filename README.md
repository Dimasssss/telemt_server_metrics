# Server Metrics 2026-03-14 20:44:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 26820.8 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016131
telemt_connections_bad_total 42326
telemt_handshake_timeouts_total 14608
telemt_upstream_connect_attempt_total 4889
telemt_upstream_connect_success_total 4866
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 4297
telemt_me_reconnect_success_total 3490
telemt_me_reader_eof_total 3681
telemt_me_idle_close_by_peer_total 3681
telemt_me_route_drop_no_conn_total 388466
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902731
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3085
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2207
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1140
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3573
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3481
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 902677
telemt_user_connections_current{user="hello"} 1425
telemt_user_octets_from_client{user="hello"} 16202561208 (15.09 GB)
telemt_user_octets_to_client{user="hello"} 305565907532 (284.58 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 26826.1 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399115
telemt_connections_bad_total 30075
telemt_handshake_timeouts_total 12218
telemt_upstream_connect_attempt_total 5763
telemt_upstream_connect_success_total 5704
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 5763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 5127
telemt_me_reconnect_success_total 4329
telemt_me_reader_eof_total 4523
telemt_me_idle_close_by_peer_total 4523
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 117763
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334004
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1630
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 676
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4446
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4306
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 333942
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 4940154876 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 116952009844 (108.92 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 26688.8 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864563
telemt_connections_bad_total 3373
telemt_handshake_timeouts_total 209887
telemt_upstream_connect_attempt_total 5178
telemt_upstream_connect_success_total 5161
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 7711
telemt_me_reconnect_success_total 3799
telemt_me_reader_eof_total 4074
telemt_me_idle_close_by_peer_total 4074
telemt_me_route_drop_no_conn_total 195611
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554977
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2054
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3963
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3766
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 554805
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 8281634964 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 204028465088 (190.02 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 26543.4 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461826
telemt_connections_bad_total 99207
telemt_handshake_timeouts_total 53662
telemt_upstream_connect_attempt_total 6143
telemt_upstream_connect_success_total 6142
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5709
telemt_me_reconnect_success_total 4787
telemt_me_reader_eof_total 5020
telemt_me_idle_close_by_peer_total 5020
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 106217
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 664
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 432
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4873
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4775
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 300981
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 4261365840 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 93496443984 (87.08 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 26838.5 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387220
telemt_connections_bad_total 1373
telemt_handshake_timeouts_total 3931
telemt_upstream_connect_attempt_total 5699
telemt_upstream_connect_success_total 5588
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 5699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 4908
telemt_me_reconnect_success_total 4233
telemt_me_reader_eof_total 4464
telemt_me_idle_close_by_peer_total 4464
telemt_me_route_drop_no_conn_total 122352
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359129
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4331
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4215
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 359094
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 5815746088 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 151669477640 (141.25 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 60
```