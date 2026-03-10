# Server Metrics 2026-03-10 15:15:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2909.0 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107734
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 583
telemt_upstream_connect_attempt_total 716
telemt_upstream_connect_success_total 712
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1404
telemt_me_reconnect_success_total 503
telemt_me_reader_eof_total 488
telemt_me_idle_close_by_peer_total 488
telemt_me_route_drop_no_conn_total 46684
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103396
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_me_writer_removed_unexpected_total 514
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 103389
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 1488903300 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 29127764860 (27.13 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2965.9 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47176
telemt_connections_bad_total 1292
telemt_handshake_timeouts_total 6178
telemt_upstream_connect_attempt_total 635
telemt_upstream_connect_success_total 630
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 428
telemt_me_reconnect_success_total 425
telemt_me_reader_eof_total 411
telemt_me_idle_close_by_peer_total 411
telemt_me_route_drop_no_conn_total 11116
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 241
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 36915
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 404839844 (386.09 MB)
telemt_user_octets_to_client{user="hello"} 11728563772 (10.92 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2965.7 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75645
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 2216
telemt_upstream_connect_attempt_total 1726
telemt_upstream_connect_success_total 1691
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 1726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 472
telemt_me_reconnect_success_total 452
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 25186
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63163
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 64164
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 699342977 (666.95 MB)
telemt_user_octets_to_client{user="hello"} 19871279681 (18.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2966.2 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50281
telemt_connections_bad_total 2842
telemt_handshake_timeouts_total 4260
telemt_upstream_connect_attempt_total 578
telemt_upstream_connect_success_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 234
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 380
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 16568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40566
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 108
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_restored_same_endpoint_total 367
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 40531
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 562147280 (536.11 MB)
telemt_user_octets_to_client{user="hello"} 9857555132 (9.18 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2965.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57182
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 911
telemt_upstream_connect_success_total 907
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 705
telemt_me_reconnect_success_total 699
telemt_me_reader_eof_total 676
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 19188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52881
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 318
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_me_writer_removed_unexpected_total 698
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 52854
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 1122921188 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 13796203900 (12.85 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 118
```