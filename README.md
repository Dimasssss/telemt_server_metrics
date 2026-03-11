# Server Metrics 2026-03-11 04:34:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50866.9 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985920
telemt_connections_bad_total 10080
telemt_handshake_timeouts_total 29245
telemt_upstream_connect_attempt_total 10957
telemt_upstream_connect_success_total 10948
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 534
telemt_me_reconnect_attempts_total 20026
telemt_me_reconnect_success_total 8352
telemt_me_reader_eof_total 9102
telemt_me_idle_close_by_peer_total 9102
telemt_me_route_drop_no_conn_total 370414
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889460
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4023
telemt_desync_full_logged_total 1128
telemt_desync_suppressed_total 2895
telemt_desync_frames_bucket_total{bucket="1_2"} 1135
telemt_desync_frames_bucket_total{bucket="3_10"} 1510
telemt_desync_frames_bucket_total{bucket="gt_10"} 1378
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8792
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8346
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 889181
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 11622870828 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 261648420744 (243.68 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50923.6 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389953
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 18909
telemt_upstream_connect_attempt_total 19244
telemt_upstream_connect_success_total 16347
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 19244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1777
telemt_me_reconnect_attempts_total 11654
telemt_me_reconnect_success_total 10836
telemt_me_reader_eof_total 11450
telemt_me_idle_close_by_peer_total 11448
telemt_me_route_drop_no_conn_total 186154
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334893
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 10963
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10815
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 337165
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 3229963250 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 80451935596 (74.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50923.3 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656791
telemt_connections_bad_total 5547
telemt_handshake_timeouts_total 36147
telemt_upstream_connect_attempt_total 13821
telemt_upstream_connect_success_total 13642
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 21073
telemt_me_reconnect_success_total 10003
telemt_me_reader_eof_total 10817
telemt_me_idle_close_by_peer_total 10817
telemt_me_route_drop_no_conn_total 221753
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585294
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1631
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10478
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9992
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 586172
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 7298581933 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 177250687525 (165.08 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50923.7 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500698
telemt_connections_bad_total 47950
telemt_handshake_timeouts_total 52662
telemt_upstream_connect_attempt_total 14765
telemt_upstream_connect_success_total 14765
telemt_upstream_connect_attempts_per_request{bucket="1"} 14765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 486
telemt_me_reconnect_attempts_total 13246
telemt_me_reconnect_success_total 12205
telemt_me_reader_eof_total 12959
telemt_me_idle_close_by_peer_total 12959
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 148869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385924
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 824
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12347
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12185
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 385592
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 4657982468 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 105260437124 (98.03 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50923.3 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525092
telemt_connections_bad_total 5827
telemt_handshake_timeouts_total 3381
telemt_upstream_connect_attempt_total 14788
telemt_upstream_connect_success_total 14726
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 15904
telemt_me_reconnect_success_total 12122
telemt_me_reader_eof_total 12797
telemt_me_idle_close_by_peer_total 12797
telemt_me_route_drop_no_conn_total 169861
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478146
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2394
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12397
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12122
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 477766
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 8794433272 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 169225202148 (157.60 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 61
```