# Server Metrics 2026-03-15 11:06:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 46296.8 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1174736
telemt_connections_bad_total 71108
telemt_handshake_timeouts_total 9789
telemt_upstream_connect_attempt_total 9280
telemt_upstream_connect_success_total 9241
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9419
telemt_me_reconnect_success_total 6913
telemt_me_reader_eof_total 7377
telemt_me_idle_close_by_peer_total 7377
telemt_me_route_drop_no_conn_total 393081
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993120
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3809
telemt_desync_full_logged_total 1069
telemt_desync_suppressed_total 2740
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1380
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7091
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 6902
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 993130
telemt_user_connections_current{user="hello"} 2199
telemt_user_octets_from_client{user="hello"} 14026040400 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 398248079524 (370.90 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 46297.5 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462901
telemt_connections_bad_total 24964
telemt_handshake_timeouts_total 20382
telemt_upstream_connect_attempt_total 12242
telemt_upstream_connect_success_total 12178
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9589
telemt_me_reconnect_success_total 9527
telemt_me_reader_eof_total 10079
telemt_me_idle_close_by_peer_total 10079
telemt_me_route_drop_no_conn_total 118324
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365273
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1282
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9626
telemt_me_writer_restored_same_endpoint_total 9515
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 365553
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 5340493695 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 139732273388 (130.14 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 46297.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899091
telemt_connections_bad_total 29865
telemt_handshake_timeouts_total 87799
telemt_upstream_connect_attempt_total 10204
telemt_upstream_connect_success_total 10159
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 10204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7875
telemt_me_reconnect_success_total 7823
telemt_me_reader_eof_total 8285
telemt_me_idle_close_by_peer_total 8285
telemt_me_route_drop_no_conn_total 242708
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641177
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1555
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7925
telemt_me_writer_restored_same_endpoint_total 7804
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 640531
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 9656340008 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 252633962328 (235.28 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 46297.3 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476134
telemt_connections_bad_total 58710
telemt_handshake_timeouts_total 26308
telemt_upstream_connect_attempt_total 13879
telemt_upstream_connect_success_total 13526
telemt_upstream_connect_fail_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 13879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 353
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 32646
telemt_me_reconnect_success_total 11193
telemt_me_reader_eof_total 12193
telemt_me_idle_close_by_peer_total 12193
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 133663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357656
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 836
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11966
telemt_me_refill_failed_total 670
telemt_me_writer_restored_same_endpoint_total 11161
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 773
telemt_user_connections_total{user="hello"} 357561
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 4230213524 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 111648943092 (103.98 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 46298.3 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494582
telemt_connections_bad_total 6227
telemt_handshake_timeouts_total 9876
telemt_upstream_connect_attempt_total 10316
telemt_upstream_connect_success_total 10265
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 7985
telemt_me_reconnect_success_total 7943
telemt_me_reader_eof_total 8432
telemt_me_idle_close_by_peer_total 8432
telemt_me_route_drop_no_conn_total 127670
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407176
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1580
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8035
telemt_me_writer_restored_same_endpoint_total 7935
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 407198
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 5138988988 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 152462272204 (141.99 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 113
```