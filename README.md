# Server Metrics 2026-03-15 12:17:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 50587.0 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1406330
telemt_connections_bad_total 82647
telemt_handshake_timeouts_total 11657
telemt_upstream_connect_attempt_total 10146
telemt_upstream_connect_success_total 10098
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12420
telemt_me_reconnect_success_total 7542
telemt_me_reader_eof_total 8096
telemt_me_idle_close_by_peer_total 8096
telemt_me_route_drop_no_conn_total 469611
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178754
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4488
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 3219
telemt_desync_frames_bucket_total{bucket="1_2"} 1087
telemt_desync_frames_bucket_total{bucket="3_10"} 1766
telemt_desync_frames_bucket_total{bucket="gt_10"} 1635
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7807
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7531
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 1178445
telemt_user_connections_current{user="hello"} 2088
telemt_user_octets_from_client{user="hello"} 16533367432 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 473122113380 (440.63 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 50587.7 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558271
telemt_connections_bad_total 28801
telemt_handshake_timeouts_total 32793
telemt_upstream_connect_attempt_total 13196
telemt_upstream_connect_success_total 13131
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10319
telemt_me_reconnect_success_total 10246
telemt_me_reader_eof_total 10839
telemt_me_idle_close_by_peer_total 10839
telemt_me_route_drop_no_conn_total 142155
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435348
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1703
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1113
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10359
telemt_me_writer_restored_same_endpoint_total 10234
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 435616
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 6166042583 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 161517166760 (150.42 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 50587.6 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1112227
telemt_connections_bad_total 36468
telemt_handshake_timeouts_total 111941
telemt_upstream_connect_attempt_total 11177
telemt_upstream_connect_success_total 11123
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 11177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 8554
telemt_me_reader_eof_total 9076
telemt_me_idle_close_by_peer_total 9076
telemt_me_route_drop_no_conn_total 346163
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756104
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1948
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1261
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8704
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8535
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 752620
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 11064731416 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 284474938104 (264.94 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 50587.4 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560154
telemt_connections_bad_total 65440
telemt_handshake_timeouts_total 32622
telemt_upstream_connect_attempt_total 14572
telemt_upstream_connect_success_total 14194
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 14572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 39350
telemt_me_reconnect_success_total 11640
telemt_me_reader_eof_total 12840
telemt_me_idle_close_by_peer_total 12840
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 158793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418013
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1097
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12616
telemt_me_refill_failed_total 866
telemt_me_writer_restored_same_endpoint_total 11608
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 976
telemt_user_connections_total{user="hello"} 417892
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 6935686824 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 141945367268 (132.20 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 50588.6 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598904
telemt_connections_bad_total 6879
telemt_handshake_timeouts_total 13003
telemt_upstream_connect_attempt_total 11262
telemt_upstream_connect_success_total 11204
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 8699
telemt_me_reconnect_success_total 8649
telemt_me_reader_eof_total 9178
telemt_me_idle_close_by_peer_total 9178
telemt_me_route_drop_no_conn_total 150897
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488197
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1920
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1290
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 764
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8749
telemt_me_writer_restored_same_endpoint_total 8641
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 488230
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 6350725172 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 175615190796 (163.55 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 118
```