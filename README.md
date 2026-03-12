# Server Metrics 2026-03-12 06:50:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3126.4 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89753
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 878
telemt_upstream_connect_attempt_total 667
telemt_upstream_connect_success_total 662
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 463
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 450
telemt_me_idle_close_by_peer_total 450
telemt_me_route_drop_no_conn_total 28617
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85833
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 85785
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 1729527176 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 27494877660 (25.61 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32747.1 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142144
telemt_connections_bad_total 1901
telemt_handshake_timeouts_total 5573
telemt_upstream_connect_attempt_total 8604
telemt_upstream_connect_success_total 8599
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 6796
telemt_me_reconnect_success_total 6759
telemt_me_reader_eof_total 7191
telemt_me_idle_close_by_peer_total 7191
telemt_me_route_drop_no_conn_total 41899
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6815
telemt_me_writer_restored_same_endpoint_total 6750
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 125656
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 1910033199 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 53943950906 (50.24 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 32746.7 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481533
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 35674
telemt_upstream_connect_attempt_total 8878
telemt_upstream_connect_success_total 8876
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 6928
telemt_me_reconnect_success_total 6863
telemt_me_reader_eof_total 7194
telemt_me_idle_close_by_peer_total 7194
telemt_me_route_drop_no_conn_total 78870
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236098
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1031
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6846
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6822
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 236396
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 2528389360 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 82978339517 (77.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 32747.2 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211373
telemt_connections_bad_total 1738
telemt_handshake_timeouts_total 13445
telemt_upstream_connect_attempt_total 9381
telemt_upstream_connect_success_total 9341
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 7714
telemt_me_reconnect_success_total 7686
telemt_me_reader_eof_total 8166
telemt_me_idle_close_by_peer_total 8166
telemt_me_route_drop_no_conn_total 67403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171014
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7730
telemt_me_writer_restored_same_endpoint_total 7665
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 170879
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 1940411392 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 53454448528 (49.78 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32747.1 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223725
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 1406
telemt_upstream_connect_attempt_total 11129
telemt_upstream_connect_success_total 11000
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 11129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 10845
telemt_me_reconnect_success_total 9334
telemt_me_reader_eof_total 9725
telemt_me_idle_close_by_peer_total 9725
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 68613
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211984
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 849
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9467
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9315
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 211939
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 1871479012 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 48797518492 (45.45 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 81
```