# Server Metrics 2026-03-12 05:08:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26623.4 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274040
telemt_connections_bad_total 1396
telemt_handshake_timeouts_total 4368
telemt_upstream_connect_attempt_total 5998
telemt_upstream_connect_success_total 5998
telemt_upstream_connect_attempts_per_request{bucket="1"} 5998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4677
telemt_me_reconnect_success_total 4659
telemt_me_reader_eof_total 4926
telemt_me_idle_close_by_peer_total 4926
telemt_me_route_drop_no_conn_total 98039
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261134
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 561
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4707
telemt_me_writer_restored_same_endpoint_total 4643
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 260879
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 2534999156 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 80086217420 (74.59 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26624.0 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90472
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1709
telemt_upstream_connect_attempt_total 7307
telemt_upstream_connect_success_total 7304
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 5801
telemt_me_reconnect_success_total 5768
telemt_me_reader_eof_total 6132
telemt_me_idle_close_by_peer_total 6132
telemt_me_route_drop_no_conn_total 26970
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81929
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5813
telemt_me_writer_restored_same_endpoint_total 5759
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 82117
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 1316566091 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 31685972102 (29.51 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26623.9 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382758
telemt_connections_bad_total 2067
telemt_handshake_timeouts_total 25166
telemt_upstream_connect_attempt_total 7597
telemt_upstream_connect_success_total 7595
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 5948
telemt_me_reconnect_success_total 5886
telemt_me_reader_eof_total 6155
telemt_me_idle_close_by_peer_total 6155
telemt_me_route_drop_no_conn_total 50184
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153438
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5857
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5845
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 153753
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 1495348768 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 47114611129 (43.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26624.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131566
telemt_connections_bad_total 1687
telemt_handshake_timeouts_total 8726
telemt_upstream_connect_attempt_total 7836
telemt_upstream_connect_success_total 7801
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 6475
telemt_me_reconnect_success_total 6453
telemt_me_reader_eof_total 6852
telemt_me_idle_close_by_peer_total 6852
telemt_me_route_drop_no_conn_total 44314
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6493
telemt_me_writer_restored_same_endpoint_total 6432
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 119390
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 990548544 (944.66 MB)
telemt_user_octets_to_client{user="hello"} 34799255872 (32.41 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26623.9 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152764
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 896
telemt_upstream_connect_attempt_total 9771
telemt_upstream_connect_success_total 9662
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 9808
telemt_me_reconnect_success_total 8303
telemt_me_reader_eof_total 8628
telemt_me_idle_close_by_peer_total 8628
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 43557
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146022
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 525
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8418
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8284
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 146005
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 1069579312 (1020.03 MB)
telemt_user_octets_to_client{user="hello"} 32449758228 (30.22 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 63
```