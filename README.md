# Server Metrics 2026-03-11 22:30:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2752.6 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30018
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 133
telemt_upstream_connect_attempt_total 510
telemt_upstream_connect_success_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 338
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 9766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27545
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 27539
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 184341048 (175.80 MB)
telemt_user_octets_to_client{user="hello"} 8340389640 (7.77 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2753.0 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10835
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 81
telemt_upstream_connect_attempt_total 834
telemt_upstream_connect_success_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 647
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 2794
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 10300
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 465760776 (444.18 MB)
telemt_user_octets_to_client{user="hello"} 5942408452 (5.53 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2752.8 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22109
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 1392
telemt_upstream_connect_success_total 1392
telemt_upstream_connect_attempts_per_request{bucket="1"} 1392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 895
telemt_me_reconnect_success_total 857
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 4733
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18258
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 772
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 18612
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 153914932 (146.78 MB)
telemt_user_octets_to_client{user="hello"} 7524880369 (7.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2753.2 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15268
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 300
telemt_upstream_connect_attempt_total 917
telemt_upstream_connect_success_total 910
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 740
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 4067
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14721
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_writer_removed_unexpected_total 733
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 14724
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 96843000 (92.36 MB)
telemt_user_octets_to_client{user="hello"} 5789930380 (5.39 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2753.1 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18151
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 823
telemt_upstream_connect_success_total 814
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 651
telemt_me_reconnect_success_total 644
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 4386
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17125
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 23
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_restored_same_endpoint_total 641
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 17121
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 119997596 (114.44 MB)
telemt_user_octets_to_client{user="hello"} 5309604804 (4.94 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 36
```