# Server Metrics 2026-03-14 20:29:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 25900.3 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990264
telemt_connections_bad_total 41213
telemt_handshake_timeouts_total 14482
telemt_upstream_connect_attempt_total 4719
telemt_upstream_connect_success_total 4698
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4172
telemt_me_reconnect_success_total 3366
telemt_me_reader_eof_total 3547
telemt_me_idle_close_by_peer_total 3547
telemt_me_route_drop_no_conn_total 379461
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879074
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3026
telemt_desync_full_logged_total 857
telemt_desync_suppressed_total 2169
telemt_desync_frames_bucket_total{bucket="1_2"} 720
telemt_desync_frames_bucket_total{bucket="3_10"} 1114
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3447
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3357
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 879026
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 15739814196 (14.66 GB)
telemt_user_octets_to_client{user="hello"} 297627523912 (277.19 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 25905.6 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388943
telemt_connections_bad_total 28785
telemt_handshake_timeouts_total 11695
telemt_upstream_connect_attempt_total 5562
telemt_upstream_connect_success_total 5506
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 5562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 4971
telemt_me_reconnect_success_total 4176
telemt_me_reader_eof_total 4350
telemt_me_idle_close_by_peer_total 4350
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 115607
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325945
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 1172
telemt_desync_frames_bucket_total{bucket="1_2"} 664
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4289
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4153
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 325878
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 4836397880 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 114092433428 (106.26 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 25768.4 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830663
telemt_connections_bad_total 3340
telemt_handshake_timeouts_total 190366
telemt_upstream_connect_attempt_total 4985
telemt_upstream_connect_success_total 4968
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 7561
telemt_me_reconnect_success_total 3650
telemt_me_reader_eof_total 3914
telemt_me_idle_close_by_peer_total 3914
telemt_me_route_drop_no_conn_total 191877
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542256
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2020
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3810
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3617
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 542084
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 8161838436 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 195883104592 (182.43 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 25622.9 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450804
telemt_connections_bad_total 98497
telemt_handshake_timeouts_total 52838
telemt_upstream_connect_attempt_total 5954
telemt_upstream_connect_success_total 5953
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 5563
telemt_me_reconnect_success_total 4642
telemt_me_reader_eof_total 4864
telemt_me_idle_close_by_peer_total 4864
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 103141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291945
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 655
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4724
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4631
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 291862
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 4185012960 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 90754491044 (84.52 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 25918.3 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378617
telemt_connections_bad_total 1364
telemt_handshake_timeouts_total 3897
telemt_upstream_connect_attempt_total 5529
telemt_upstream_connect_success_total 5419
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 5529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 4782
telemt_me_reconnect_success_total 4107
telemt_me_reader_eof_total 4330
telemt_me_idle_close_by_peer_total 4330
telemt_me_route_drop_no_conn_total 120005
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350930
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 894
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4203
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4089
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 350897
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 5684688924 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 149583729644 (139.31 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 78
```