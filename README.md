# Server Metrics 2026-03-14 14:10:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 3159.6 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128595
telemt_connections_bad_total 2220
telemt_handshake_timeouts_total 1754
telemt_upstream_connect_attempt_total 649
telemt_upstream_connect_success_total 645
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1211
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 48602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119518
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 204
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_me_writer_removed_unexpected_total 463
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 119514
telemt_user_connections_current{user="hello"} 1870
telemt_user_octets_from_client{user="hello"} 1919854772 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 29819421136 (27.77 GB)
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 3165.0 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49701
telemt_connections_bad_total 3046
telemt_handshake_timeouts_total 2086
telemt_upstream_connect_attempt_total 702
telemt_upstream_connect_success_total 697
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 501
telemt_me_reconnect_success_total 490
telemt_me_reader_eof_total 476
telemt_me_idle_close_by_peer_total 476
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 16507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41633
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 315
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 492
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 41595
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 630202348 (601.01 MB)
telemt_user_octets_to_client{user="hello"} 20574498700 (19.16 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 3027.8 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85017
telemt_connections_bad_total 238
telemt_handshake_timeouts_total 11106
telemt_upstream_connect_attempt_total 643
telemt_upstream_connect_success_total 639
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 440
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 25178
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68449
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 68422
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 1067018076 (1017.59 MB)
telemt_user_octets_to_client{user="hello"} 19435186028 (18.10 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 2882.2 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45105
telemt_connections_bad_total 14435
telemt_handshake_timeouts_total 8009
telemt_upstream_connect_attempt_total 840
telemt_upstream_connect_success_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 639
telemt_me_reconnect_success_total 633
telemt_me_reader_eof_total 617
telemt_me_idle_close_by_peer_total 617
telemt_me_route_drop_no_conn_total 9480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22221
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 22189
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 700818868 (668.35 MB)
telemt_user_octets_to_client{user="hello"} 6147085180 (5.72 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 3177.7 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50662
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 357
telemt_upstream_connect_attempt_total 775
telemt_upstream_connect_success_total 759
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 1200
telemt_me_reconnect_success_total 553
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 17423
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46357
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 191
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_me_writer_removed_unexpected_total 585
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 46362
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 591787884 (564.37 MB)
telemt_user_octets_to_client{user="hello"} 17332484788 (16.14 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 115
```