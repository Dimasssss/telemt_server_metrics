# Server Metrics 2026-03-14 14:35:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 4691.2 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189376
telemt_connections_bad_total 4027
telemt_handshake_timeouts_total 2657
telemt_upstream_connect_attempt_total 944
telemt_upstream_connect_success_total 938
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1416
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 73349
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174353
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 344
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 668
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 174351
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 2978754540 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 48922154060 (45.56 GB)
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 4696.5 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74572
telemt_connections_bad_total 5363
telemt_handshake_timeouts_total 2783
telemt_upstream_connect_attempt_total 1029
telemt_upstream_connect_success_total 1023
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 737
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 23735
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60628
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 60587
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 827887568 (789.54 MB)
telemt_user_octets_to_client{user="hello"} 29624915420 (27.59 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 4559.6 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130582
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 17498
telemt_upstream_connect_attempt_total 936
telemt_upstream_connect_success_total 932
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 666
telemt_me_reconnect_success_total 658
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 38368
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105871
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_restored_same_endpoint_total 625
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 105836
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 1514119152 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 30029504136 (27.97 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 4413.9 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71494
telemt_connections_bad_total 19610
telemt_handshake_timeouts_total 10630
telemt_upstream_connect_attempt_total 1214
telemt_upstream_connect_success_total 1214
telemt_upstream_connect_attempts_per_request{bucket="1"} 1214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 970
telemt_me_reconnect_success_total 964
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 15904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40456
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 962
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 40424
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 882884864 (841.98 MB)
telemt_user_octets_to_client{user="hello"} 11222074328 (10.45 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 4709.5 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75038
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 1109
telemt_upstream_connect_success_total 1086
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1441
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 818
telemt_me_idle_close_by_peer_total 818
telemt_me_route_drop_no_conn_total 25939
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68864
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 829
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 68865
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 1021091468 (973.79 MB)
telemt_user_octets_to_client{user="hello"} 23522389908 (21.91 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 120
```