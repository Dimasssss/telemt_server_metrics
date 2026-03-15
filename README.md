# Server Metrics 2026-03-15 16:17:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 64994.1 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2174439
telemt_connections_bad_total 129305
telemt_handshake_timeouts_total 26594
telemt_upstream_connect_attempt_total 12891
telemt_upstream_connect_success_total 12835
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14452
telemt_me_reconnect_success_total 9557
telemt_me_reader_eof_total 10217
telemt_me_idle_close_by_peer_total 10217
telemt_me_route_drop_no_conn_total 747483
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1828342
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7051
telemt_desync_full_logged_total 1944
telemt_desync_suppressed_total 5107
telemt_desync_frames_bucket_total{bucket="1_2"} 1729
telemt_desync_frames_bucket_total{bucket="3_10"} 2699
telemt_desync_frames_bucket_total{bucket="gt_10"} 2623
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9867
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9546
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 1827838
telemt_user_connections_current{user="hello"} 2421
telemt_user_octets_from_client{user="hello"} 26738281936 (24.90 GB)
telemt_user_octets_to_client{user="hello"} 700608912612 (652.49 GB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 64995.0 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853801
telemt_connections_bad_total 45408
telemt_handshake_timeouts_total 60184
telemt_upstream_connect_attempt_total 16368
telemt_upstream_connect_success_total 16288
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 16368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12767
telemt_me_reconnect_success_total 12664
telemt_me_reader_eof_total 13371
telemt_me_idle_close_by_peer_total 13371
telemt_me_route_drop_no_conn_total 217564
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653004
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2100
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 767
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12828
telemt_me_writer_restored_same_endpoint_total 12652
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 653249
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 9073623631 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 248118382828 (231.08 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 64995.1 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1937719
telemt_connections_bad_total 48284
telemt_handshake_timeouts_total 190360
telemt_upstream_connect_attempt_total 14122
telemt_upstream_connect_success_total 14054
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 14122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12015
telemt_me_reconnect_success_total 10750
telemt_me_reader_eof_total 11389
telemt_me_idle_close_by_peer_total 11389
telemt_me_route_drop_no_conn_total 498760
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1162594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2887
telemt_desync_full_logged_total 1052
telemt_desync_suppressed_total 1835
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 1109
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10938
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10731
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1158563
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 16753073056 (15.60 GB)
telemt_user_octets_to_client{user="hello"} 417262205032 (388.61 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 64995.1 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906988
telemt_connections_bad_total 78374
telemt_handshake_timeouts_total 44021
telemt_upstream_connect_attempt_total 168722
telemt_upstream_connect_success_total 168197
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 168722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 54065
telemt_me_reconnect_success_total 12851
telemt_me_reader_eof_total 14494
telemt_me_idle_close_by_peer_total 14494
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 204698
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546888
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1501
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14270
telemt_me_refill_failed_total 1289
telemt_me_writer_restored_same_endpoint_total 12815
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1419
telemt_user_connections_total{user="hello"} 698528
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 13512172638 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 247766842261 (230.75 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 64995.7 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917309
telemt_connections_bad_total 11730
telemt_handshake_timeouts_total 20001
telemt_upstream_connect_attempt_total 14592
telemt_upstream_connect_success_total 14512
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14916
telemt_me_reconnect_success_total 11229
telemt_me_reader_eof_total 11978
telemt_me_idle_close_by_peer_total 11978
telemt_me_route_drop_no_conn_total 229050
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756519
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2605
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1726
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 988
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11479
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11221
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 756562
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 9301731700 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 271334777828 (252.70 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 134
```