# Server Metrics 2026-03-14 21:40:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 30193.2 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091027
telemt_connections_bad_total 42775
telemt_handshake_timeouts_total 14845
telemt_upstream_connect_attempt_total 5510
telemt_upstream_connect_success_total 5487
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 4746
telemt_me_reconnect_success_total 3937
telemt_me_reader_eof_total 4155
telemt_me_idle_close_by_peer_total 4155
telemt_me_route_drop_no_conn_total 416175
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972635
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3230
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2286
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1218
telemt_desync_frames_bucket_total{bucket="gt_10"} 1248
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4025
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3928
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 972604
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 17498630152 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 328994723380 (306.40 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 30198.4 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430910
telemt_connections_bad_total 33166
telemt_handshake_timeouts_total 13290
telemt_upstream_connect_attempt_total 6469
telemt_upstream_connect_success_total 6407
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 5657
telemt_me_reconnect_success_total 4856
telemt_me_reader_eof_total 5086
telemt_me_idle_close_by_peer_total 5086
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 125759
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360578
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1322
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4981
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4833
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 360522
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 5683840832 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 126845091664 (118.13 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 30061.4 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935879
telemt_connections_bad_total 3956
telemt_handshake_timeouts_total 235070
telemt_upstream_connect_attempt_total 5851
telemt_upstream_connect_success_total 5833
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 8210
telemt_me_reconnect_success_total 4296
telemt_me_reader_eof_total 4604
telemt_me_idle_close_by_peer_total 4604
telemt_me_route_drop_no_conn_total 208105
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597973
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2233
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4467
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4263
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 597795
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 9162510052 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 222909199376 (207.60 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 29915.8 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495844
telemt_connections_bad_total 101839
telemt_handshake_timeouts_total 55671
telemt_upstream_connect_attempt_total 6875
telemt_upstream_connect_success_total 6873
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 6268
telemt_me_reconnect_success_total 5343
telemt_me_reader_eof_total 5616
telemt_me_idle_close_by_peer_total 5616
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 115375
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330077
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5434
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5331
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 329991
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 4588110968 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 101317434452 (94.36 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 30211.3 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415392
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4088
telemt_upstream_connect_attempt_total 6400
telemt_upstream_connect_success_total 6275
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 5423
telemt_me_reconnect_success_total 4744
telemt_me_reader_eof_total 5015
telemt_me_idle_close_by_peer_total 5015
telemt_me_route_drop_no_conn_total 130203
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1129
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4849
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4726
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 385782
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 6056627132 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 158216231676 (147.35 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 42
```