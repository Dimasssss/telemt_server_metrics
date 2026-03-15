# Server Metrics 2026-03-15 13:44:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 55796.7 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679837
telemt_connections_bad_total 96929
telemt_handshake_timeouts_total 16776
telemt_upstream_connect_attempt_total 11103
telemt_upstream_connect_success_total 11054
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13156
telemt_me_reconnect_success_total 8268
telemt_me_reader_eof_total 8858
telemt_me_idle_close_by_peer_total 8858
telemt_me_route_drop_no_conn_total 571060
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1415303
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5261
telemt_desync_full_logged_total 1470
telemt_desync_suppressed_total 3791
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 2043
telemt_desync_frames_bucket_total{bucket="gt_10"} 1859
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8552
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8257
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 1414943
telemt_user_connections_current{user="hello"} 2442
telemt_user_octets_from_client{user="hello"} 20414429992 (19.01 GB)
telemt_user_octets_to_client{user="hello"} 563629193140 (524.92 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 55797.6 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677517
telemt_connections_bad_total 35948
telemt_handshake_timeouts_total 50439
telemt_upstream_connect_attempt_total 14302
telemt_upstream_connect_success_total 14232
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11198
telemt_me_reconnect_success_total 11115
telemt_me_reader_eof_total 11752
telemt_me_idle_close_by_peer_total 11752
telemt_me_route_drop_no_conn_total 169078
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511278
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1960
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1285
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11250
telemt_me_writer_restored_same_endpoint_total 11103
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 511545
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 7254495743 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 194533058592 (181.17 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 55797.5 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1423130
telemt_connections_bad_total 43416
telemt_handshake_timeouts_total 147760
telemt_upstream_connect_attempt_total 12326
telemt_upstream_connect_success_total 12270
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10720
telemt_me_reconnect_success_total 9469
telemt_me_reader_eof_total 10037
telemt_me_idle_close_by_peer_total 10037
telemt_me_route_drop_no_conn_total 395565
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904548
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2291
telemt_desync_full_logged_total 844
telemt_desync_suppressed_total 1447
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 870
telemt_desync_frames_bucket_total{bucket="gt_10"} 900
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9631
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9450
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 901028
telemt_user_connections_current{user="hello"} 1269
telemt_user_octets_from_client{user="hello"} 13024876292 (12.13 GB)
telemt_user_octets_to_client{user="hello"} 327792498588 (305.28 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 55797.4 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689275
telemt_connections_bad_total 69977
telemt_handshake_timeouts_total 37284
telemt_upstream_connect_attempt_total 91300
telemt_upstream_connect_success_total 90861
telemt_upstream_connect_fail_total 439
telemt_upstream_connect_attempts_per_request{bucket="1"} 91300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 439
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 46741
telemt_me_reconnect_success_total 11781
telemt_me_reader_eof_total 13205
telemt_me_idle_close_by_peer_total 13205
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 168726
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440777
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1158
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12984
telemt_me_refill_failed_total 1093
telemt_me_writer_restored_same_endpoint_total 11749
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1203
telemt_user_connections_total{user="hello"} 516951
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 9571535128 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 178096833948 (165.87 GB)
telemt_user_msgs_from_client{user="hello"} 1411831
telemt_user_msgs_to_client{user="hello"} 5423980
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 55798.6 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717592
telemt_connections_bad_total 9140
telemt_handshake_timeouts_total 14962
telemt_upstream_connect_attempt_total 12272
telemt_upstream_connect_success_total 12205
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13095
telemt_me_reconnect_success_total 9425
telemt_me_reader_eof_total 10095
telemt_me_idle_close_by_peer_total 10095
telemt_me_route_drop_no_conn_total 178658
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583275
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2168
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1441
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9653
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9417
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 583316
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 7325409252 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 220246985652 (205.12 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 132
```