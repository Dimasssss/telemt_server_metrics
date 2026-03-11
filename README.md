# Server Metrics 2026-03-11 00:00:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34409.4 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774235
telemt_connections_bad_total 9280
telemt_handshake_timeouts_total 8689
telemt_upstream_connect_attempt_total 7482
telemt_upstream_connect_success_total 7473
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 465
telemt_me_reconnect_attempts_total 17329
telemt_me_reconnect_success_total 5666
telemt_me_reader_eof_total 6228
telemt_me_idle_close_by_peer_total 6228
telemt_me_route_drop_no_conn_total 319938
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732835
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3530
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 2543
telemt_desync_frames_bucket_total{bucket="1_2"} 1024
telemt_desync_frames_bucket_total{bucket="3_10"} 1316
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6077
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5660
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 732620
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 10162091668 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 217920218956 (202.95 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 34466.2 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334742
telemt_connections_bad_total 2382
telemt_handshake_timeouts_total 17621
telemt_upstream_connect_attempt_total 14391
telemt_upstream_connect_success_total 11513
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1702
telemt_me_reconnect_attempts_total 7603
telemt_me_reconnect_success_total 6791
telemt_me_reader_eof_total 7160
telemt_me_idle_close_by_peer_total 7158
telemt_me_route_drop_no_conn_total 170902
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284343
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1733
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6888
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6770
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 286612
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 2781551614 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 69318442928 (64.56 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 34466.0 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555999
telemt_connections_bad_total 3855
telemt_handshake_timeouts_total 34000
telemt_upstream_connect_attempt_total 9370
telemt_upstream_connect_success_total 9236
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 9370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 17447
telemt_me_reconnect_success_total 6389
telemt_me_reader_eof_total 6988
telemt_me_idle_close_by_peer_total 6988
telemt_me_route_drop_no_conn_total 191901
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6829
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6378
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 490594
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 6766418937 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 152439601017 (141.97 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 34466.5 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401719
telemt_connections_bad_total 32904
telemt_handshake_timeouts_total 37146
telemt_upstream_connect_attempt_total 9690
telemt_upstream_connect_success_total 9690
telemt_upstream_connect_attempts_per_request{bucket="1"} 9690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 392
telemt_me_reconnect_attempts_total 8945
telemt_me_reconnect_success_total 7916
telemt_me_reader_eof_total 8352
telemt_me_idle_close_by_peer_total 8352
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 125482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8029
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7901
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 318382
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 4115688780 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 89635801224 (83.48 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 34466.3 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424964
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2700
telemt_upstream_connect_attempt_total 10485
telemt_upstream_connect_success_total 10445
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 12400
telemt_me_reconnect_success_total 8637
telemt_me_reader_eof_total 9079
telemt_me_idle_close_by_peer_total 9079
telemt_me_route_drop_no_conn_total 144033
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393502
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2247
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 964
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 8868
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8637
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 393267
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 6875309532 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 144276071896 (134.37 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 32
```