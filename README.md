# Server Metrics 2026-03-14 14:25:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 4078.2 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165176
telemt_connections_bad_total 3122
telemt_handshake_timeouts_total 2341
telemt_upstream_connect_attempt_total 823
telemt_upstream_connect_success_total 818
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1341
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 62610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152478
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 594
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 152471
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 2411595492 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 41488617316 (38.64 GB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 4083.6 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65121
telemt_connections_bad_total 4205
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 888
telemt_upstream_connect_success_total 883
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 640
telemt_me_reconnect_success_total 629
telemt_me_reader_eof_total 621
telemt_me_idle_close_by_peer_total 621
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 20896
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52845
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 637
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 52805
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 754242180 (719.30 MB)
telemt_user_octets_to_client{user="hello"} 25882772588 (24.11 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 3946.5 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111586
telemt_connections_bad_total 360
telemt_handshake_timeouts_total 14489
telemt_upstream_connect_attempt_total 823
telemt_upstream_connect_success_total 819
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 574
telemt_me_reconnect_success_total 566
telemt_me_reader_eof_total 547
telemt_me_idle_close_by_peer_total 547
telemt_me_route_drop_no_conn_total 32705
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90330
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 170
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 557
telemt_me_writer_restored_same_endpoint_total 533
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 90298
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 1253838220 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 25153683668 (23.43 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 3800.8 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60565
telemt_connections_bad_total 17541
telemt_handshake_timeouts_total 9503
telemt_upstream_connect_attempt_total 1141
telemt_upstream_connect_success_total 1141
telemt_upstream_connect_attempts_per_request{bucket="1"} 1141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 897
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 895
telemt_me_route_drop_no_conn_total 13220
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32875
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 53
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 886
telemt_me_writer_restored_same_endpoint_total 890
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 32843
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 814900496 (777.15 MB)
telemt_user_octets_to_client{user="hello"} 9031942848 (8.41 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 4096.4 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64868
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 970
telemt_upstream_connect_success_total 952
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 703
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 22533
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 737
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 59592
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 880165620 (839.39 MB)
telemt_user_octets_to_client{user="hello"} 21095980460 (19.65 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 106
```