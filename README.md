# Server Metrics 2026-03-13 16:16:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 123499.5 (34h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3891049
telemt_connections_bad_total 37455
telemt_handshake_timeouts_total 91224
telemt_upstream_connect_attempt_total 23962
telemt_upstream_connect_success_total 23825
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 27767
telemt_me_reconnect_success_total 17677
telemt_me_reader_eof_total 18999
telemt_me_idle_close_by_peer_total 18998
telemt_me_route_drop_no_conn_total 1444362
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3558090
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14158
telemt_desync_full_logged_total 3738
telemt_desync_suppressed_total 10420
telemt_desync_frames_bucket_total{bucket="1_2"} 3553
telemt_desync_frames_bucket_total{bucket="3_10"} 5361
telemt_desync_frames_bucket_total{bucket="gt_10"} 5244
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18233
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17664
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 556
telemt_user_connections_total{user="hello"} 3557895
telemt_user_connections_current{user="hello"} 1800
telemt_user_octets_from_client{user="hello"} 49181184840 (45.80 GB)
telemt_user_octets_to_client{user="hello"} 1113763314872 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23163.3 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338527
telemt_connections_bad_total 20989
telemt_handshake_timeouts_total 9399
telemt_upstream_connect_attempt_total 5385
telemt_upstream_connect_success_total 5298
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 5385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6398
telemt_me_reconnect_success_total 4103
telemt_me_reader_eof_total 4350
telemt_me_idle_close_by_peer_total 4350
telemt_me_route_drop_no_conn_total 122836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299662
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1119
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4229
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4096
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 299691
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 2991317548 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 84829073984 (79.00 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 153120.0 (42h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2869558
telemt_connections_bad_total 27941
telemt_handshake_timeouts_total 193421
telemt_upstream_connect_attempt_total 34247
telemt_upstream_connect_success_total 34237
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3287
telemt_me_reconnect_attempts_total 28818
telemt_me_reconnect_success_total 26267
telemt_me_reader_eof_total 27855
telemt_me_idle_close_by_peer_total 27854
telemt_me_route_drop_no_conn_total 971823
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2359706
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8314
telemt_desync_full_logged_total 2753
telemt_desync_suppressed_total 5561
telemt_desync_frames_bucket_total{bucket="1_2"} 1335
telemt_desync_frames_bucket_total{bucket="3_10"} 3030
telemt_desync_frames_bucket_total{bucket="gt_10"} 3949
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26576
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26226
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 2359090
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 38527878288 (35.88 GB)
telemt_user_octets_to_client{user="hello"} 821057649341 (764.67 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 153120.5 (42h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833699
telemt_connections_bad_total 18158
telemt_handshake_timeouts_total 154996
telemt_upstream_connect_attempt_total 48110
telemt_upstream_connect_success_total 45774
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 47836
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11888
telemt_me_reconnect_attempts_total 41257
telemt_me_reconnect_success_total 32284
telemt_me_reader_eof_total 34673
telemt_me_idle_close_by_peer_total 34666
telemt_me_route_drop_no_conn_total 656335
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520230
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3044
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 2060
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1261
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 32817
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32260
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 533
telemt_user_connections_total{user="hello"} 1524934
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 23559556625 (21.94 GB)
telemt_user_octets_to_client{user="hello"} 581242663426 (541.32 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22556.5 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366271
telemt_connections_bad_total 4136
telemt_handshake_timeouts_total 3373
telemt_upstream_connect_attempt_total 4906
telemt_upstream_connect_success_total 4763
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 4906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 14184
telemt_me_reconnect_success_total 3608
telemt_me_reader_eof_total 4009
telemt_me_idle_close_by_peer_total 4009
telemt_me_route_drop_no_conn_total 143864
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342730
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 807
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3960
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3604
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 342704
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 3946498456 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 110411701012 (102.83 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 111
```