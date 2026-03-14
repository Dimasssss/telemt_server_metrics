# Server Metrics 2026-03-14 14:15:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 3466.2 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140922
telemt_connections_bad_total 2220
telemt_handshake_timeouts_total 2032
telemt_upstream_connect_attempt_total 684
telemt_upstream_connect_success_total 680
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1246
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 53033
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130915
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_me_writer_removed_unexpected_total 498
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 130908
telemt_user_connections_current{user="hello"} 1850
telemt_user_octets_from_client{user="hello"} 2134342608 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 34106327856 (31.76 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 3471.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53991
telemt_connections_bad_total 3422
telemt_handshake_timeouts_total 2159
telemt_upstream_connect_attempt_total 728
telemt_upstream_connect_success_total 723
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 527
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 502
telemt_me_idle_close_by_peer_total 502
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 17862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45385
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 321
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_restored_same_endpoint_total 505
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 45346
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 686185720 (654.40 MB)
telemt_user_octets_to_client{user="hello"} 22500195252 (20.95 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 3334.4 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94315
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 12712
telemt_upstream_connect_attempt_total 667
telemt_upstream_connect_success_total 663
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 458
telemt_me_reader_eof_total 438
telemt_me_idle_close_by_peer_total 438
telemt_me_route_drop_no_conn_total 27744
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75757
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
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 75725
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 1113216444 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 21104114520 (19.65 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 3188.8 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50941
telemt_connections_bad_total 15441
telemt_handshake_timeouts_total 8923
telemt_upstream_connect_attempt_total 939
telemt_upstream_connect_success_total 939
telemt_upstream_connect_attempts_per_request{bucket="1"} 939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 738
telemt_me_reconnect_success_total 733
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 10968
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26063
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_restored_same_endpoint_total 732
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 26031
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 754577480 (719.62 MB)
telemt_user_octets_to_client{user="hello"} 7584615628 (7.06 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 3484.0 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55459
telemt_connections_bad_total 96
telemt_handshake_timeouts_total 405
telemt_upstream_connect_attempt_total 825
telemt_upstream_connect_success_total 809
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 1250
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 612
telemt_me_route_drop_no_conn_total 19086
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50841
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_me_writer_removed_unexpected_total 635
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 585
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 50845
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 676761024 (645.41 MB)
telemt_user_octets_to_client{user="hello"} 18368846996 (17.11 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 100
```