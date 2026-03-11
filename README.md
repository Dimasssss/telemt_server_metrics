# Server Metrics 2026-03-11 22:25:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 2446.5 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27839
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 457
telemt_upstream_connect_success_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 304
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 293
telemt_me_idle_close_by_peer_total 293
telemt_me_route_drop_no_conn_total 8789
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25400
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 66
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 306
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 25394
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 170754860 (162.84 MB)
telemt_user_octets_to_client{user="hello"} 7607888772 (7.09 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2447.1 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9918
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 78
telemt_upstream_connect_attempt_total 716
telemt_upstream_connect_success_total 716
telemt_upstream_connect_attempts_per_request{bucket="1"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 557
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 2399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9420
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
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_user_connections_total{user="hello"} 9418
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 124481500 (118.71 MB)
telemt_user_octets_to_client{user="hello"} 5086124488 (4.74 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 2446.9 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20472
telemt_connections_bad_total 271
telemt_handshake_timeouts_total 2409
telemt_upstream_connect_attempt_total 1289
telemt_upstream_connect_success_total 1289
telemt_upstream_connect_attempts_per_request{bucket="1"} 1289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 809
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 680
telemt_me_idle_close_by_peer_total 680
telemt_me_route_drop_no_conn_total 3995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16815
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 685
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 17169
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 142622612 (136.02 MB)
telemt_user_octets_to_client{user="hello"} 6306358029 (5.87 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 2447.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13881
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 299
telemt_upstream_connect_attempt_total 792
telemt_upstream_connect_success_total 786
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 270
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 628
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 3672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13365
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
telemt_me_writer_removed_unexpected_total 617
telemt_me_writer_restored_same_endpoint_total 602
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_user_connections_total{user="hello"} 13368
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 90668788 (86.47 MB)
telemt_user_octets_to_client{user="hello"} 4674189356 (4.35 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2447.0 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16271
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 733
telemt_upstream_connect_success_total 724
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 568
telemt_me_reconnect_success_total 561
telemt_me_reader_eof_total 529
telemt_me_idle_close_by_peer_total 529
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 3878
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15350
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
telemt_me_writer_removed_unexpected_total 552
telemt_me_writer_restored_same_endpoint_total 558
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 15346
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 115881344 (110.51 MB)
telemt_user_octets_to_client{user="hello"} 4989748880 (4.65 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 37
```