# Server Metrics 2026-03-14 00:37:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 153502.1 (42h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4605991
telemt_connections_bad_total 38417
telemt_handshake_timeouts_total 107877
telemt_upstream_connect_attempt_total 32319
telemt_upstream_connect_success_total 32101
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6665
telemt_me_reconnect_attempts_total 32245
telemt_me_reconnect_success_total 22113
telemt_me_reader_eof_total 23719
telemt_me_idle_close_by_peer_total 23718
telemt_me_route_drop_no_conn_total 1744014
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4222452
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16640
telemt_desync_full_logged_total 4487
telemt_desync_suppressed_total 12153
telemt_desync_frames_bucket_total{bucket="1_2"} 4147
telemt_desync_frames_bucket_total{bucket="3_10"} 6362
telemt_desync_frames_bucket_total{bucket="gt_10"} 6131
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22747
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22100
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 4224327
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 62301756744 (58.02 GB)
telemt_user_octets_to_client{user="hello"} 1335048493537 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53165.6 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649575
telemt_connections_bad_total 48477
telemt_handshake_timeouts_total 12846
telemt_upstream_connect_attempt_total 14928
telemt_upstream_connect_success_total 14683
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 14928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 1941
telemt_me_reconnect_attempts_total 13429
telemt_me_reconnect_success_total 9987
telemt_me_reader_eof_total 10591
telemt_me_idle_close_by_peer_total 10590
telemt_me_route_drop_no_conn_total 226478
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536730
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10234
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9979
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 538681
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 5855701109 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 175033916860 (163.01 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 183122.3 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3338098
telemt_connections_bad_total 33968
telemt_handshake_timeouts_total 222444
telemt_upstream_connect_attempt_total 40972
telemt_upstream_connect_success_total 40951
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10355
telemt_me_reconnect_attempts_total 36469
telemt_me_reconnect_success_total 31513
telemt_me_reader_eof_total 33454
telemt_me_idle_close_by_peer_total 33453
telemt_me_route_drop_no_conn_total 1145611
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2774238
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9138
telemt_desync_full_logged_total 3069
telemt_desync_suppressed_total 6069
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 3311
telemt_desync_frames_bucket_total{bucket="gt_10"} 4289
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 31967
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31472
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 2773476
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 44891071016 (41.81 GB)
telemt_user_octets_to_client{user="hello"} 985304028681 (917.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 183125.0 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2213079
telemt_connections_bad_total 22910
telemt_handshake_timeouts_total 237805
telemt_upstream_connect_attempt_total 56993
telemt_upstream_connect_success_total 54537
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 56719
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2318
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20383
telemt_me_reconnect_attempts_total 47419
telemt_me_reconnect_success_total 38392
telemt_me_reader_eof_total 41191
telemt_me_idle_close_by_peer_total 41184
telemt_me_route_drop_no_conn_total 765222
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1780824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3798
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 39007
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38368
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 1786734
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 27388735355 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 663242195014 (617.69 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52558.7 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674539
telemt_connections_bad_total 7870
telemt_handshake_timeouts_total 8604
telemt_upstream_connect_attempt_total 12767
telemt_upstream_connect_success_total 12397
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 12767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_keepalive_timeout_total 1463
telemt_me_reconnect_attempts_total 41906
telemt_me_reconnect_success_total 9749
telemt_me_reader_eof_total 10951
telemt_me_idle_close_by_peer_total 10950
telemt_me_route_drop_no_conn_total 254351
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627201
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 10840
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9744
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1091
telemt_user_connections_total{user="hello"} 627100
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 10527717136 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 205263034812 (191.17 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 25
```