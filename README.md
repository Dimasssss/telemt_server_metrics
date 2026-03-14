# Server Metrics 2026-03-14 23:07:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 3184.7 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50388
telemt_connections_bad_total 431
telemt_handshake_timeouts_total 230
telemt_upstream_connect_attempt_total 690
telemt_upstream_connect_success_total 688
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 494
telemt_me_reader_eof_total 497
telemt_me_idle_close_by_peer_total 497
telemt_me_route_drop_no_conn_total 15593
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46314
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 46308
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 691620296 (659.58 MB)
telemt_user_octets_to_client{user="hello"} 17994600616 (16.76 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 3185.3 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21422
telemt_connections_bad_total 3325
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 1263
telemt_upstream_connect_success_total 1253
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 756
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 4270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15647
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 706
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 15943
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1204263543 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 3838345792 (3.57 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 3185.4 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32545
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 1841
telemt_upstream_connect_attempt_total 648
telemt_upstream_connect_success_total 642
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 446
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 7729
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29716
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 57
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 29665
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 500925960 (477.72 MB)
telemt_user_octets_to_client{user="hello"} 9184011948 (8.55 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 3185.3 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21846
telemt_connections_bad_total 2743
telemt_handshake_timeouts_total 742
telemt_upstream_connect_attempt_total 968
telemt_upstream_connect_success_total 926
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 725
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 4743
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18019
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 18021
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 146907172 (140.10 MB)
telemt_user_octets_to_client{user="hello"} 4723722896 (4.40 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 3186.1 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17885
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 501
telemt_upstream_connect_attempt_total 585
telemt_upstream_connect_success_total 580
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 388
telemt_me_reconnect_success_total 384
telemt_me_reader_eof_total 382
telemt_me_idle_close_by_peer_total 382
telemt_me_route_drop_no_conn_total 3958
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16925
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 16925
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 135258024 (128.99 MB)
telemt_user_octets_to_client{user="hello"} 10638144024 (9.91 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 42
```