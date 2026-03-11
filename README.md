# Server Metrics 2026-03-11 05:00:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52391.4 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014486
telemt_connections_bad_total 10911
telemt_handshake_timeouts_total 32242
telemt_upstream_connect_attempt_total 11252
telemt_upstream_connect_success_total 11243
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 20235
telemt_me_reconnect_success_total 8559
telemt_me_reader_eof_total 9324
telemt_me_idle_close_by_peer_total 9324
telemt_me_route_drop_no_conn_total 378228
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 913196
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4174
telemt_desync_full_logged_total 1174
telemt_desync_suppressed_total 3000
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 1576
telemt_desync_frames_bucket_total{bucket="gt_10"} 1432
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9000
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8553
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 912908
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 12152932560 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 267347401728 (248.99 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52448.2 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397193
telemt_connections_bad_total 2679
telemt_handshake_timeouts_total 19241
telemt_upstream_connect_attempt_total 19622
telemt_upstream_connect_success_total 16718
telemt_upstream_connect_fail_total 2904
telemt_upstream_connect_attempts_per_request{bucket="1"} 19622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2904
telemt_me_keepalive_timeout_total 1781
telemt_me_reconnect_attempts_total 11938
telemt_me_reconnect_success_total 11118
telemt_me_reader_eof_total 11746
telemt_me_idle_close_by_peer_total 11744
telemt_me_route_drop_no_conn_total 188470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341276
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11250
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11097
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 343548
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 3290159610 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 82094476868 (76.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52448.1 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674708
telemt_connections_bad_total 5593
telemt_handshake_timeouts_total 36964
telemt_upstream_connect_attempt_total 14211
telemt_upstream_connect_success_total 14025
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 14211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 21370
telemt_me_reconnect_success_total 10298
telemt_me_reader_eof_total 11141
telemt_me_idle_close_by_peer_total 11141
telemt_me_route_drop_no_conn_total 227175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601858
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 1162
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 711
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10780
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10287
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 602725
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 7427535773 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 180425058081 (168.03 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52448.4 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515442
telemt_connections_bad_total 49339
telemt_handshake_timeouts_total 53994
telemt_upstream_connect_attempt_total 15138
telemt_upstream_connect_success_total 15138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 13530
telemt_me_reconnect_success_total 12488
telemt_me_reader_eof_total 13264
telemt_me_idle_close_by_peer_total 13264
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 152497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397822
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 844
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12633
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12467
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 397461
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 4835402172 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 108784286328 (101.31 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52448.0 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537432
telemt_connections_bad_total 5829
telemt_handshake_timeouts_total 3483
telemt_upstream_connect_attempt_total 15131
telemt_upstream_connect_success_total 15069
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 16160
telemt_me_reconnect_success_total 12378
telemt_me_reader_eof_total 13070
telemt_me_idle_close_by_peer_total 13070
telemt_me_route_drop_no_conn_total 174145
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490132
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2415
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 1468
telemt_desync_frames_bucket_total{bucket="1_2"} 888
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 504
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12653
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12378
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 489750
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 8923733744 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 173433479568 (161.52 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 72
```