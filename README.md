# Server Metrics 2026-03-11 20:02:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 106549.2 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2706394
telemt_connections_bad_total 51207
telemt_handshake_timeouts_total 60726
telemt_upstream_connect_attempt_total 22552
telemt_upstream_connect_success_total 22540
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5401
telemt_me_reconnect_attempts_total 35026
telemt_me_reconnect_success_total 17132
telemt_me_reader_eof_total 18511
telemt_me_idle_close_by_peer_total 18511
telemt_me_route_drop_no_conn_total 1020746
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2468568
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12524
telemt_desync_full_logged_total 3475
telemt_desync_suppressed_total 9049
telemt_desync_frames_bucket_total{bucket="1_2"} 3085
telemt_desync_frames_bucket_total{bucket="3_10"} 4821
telemt_desync_frames_bucket_total{bucket="gt_10"} 4618
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17887
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17126
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 2466920
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 36711593184 (34.19 GB)
telemt_user_octets_to_client{user="hello"} 702718692788 (654.46 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106605.8 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000681
telemt_connections_bad_total 16501
telemt_handshake_timeouts_total 90224
telemt_upstream_connect_attempt_total 32767
telemt_upstream_connect_success_total 29795
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2082
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2870
telemt_me_reconnect_attempts_total 23596
telemt_me_reconnect_success_total 21475
telemt_me_reader_eof_total 22746
telemt_me_idle_close_by_peer_total 22743
telemt_me_route_drop_no_conn_total 378261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835157
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3322
telemt_desync_full_logged_total 1077
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 21789
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21452
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 837608
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 10081467706 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 243721609164 (226.98 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106605.7 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1731759
telemt_connections_bad_total 10827
telemt_handshake_timeouts_total 134458
telemt_upstream_connect_attempt_total 27258
telemt_upstream_connect_success_total 26915
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 27258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 55503
telemt_me_reconnect_success_total 20440
telemt_me_reader_eof_total 22394
telemt_me_idle_close_by_peer_total 22394
telemt_me_route_drop_no_conn_total 630267
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1521581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4131
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2912
telemt_desync_frames_bucket_total{bucket="1_2"} 967
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21816
telemt_me_refill_failed_total 1090
telemt_me_writer_restored_same_endpoint_total 20428
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1376
telemt_user_connections_total{user="hello"} 1521220
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 19606005185 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 466468343485 (434.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106606.3 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1236539
telemt_connections_bad_total 78220
telemt_handshake_timeouts_total 111092
telemt_upstream_connect_attempt_total 28749
telemt_upstream_connect_success_total 28749
telemt_upstream_connect_attempts_per_request{bucket="1"} 28749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1474
telemt_me_reconnect_attempts_total 28024
telemt_me_reconnect_success_total 23407
telemt_me_reader_eof_total 24857
telemt_me_idle_close_by_peer_total 24856
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 415080
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011810
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1360
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 668
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23796
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23374
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 1010936
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 12006386696 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 309624701512 (288.36 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11282.1 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175007
telemt_connections_bad_total 4311
telemt_handshake_timeouts_total 1868
telemt_upstream_connect_attempt_total 3266
telemt_upstream_connect_success_total 3265
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2665
telemt_me_reconnect_success_total 2638
telemt_me_reader_eof_total 2714
telemt_me_idle_close_by_peer_total 2714
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 58555
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 348
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2669
telemt_me_writer_restored_same_endpoint_total 2613
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 153869
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 9401738340 (8.76 GB)
telemt_user_octets_to_client{user="hello"} 51440267272 (47.91 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 66
```