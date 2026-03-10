# Server Metrics 2026-03-10 15:36:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4135.6 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150878
telemt_connections_bad_total 797
telemt_handshake_timeouts_total 699
telemt_upstream_connect_attempt_total 916
telemt_upstream_connect_success_total 912
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 3448
telemt_me_reconnect_success_total 658
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 65490
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144687
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 456
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_me_writer_removed_unexpected_total 730
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 144638
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 1878452548 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 39614307176 (36.89 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4192.2 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61491
telemt_connections_bad_total 1449
telemt_handshake_timeouts_total 6398
telemt_upstream_connect_attempt_total 886
telemt_upstream_connect_success_total 879
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 635
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 626
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 15930
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 287
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_restored_same_endpoint_total 609
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 50174
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 627988908 (598.90 MB)
telemt_user_octets_to_client{user="hello"} 15107038068 (14.07 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4192.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106934
telemt_connections_bad_total 392
telemt_handshake_timeouts_total 4588
telemt_upstream_connect_attempt_total 2094
telemt_upstream_connect_success_total 2055
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 2094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 793
telemt_me_reconnect_success_total 773
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 34844
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 188
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 91060
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 928445601 (885.43 MB)
telemt_user_octets_to_client{user="hello"} 26322695997 (24.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4192.6 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70589
telemt_connections_bad_total 4105
telemt_handshake_timeouts_total 7421
telemt_upstream_connect_attempt_total 843
telemt_upstream_connect_success_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 345
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 602
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 23089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55756
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 171
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 55708
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 742939696 (708.52 MB)
telemt_user_octets_to_client{user="hello"} 13578710232 (12.65 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4192.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78289
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 608
telemt_upstream_connect_attempt_total 1304
telemt_upstream_connect_success_total 1299
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1052
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 30081
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72273
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 426
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1045
telemt_me_writer_restored_same_endpoint_total 1045
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 72231
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 1377384840 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 18649450888 (17.37 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 93
```