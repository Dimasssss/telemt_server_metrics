# Server Metrics 2026-03-12 15:10:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33113.1 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188024
telemt_connections_bad_total 20230
telemt_handshake_timeouts_total 12089
telemt_upstream_connect_attempt_total 6559
telemt_upstream_connect_success_total 6523
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 8746
telemt_me_reconnect_success_total 4842
telemt_me_reader_eof_total 5161
telemt_me_idle_close_by_peer_total 5160
telemt_me_route_drop_no_conn_total 420756
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5962
telemt_desync_full_logged_total 1489
telemt_desync_suppressed_total 4473
telemt_desync_frames_bucket_total{bucket="1_2"} 1528
telemt_desync_frames_bucket_total{bucket="3_10"} 2143
telemt_desync_frames_bucket_total{bucket="gt_10"} 2291
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5021
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4829
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1117474
telemt_user_connections_current{user="hello"} 1528
telemt_user_octets_from_client{user="hello"} 17621550648 (16.41 GB)
telemt_user_octets_to_client{user="hello"} 327106573080 (304.64 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62733.7 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539904
telemt_connections_bad_total 6457
telemt_handshake_timeouts_total 26886
telemt_upstream_connect_attempt_total 15096
telemt_upstream_connect_success_total 15089
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 11844
telemt_me_reconnect_success_total 11778
telemt_me_reader_eof_total 12517
telemt_me_idle_close_by_peer_total 12517
telemt_me_route_drop_no_conn_total 157625
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481265
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1848
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1266
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11889
telemt_me_writer_restored_same_endpoint_total 11769
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 481764
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 7384838967 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 169318757682 (157.69 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62733.8 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155531
telemt_connections_bad_total 6077
telemt_handshake_timeouts_total 81117
telemt_upstream_connect_attempt_total 15048
telemt_upstream_connect_success_total 15043
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 974
telemt_me_reconnect_attempts_total 12775
telemt_me_reconnect_success_total 11554
telemt_me_reader_eof_total 12190
telemt_me_idle_close_by_peer_total 12190
telemt_me_route_drop_no_conn_total 307823
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844787
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3515
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2431
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 1708
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11638
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11513
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 844977
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 11164741288 (10.40 GB)
telemt_user_octets_to_client{user="hello"} 265399162157 (247.17 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62734.0 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682913
telemt_connections_bad_total 7699
telemt_handshake_timeouts_total 57564
telemt_upstream_connect_attempt_total 16670
telemt_upstream_connect_success_total 16601
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 17331
telemt_me_reconnect_success_total 13470
telemt_me_reader_eof_total 14326
telemt_me_idle_close_by_peer_total 14326
telemt_me_route_drop_no_conn_total 230706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1156
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 756
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 466
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13692
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 13449
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 583560
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 6977552024 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 232706206376 (216.72 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62733.8 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767659
telemt_connections_bad_total 6531
telemt_handshake_timeouts_total 6131
telemt_upstream_connect_attempt_total 19707
telemt_upstream_connect_success_total 19463
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 1110
telemt_me_reconnect_attempts_total 23563
telemt_me_reconnect_success_total 16330
telemt_me_reader_eof_total 17096
telemt_me_idle_close_by_peer_total 17096
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 266927
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709447
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2848
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 1890
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 1067
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16724
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16296
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 709347
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 8447842004 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 196625833260 (183.12 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 126
```