# Server Metrics 2026-03-13 23:45:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 150434.9 (41h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4579660
telemt_connections_bad_total 38388
telemt_handshake_timeouts_total 107774
telemt_upstream_connect_attempt_total 31618
telemt_upstream_connect_success_total 31401
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 31618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 6654
telemt_me_reconnect_attempts_total 31678
telemt_me_reconnect_success_total 21547
telemt_me_reader_eof_total 23112
telemt_me_idle_close_by_peer_total 23111
telemt_me_route_drop_no_conn_total 1731376
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4196922
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16602
telemt_desync_full_logged_total 4471
telemt_desync_suppressed_total 12131
telemt_desync_frames_bucket_total{bucket="1_2"} 4133
telemt_desync_frames_bucket_total{bucket="3_10"} 6351
telemt_desync_frames_bucket_total{bucket="gt_10"} 6118
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 22175
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21534
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 4198845
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 61809908852 (57.56 GB)
telemt_user_octets_to_client{user="hello"} 1327046534697 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50098.6 (13h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619787
telemt_connections_bad_total 46013
telemt_handshake_timeouts_total 12725
telemt_upstream_connect_attempt_total 14145
telemt_upstream_connect_success_total 13906
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 14145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 1926
telemt_me_reconnect_attempts_total 12804
telemt_me_reconnect_success_total 9365
telemt_me_reader_eof_total 9930
telemt_me_idle_close_by_peer_total 9929
telemt_me_route_drop_no_conn_total 222025
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528365
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
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9608
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9357
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 530316
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 5817179145 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 173409224320 (161.50 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 180055.4 (50h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3320814
telemt_connections_bad_total 32323
telemt_handshake_timeouts_total 222095
telemt_upstream_connect_attempt_total 40058
telemt_upstream_connect_success_total 40037
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 40058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10342
telemt_me_reconnect_attempts_total 35708
telemt_me_reconnect_success_total 30753
telemt_me_reader_eof_total 32639
telemt_me_idle_close_by_peer_total 32638
telemt_me_route_drop_no_conn_total 1139553
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2759345
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9036
telemt_desync_full_logged_total 3040
telemt_desync_suppressed_total 5996
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3275
telemt_desync_frames_bucket_total{bucket="gt_10"} 4242
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 31203
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30712
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 2758592
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 44772198692 (41.70 GB)
telemt_user_octets_to_client{user="hello"} 976085937177 (909.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 180057.8 (50h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2189690
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 232310
telemt_upstream_connect_attempt_total 56046
telemt_upstream_connect_success_total 53593
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 55772
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46631
telemt_me_reconnect_success_total 37608
telemt_me_reader_eof_total 40337
telemt_me_idle_close_by_peer_total 40330
telemt_me_route_drop_no_conn_total 761766
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1771371
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3796
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 38216
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37584
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 1777264
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 27353082479 (25.47 GB)
telemt_user_octets_to_client{user="hello"} 661606625670 (616.17 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49491.4 (13h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661111
telemt_connections_bad_total 7858
telemt_handshake_timeouts_total 7918
telemt_upstream_connect_attempt_total 11786
telemt_upstream_connect_success_total 11435
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 11786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 39741
telemt_me_reconnect_success_total 8962
telemt_me_reader_eof_total 10081
telemt_me_idle_close_by_peer_total 10080
telemt_me_route_drop_no_conn_total 250313
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615465
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1611
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 10007
telemt_me_refill_failed_total 958
telemt_me_writer_restored_same_endpoint_total 8957
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1045
telemt_user_connections_total{user="hello"} 615364
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 9849277300 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 200787050856 (187.00 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 22
```