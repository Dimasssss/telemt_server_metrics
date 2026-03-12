# Server Metrics 2026-03-12 23:51:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64362.9 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1969066
telemt_connections_bad_total 26091
telemt_handshake_timeouts_total 21304
telemt_upstream_connect_attempt_total 12774
telemt_upstream_connect_success_total 12702
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 12774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 18326
telemt_me_reconnect_success_total 9468
telemt_me_reader_eof_total 10221
telemt_me_idle_close_by_peer_total 10220
telemt_me_route_drop_no_conn_total 766017
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1830603
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8601
telemt_desync_full_logged_total 2245
telemt_desync_suppressed_total 6356
telemt_desync_frames_bucket_total{bucket="1_2"} 2268
telemt_desync_frames_bucket_total{bucket="3_10"} 3097
telemt_desync_frames_bucket_total{bucket="gt_10"} 3236
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9879
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9455
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 1830068
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 27327125716 (25.45 GB)
telemt_user_octets_to_client{user="hello"} 647700585552 (603.22 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93983.4 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813408
telemt_connections_bad_total 11745
telemt_handshake_timeouts_total 31614
telemt_upstream_connect_attempt_total 23846
telemt_upstream_connect_success_total 23817
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3431
telemt_me_reconnect_attempts_total 17572
telemt_me_reconnect_success_total 17475
telemt_me_reader_eof_total 18602
telemt_me_idle_close_by_peer_total 18602
telemt_me_route_drop_no_conn_total 262903
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735797
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3018
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17647
telemt_me_writer_restored_same_endpoint_total 17466
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 737677
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 12146800756 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 283916713179 (264.42 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93983.2 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1693538
telemt_connections_bad_total 8298
telemt_handshake_timeouts_total 113419
telemt_upstream_connect_attempt_total 21871
telemt_upstream_connect_success_total 21865
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1235
telemt_me_reconnect_attempts_total 18067
telemt_me_reconnect_success_total 16813
telemt_me_reader_eof_total 17786
telemt_me_idle_close_by_peer_total 17785
telemt_me_route_drop_no_conn_total 555400
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1325660
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16974
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16772
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 1325265
telemt_user_connections_current{user="hello"} 279
telemt_user_octets_from_client{user="hello"} 19832762100 (18.47 GB)
telemt_user_octets_to_client{user="hello"} 486414706385 (453.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93983.4 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049421
telemt_connections_bad_total 13015
telemt_handshake_timeouts_total 71656
telemt_upstream_connect_attempt_total 33115
telemt_upstream_connect_success_total 30855
telemt_upstream_connect_fail_total 2123
telemt_upstream_connect_attempts_per_request{bucket="1"} 32841
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2122
telemt_me_keepalive_timeout_total 11253
telemt_me_reconnect_attempts_total 28133
telemt_me_reconnect_success_total 20295
telemt_me_reader_eof_total 21976
telemt_me_idle_close_by_peer_total 21969
telemt_me_route_drop_no_conn_total 371124
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907113
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1888
telemt_desync_full_logged_total 623
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20660
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20273
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 912333
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 14337252049 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 362795370522 (337.88 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93983.6 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1166056
telemt_connections_bad_total 12557
telemt_handshake_timeouts_total 9283
telemt_upstream_connect_attempt_total 28507
telemt_upstream_connect_success_total 28152
telemt_upstream_connect_fail_total 355
telemt_upstream_connect_attempts_per_request{bucket="1"} 28507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 355
telemt_me_keepalive_timeout_total 1462
telemt_me_reconnect_attempts_total 34491
telemt_me_reconnect_success_total 23450
telemt_me_reader_eof_total 24677
telemt_me_idle_close_by_peer_total 24677
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 435047
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075235
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4046
telemt_desync_full_logged_total 1419
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1179
telemt_desync_frames_bucket_total{bucket="3_10"} 1348
telemt_desync_frames_bucket_total{bucket="gt_10"} 1519
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 24069
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23405
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 1075092
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 13544108856 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 378383067036 (352.40 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 37
```