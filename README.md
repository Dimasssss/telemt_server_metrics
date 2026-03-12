# Server Metrics 2026-03-12 13:33:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27297.3 (7h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951514
telemt_connections_bad_total 7874
telemt_handshake_timeouts_total 8754
telemt_upstream_connect_attempt_total 5360
telemt_upstream_connect_success_total 5326
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 7814
telemt_me_reconnect_success_total 3916
telemt_me_reader_eof_total 4197
telemt_me_idle_close_by_peer_total 4196
telemt_me_route_drop_no_conn_total 335858
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4853
telemt_desync_full_logged_total 1222
telemt_desync_suppressed_total 3631
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 1759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1880
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4081
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3903
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 907143
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 15266561740 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 271187058272 (252.56 GB)
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56917.9 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461350
telemt_connections_bad_total 5295
telemt_handshake_timeouts_total 24700
telemt_upstream_connect_attempt_total 13768
telemt_upstream_connect_success_total 13761
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1109
telemt_me_reconnect_attempts_total 10782
telemt_me_reconnect_success_total 10723
telemt_me_reader_eof_total 11406
telemt_me_idle_close_by_peer_total 11406
telemt_me_route_drop_no_conn_total 132852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1374
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 925
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10821
telemt_me_writer_restored_same_endpoint_total 10714
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 408569
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 6384526511 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 149168771570 (138.92 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56917.8 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012917
telemt_connections_bad_total 5464
telemt_handshake_timeouts_total 76029
telemt_upstream_connect_attempt_total 13702
telemt_upstream_connect_success_total 13697
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 919
telemt_me_reconnect_attempts_total 10576
telemt_me_reconnect_success_total 10479
telemt_me_reader_eof_total 11043
telemt_me_idle_close_by_peer_total 11043
telemt_me_route_drop_no_conn_total 258286
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713116
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3085
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2148
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10514
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10438
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 713316
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 9364864692 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 231999400985 (216.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56918.3 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579279
telemt_connections_bad_total 7672
telemt_handshake_timeouts_total 53614
telemt_upstream_connect_attempt_total 15162
telemt_upstream_connect_success_total 15100
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1301
telemt_me_reconnect_attempts_total 13472
telemt_me_reconnect_success_total 12238
telemt_me_reader_eof_total 12982
telemt_me_idle_close_by_peer_total 12982
telemt_me_route_drop_no_conn_total 194574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 984
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12371
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12217
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 486561
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 5457402188 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 198155447424 (184.55 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56918.1 (15h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653735
telemt_connections_bad_total 1743
telemt_handshake_timeouts_total 5371
telemt_upstream_connect_attempt_total 18085
telemt_upstream_connect_success_total 17866
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 18085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 1015
telemt_me_reconnect_attempts_total 22229
telemt_me_reconnect_success_total 15002
telemt_me_reader_eof_total 15730
telemt_me_idle_close_by_peer_total 15730
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 222517
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608165
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2524
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1674
telemt_desync_frames_bucket_total{bucket="1_2"} 698
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15374
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14973
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 608075
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 6993637732 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 163360518884 (152.14 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 123
```