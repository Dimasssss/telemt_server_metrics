# Server Metrics 2026-03-11 05:46:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55135.8 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077676
telemt_connections_bad_total 12938
telemt_handshake_timeouts_total 37763
telemt_upstream_connect_attempt_total 11748
telemt_upstream_connect_success_total 11739
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 20601
telemt_me_reconnect_success_total 8922
telemt_me_reader_eof_total 9713
telemt_me_idle_close_by_peer_total 9713
telemt_me_route_drop_no_conn_total 396792
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966950
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4446
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 3190
telemt_desync_frames_bucket_total{bucket="1_2"} 1227
telemt_desync_frames_bucket_total{bucket="3_10"} 1680
telemt_desync_frames_bucket_total{bucket="gt_10"} 1539
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9369
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8916
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 966655
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 13074592536 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 281452518644 (262.12 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55192.5 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415769
telemt_connections_bad_total 3234
telemt_handshake_timeouts_total 19775
telemt_upstream_connect_attempt_total 20340
telemt_upstream_connect_success_total 17433
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1793
telemt_me_reconnect_attempts_total 12524
telemt_me_reconnect_success_total 11701
telemt_me_reader_eof_total 12367
telemt_me_idle_close_by_peer_total 12365
telemt_me_route_drop_no_conn_total 193590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357121
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1314
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11836
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11680
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 359392
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 3604612250 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 88205439204 (82.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55192.3 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710352
telemt_connections_bad_total 5991
telemt_handshake_timeouts_total 38809
telemt_upstream_connect_attempt_total 14932
telemt_upstream_connect_success_total 14732
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 14932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 575
telemt_me_reconnect_attempts_total 21948
telemt_me_reconnect_success_total 10876
telemt_me_reader_eof_total 11738
telemt_me_idle_close_by_peer_total 11738
telemt_me_route_drop_no_conn_total 239220
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634598
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1797
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1272
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11364
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10865
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 635453
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 7666923369 (7.14 GB)
telemt_user_octets_to_client{user="hello"} 188454213037 (175.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55192.8 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540951
telemt_connections_bad_total 51829
telemt_handshake_timeouts_total 56348
telemt_upstream_connect_attempt_total 15901
telemt_upstream_connect_success_total 15901
telemt_upstream_connect_attempts_per_request{bucket="1"} 15901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 500
telemt_me_reconnect_attempts_total 14163
telemt_me_reconnect_success_total 13120
telemt_me_reader_eof_total 13928
telemt_me_idle_close_by_peer_total 13928
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 159864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418069
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 894
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 13270
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13098
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 417668
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5070386816 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 114878633608 (106.99 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55192.4 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564321
telemt_connections_bad_total 5956
telemt_handshake_timeouts_total 3823
telemt_upstream_connect_attempt_total 15831
telemt_upstream_connect_success_total 15764
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 16723
telemt_me_reconnect_success_total 12940
telemt_me_reader_eof_total 13663
telemt_me_idle_close_by_peer_total 13663
telemt_me_route_drop_no_conn_total 184503
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515580
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2512
telemt_desync_full_logged_total 972
telemt_desync_suppressed_total 1540
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1068
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13221
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12940
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 515198
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 9184658676 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 180333330628 (167.95 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 71
```