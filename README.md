# Server Metrics 2026-03-15 13:59:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 56716.8 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1725515
telemt_connections_bad_total 97120
telemt_handshake_timeouts_total 17852
telemt_upstream_connect_attempt_total 11235
telemt_upstream_connect_success_total 11186
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13244
telemt_me_reconnect_success_total 8356
telemt_me_reader_eof_total 8956
telemt_me_idle_close_by_peer_total 8956
telemt_me_route_drop_no_conn_total 588488
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1455753
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5404
telemt_desync_full_logged_total 1506
telemt_desync_suppressed_total 3898
telemt_desync_frames_bucket_total{bucket="1_2"} 1388
telemt_desync_frames_bucket_total{bucket="3_10"} 2108
telemt_desync_frames_bucket_total{bucket="gt_10"} 1908
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8642
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8345
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 1455389
telemt_user_connections_current{user="hello"} 2151
telemt_user_octets_from_client{user="hello"} 20817235440 (19.39 GB)
telemt_user_octets_to_client{user="hello"} 574571848764 (535.11 GB)
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 315
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 56717.8 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697952
telemt_connections_bad_total 37489
telemt_handshake_timeouts_total 54067
telemt_upstream_connect_attempt_total 14523
telemt_upstream_connect_success_total 14453
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11374
telemt_me_reconnect_success_total 11287
telemt_me_reader_eof_total 11926
telemt_me_idle_close_by_peer_total 11926
telemt_me_route_drop_no_conn_total 173463
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524448
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1292
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11425
telemt_me_writer_restored_same_endpoint_total 11275
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 524704
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 7397028835 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 198487542136 (184.86 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 56717.7 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1487403
telemt_connections_bad_total 44337
telemt_handshake_timeouts_total 154746
telemt_upstream_connect_attempt_total 12481
telemt_upstream_connect_success_total 12424
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 12481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10831
telemt_me_reconnect_success_total 9579
telemt_me_reader_eof_total 10157
telemt_me_idle_close_by_peer_total 10157
telemt_me_route_drop_no_conn_total 413166
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928697
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2358
telemt_desync_full_logged_total 868
telemt_desync_suppressed_total 1490
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 904
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9744
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9560
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 924795
telemt_user_connections_current{user="hello"} 1274
telemt_user_octets_from_client{user="hello"} 13345772168 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 335019915140 (312.01 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 56717.6 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712081
telemt_connections_bad_total 70686
telemt_handshake_timeouts_total 38123
telemt_upstream_connect_attempt_total 108670
telemt_upstream_connect_success_total 108218
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 108670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 48128
telemt_me_reconnect_success_total 11791
telemt_me_reader_eof_total 13258
telemt_me_idle_close_by_peer_total 13258
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 169645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443301
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1167
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13037
telemt_me_refill_failed_total 1136
telemt_me_writer_restored_same_endpoint_total 11759
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1246
telemt_user_connections_total{user="hello"} 536776
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 9884520596 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 183692928457 (171.08 GB)
telemt_user_msgs_from_client{user="hello"} 1813976
telemt_user_msgs_to_client{user="hello"} 6728647
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 56718.6 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740516
telemt_connections_bad_total 9140
telemt_handshake_timeouts_total 15446
telemt_upstream_connect_attempt_total 12439
telemt_upstream_connect_success_total 12371
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13218
telemt_me_reconnect_success_total 9545
telemt_me_reader_eof_total 10219
telemt_me_idle_close_by_peer_total 10219
telemt_me_route_drop_no_conn_total 183607
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600616
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 664
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 690
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9773
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9537
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 600656
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 7501258580 (6.99 GB)
telemt_user_octets_to_client{user="hello"} 225885258904 (210.37 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 110
```