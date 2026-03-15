# Server Metrics 2026-03-15 09:03:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 38938.7 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823290
telemt_connections_bad_total 34980
telemt_handshake_timeouts_total 6062
telemt_upstream_connect_attempt_total 7920
telemt_upstream_connect_success_total 7887
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5960
telemt_me_reconnect_success_total 5928
telemt_me_reader_eof_total 6276
telemt_me_idle_close_by_peer_total 6276
telemt_me_route_drop_no_conn_total 268994
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699029
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2224
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6010
telemt_me_writer_restored_same_endpoint_total 5917
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 699018
telemt_user_connections_current{user="hello"} 1941
telemt_user_octets_from_client{user="hello"} 9431822624 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 263451072664 (245.36 GB)
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 38939.8 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325434
telemt_connections_bad_total 18570
telemt_handshake_timeouts_total 12933
telemt_upstream_connect_attempt_total 10468
telemt_upstream_connect_success_total 10416
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 10468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8180
telemt_me_reconnect_success_total 8129
telemt_me_reader_eof_total 8615
telemt_me_idle_close_by_peer_total 8615
telemt_me_route_drop_no_conn_total 82122
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257407
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8196
telemt_me_writer_restored_same_endpoint_total 8121
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 257681
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 3746199711 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 97203232404 (90.53 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 38939.7 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562944
telemt_connections_bad_total 18407
telemt_handshake_timeouts_total 50714
telemt_upstream_connect_attempt_total 8654
telemt_upstream_connect_success_total 8616
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6686
telemt_me_reconnect_success_total 6643
telemt_me_reader_eof_total 7037
telemt_me_idle_close_by_peer_total 7037
telemt_me_route_drop_no_conn_total 157060
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450194
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 942
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6725
telemt_me_writer_restored_same_endpoint_total 6624
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 449727
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 6682508244 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 184065396628 (171.42 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 38939.7 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350056
telemt_connections_bad_total 51269
telemt_handshake_timeouts_total 23146
telemt_upstream_connect_attempt_total 12473
telemt_upstream_connect_success_total 12177
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 12473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 25336
telemt_me_reconnect_success_total 10212
telemt_me_reader_eof_total 10991
telemt_me_idle_close_by_peer_total 10991
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 92988
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260519
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 617
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10769
telemt_me_refill_failed_total 472
telemt_me_writer_restored_same_endpoint_total 10182
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 557
telemt_user_connections_total{user="hello"} 260522
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 2437086472 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 84457021604 (78.66 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 38940.6 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318680
telemt_connections_bad_total 3830
telemt_handshake_timeouts_total 3581
telemt_upstream_connect_attempt_total 8686
telemt_upstream_connect_success_total 8648
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 6720
telemt_me_reconnect_success_total 6688
telemt_me_reader_eof_total 7119
telemt_me_idle_close_by_peer_total 7119
telemt_me_route_drop_no_conn_total 87897
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1088
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6756
telemt_me_writer_restored_same_endpoint_total 6680
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 272652
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 3145397084 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 103533662748 (96.42 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 115
```