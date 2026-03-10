# Server Metrics 2026-03-10 15:30:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3829.3 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140550
telemt_connections_bad_total 603
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 878
telemt_upstream_connect_success_total 874
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 61599
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134829
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_me_writer_removed_unexpected_total 693
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 615
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 134785
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 1779842584 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 36716776328 (34.20 GB)
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 3886.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57925
telemt_connections_bad_total 1440
telemt_handshake_timeouts_total 6380
telemt_upstream_connect_attempt_total 834
telemt_upstream_connect_success_total 828
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 583
telemt_me_reconnect_success_total 579
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 15019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46814
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 577
telemt_me_writer_restored_same_endpoint_total 558
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 46801
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 596257908 (568.64 MB)
telemt_user_octets_to_client{user="hello"} 14431103980 (13.44 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 3885.9 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99190
telemt_connections_bad_total 304
telemt_handshake_timeouts_total 3951
telemt_upstream_connect_attempt_total 2057
telemt_upstream_connect_success_total 2018
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 756
telemt_me_reconnect_success_total 736
telemt_me_reader_eof_total 747
telemt_me_idle_close_by_peer_total 747
telemt_me_route_drop_no_conn_total 32353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83327
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 181
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 748
telemt_me_writer_restored_same_endpoint_total 725
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 84327
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 855567509 (815.93 MB)
telemt_user_octets_to_client{user="hello"} 24511614377 (22.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 3886.4 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65143
telemt_connections_bad_total 3786
telemt_handshake_timeouts_total 6389
telemt_upstream_connect_attempt_total 784
telemt_upstream_connect_success_total 784
telemt_upstream_connect_attempts_per_request{bucket="1"} 784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 21371
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51887
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 536
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 51839
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 704704620 (672.06 MB)
telemt_user_octets_to_client{user="hello"} 12554666748 (11.69 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3886.1 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73414
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 551
telemt_upstream_connect_attempt_total 1264
telemt_upstream_connect_success_total 1259
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1012
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 23576
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67771
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 403
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1005
telemt_me_writer_restored_same_endpoint_total 1005
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 67739
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 1284792284 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 17152134660 (15.97 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 122
```