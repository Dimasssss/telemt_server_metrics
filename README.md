# Server Metrics 2026-03-10 19:10:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16987.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543370
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 3186
telemt_upstream_connect_attempt_total 3416
telemt_upstream_connect_success_total 3407
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 12960
telemt_me_reconnect_success_total 2501
telemt_me_reader_eof_total 2823
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 226682
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513165
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2670
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1942
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2838
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2495
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 513072
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 7613958608 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 148855488204 (138.63 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17043.8 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236467
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16474
telemt_upstream_connect_attempt_total 8698
telemt_upstream_connect_success_total 5954
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 706
telemt_me_reconnect_attempts_total 3870
telemt_me_reconnect_success_total 3086
telemt_me_reader_eof_total 3213
telemt_me_idle_close_by_peer_total 3211
telemt_me_route_drop_no_conn_total 129953
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199783
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 818
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3141
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3065
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 201740
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 2166772226 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 48283156582 (44.97 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17043.5 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392069
telemt_connections_bad_total 1245
telemt_handshake_timeouts_total 31959
telemt_upstream_connect_attempt_total 5221
telemt_upstream_connect_success_total 5140
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 5221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 6650
telemt_me_reconnect_success_total 3201
telemt_me_reader_eof_total 3418
telemt_me_idle_close_by_peer_total 3418
telemt_me_route_drop_no_conn_total 132500
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334036
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1067
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3368
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3190
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 334989
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 4661531821 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 107006642733 (99.66 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17044.1 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256199
telemt_connections_bad_total 16816
telemt_handshake_timeouts_total 22864
telemt_upstream_connect_attempt_total 4675
telemt_upstream_connect_success_total 4675
telemt_upstream_connect_attempts_per_request{bucket="1"} 4675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 4804
telemt_me_reconnect_success_total 3791
telemt_me_reader_eof_total 3949
telemt_me_idle_close_by_peer_total 3949
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 84222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205698
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3862
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3778
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 205487
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 3004371808 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 59896341484 (55.78 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17043.8 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271034
telemt_connections_bad_total 811
telemt_handshake_timeouts_total 1856
telemt_upstream_connect_attempt_total 5139
telemt_upstream_connect_success_total 5121
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 5139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4251
telemt_me_reconnect_success_total 4217
telemt_me_reader_eof_total 4339
telemt_me_idle_close_by_peer_total 4339
telemt_me_route_drop_no_conn_total 100740
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256000
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1426
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 910
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 597
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4273
telemt_me_writer_restored_same_endpoint_total 4217
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 255931
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 5298788672 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 80524083624 (74.99 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 89
```