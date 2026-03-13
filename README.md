# Server Metrics 2026-03-13 17:53:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 129309.8 (35h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4127393
telemt_connections_bad_total 37530
telemt_handshake_timeouts_total 101572
telemt_upstream_connect_attempt_total 27372
telemt_upstream_connect_success_total 27193
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5698
telemt_me_reconnect_attempts_total 28507
telemt_me_reconnect_success_total 18401
telemt_me_reader_eof_total 19766
telemt_me_idle_close_by_peer_total 19765
telemt_me_route_drop_no_conn_total 1537314
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3770103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14726
telemt_desync_full_logged_total 3922
telemt_desync_suppressed_total 10804
telemt_desync_frames_bucket_total{bucket="1_2"} 3650
telemt_desync_frames_bucket_total{bucket="3_10"} 5588
telemt_desync_frames_bucket_total{bucket="gt_10"} 5488
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 18975
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18388
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 3772266
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 53054903936 (49.41 GB)
telemt_user_octets_to_client{user="hello"} 1170911039541 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 28973.8 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433037
telemt_connections_bad_total 32950
telemt_handshake_timeouts_total 10489
telemt_upstream_connect_attempt_total 8285
telemt_upstream_connect_success_total 8108
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 8591
telemt_me_reconnect_success_total 5193
telemt_me_reader_eof_total 5502
telemt_me_idle_close_by_peer_total 5501
telemt_me_route_drop_no_conn_total 162437
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1293
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 958
telemt_desync_frames_bucket_total{bucket="1_2"} 254
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5366
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 378518
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 3886531067 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 116009869012 (108.04 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 158930.5 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3019146
telemt_connections_bad_total 28753
telemt_handshake_timeouts_total 201751
telemt_upstream_connect_attempt_total 35475
telemt_upstream_connect_success_total 35465
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3483
telemt_me_reconnect_attempts_total 29778
telemt_me_reconnect_success_total 27224
telemt_me_reader_eof_total 28868
telemt_me_idle_close_by_peer_total 28867
telemt_me_route_drop_no_conn_total 1030098
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2495899
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8521
telemt_desync_full_logged_total 2826
telemt_desync_suppressed_total 5695
telemt_desync_frames_bucket_total{bucket="1_2"} 1375
telemt_desync_frames_bucket_total{bucket="3_10"} 3118
telemt_desync_frames_bucket_total{bucket="gt_10"} 4028
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 27542
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27183
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 2495233
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 40956640116 (38.14 GB)
telemt_user_octets_to_client{user="hello"} 869935362089 (810.19 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 158930.9 (44h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1944911
telemt_connections_bad_total 18259
telemt_handshake_timeouts_total 180239
telemt_upstream_connect_attempt_total 49343
telemt_upstream_connect_success_total 47002
telemt_upstream_connect_fail_total 2204
telemt_upstream_connect_attempts_per_request{bucket="1"} 49069
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11971
telemt_me_reconnect_attempts_total 42222
telemt_me_reconnect_success_total 33239
telemt_me_reader_eof_total 35693
telemt_me_idle_close_by_peer_total 35686
telemt_me_route_drop_no_conn_total 690856
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1603661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3153
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2127
telemt_desync_frames_bucket_total{bucket="1_2"} 876
telemt_desync_frames_bucket_total{bucket="3_10"} 1292
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 33786
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33215
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 1608357
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 24774835353 (23.07 GB)
telemt_user_octets_to_client{user="hello"} 608004581990 (566.25 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 28367.3 (7h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463960
telemt_connections_bad_total 4629
telemt_handshake_timeouts_total 4868
telemt_upstream_connect_attempt_total 6472
telemt_upstream_connect_success_total 6263
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 6472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 19025
telemt_me_reconnect_success_total 4817
telemt_me_reader_eof_total 5355
telemt_me_idle_close_by_peer_total 5355
telemt_me_route_drop_no_conn_total 177513
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433876
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1314
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 894
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5299
telemt_me_refill_failed_total 442
telemt_me_writer_restored_same_endpoint_total 4813
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 433848
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 4926709172 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 135341601400 (126.05 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 99
```