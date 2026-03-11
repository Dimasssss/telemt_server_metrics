# Server Metrics 2026-03-11 15:32:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90317.1 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2220941
telemt_connections_bad_total 38309
telemt_handshake_timeouts_total 52844
telemt_upstream_connect_attempt_total 18969
telemt_upstream_connect_success_total 18957
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4893
telemt_me_reconnect_attempts_total 32241
telemt_me_reconnect_success_total 14375
telemt_me_reader_eof_total 15606
telemt_me_idle_close_by_peer_total 15606
telemt_me_route_drop_no_conn_total 821974
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031099
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10578
telemt_desync_full_logged_total 2871
telemt_desync_suppressed_total 7707
telemt_desync_frames_bucket_total{bucket="1_2"} 2626
telemt_desync_frames_bucket_total{bucket="3_10"} 4081
telemt_desync_frames_bucket_total{bucket="gt_10"} 3871
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15092
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14369
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2029556
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 27258915212 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 576870711416 (537.25 GB)
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90373.4 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824004
telemt_connections_bad_total 13368
telemt_handshake_timeouts_total 55529
telemt_upstream_connect_attempt_total 28705
telemt_upstream_connect_success_total 25747
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 28705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2553
telemt_me_reconnect_attempts_total 20342
telemt_me_reconnect_success_total 18248
telemt_me_reader_eof_total 19311
telemt_me_idle_close_by_peer_total 19308
telemt_me_route_drop_no_conn_total 323187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2886
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 954
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18514
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18225
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 703338
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 8100399654 (7.54 GB)
telemt_user_octets_to_client{user="hello"} 198695523536 (185.05 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90373.0 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430782
telemt_connections_bad_total 8659
telemt_handshake_timeouts_total 124141
telemt_upstream_connect_attempt_total 23813
telemt_upstream_connect_success_total 23524
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 23813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 37581
telemt_me_reconnect_success_total 17882
telemt_me_reader_eof_total 19301
telemt_me_idle_close_by_peer_total 19301
telemt_me_route_drop_no_conn_total 520499
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3289
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2315
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 1244
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18741
telemt_me_refill_failed_total 611
telemt_me_writer_restored_same_endpoint_total 17871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 1245379
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 15025468385 (13.99 GB)
telemt_user_octets_to_client{user="hello"} 375147618325 (349.38 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90373.4 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1027218
telemt_connections_bad_total 77934
telemt_handshake_timeouts_total 100530
telemt_upstream_connect_attempt_total 24195
telemt_upstream_connect_success_total 24195
telemt_upstream_connect_attempts_per_request{bucket="1"} 24195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1013
telemt_me_reconnect_attempts_total 20751
telemt_me_reconnect_success_total 19676
telemt_me_reader_eof_total 20864
telemt_me_idle_close_by_peer_total 20863
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 335880
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820688
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1723
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1061
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 610
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19917
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19646
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 820013
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 9809181808 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 242384196872 (225.74 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90372.9 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1135390
telemt_connections_bad_total 6937
telemt_handshake_timeouts_total 11428
telemt_upstream_connect_attempt_total 24460
telemt_upstream_connect_success_total 24351
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 24460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1950
telemt_me_reconnect_attempts_total 23780
telemt_me_reconnect_success_total 19692
telemt_me_reader_eof_total 20762
telemt_me_idle_close_by_peer_total 20762
telemt_me_route_drop_no_conn_total 404370
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032437
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3985
telemt_desync_full_logged_total 1448
telemt_desync_suppressed_total 2537
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 1492
telemt_desync_frames_bucket_total{bucket="gt_10"} 1141
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20073
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19692
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 1032145
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 15094146119 (14.06 GB)
telemt_user_octets_to_client{user="hello"} 361805363602 (336.96 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 118
```