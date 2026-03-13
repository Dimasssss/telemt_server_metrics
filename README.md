# Server Metrics 2026-03-13 18:55:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 132982.8 (36h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4251202
telemt_connections_bad_total 37748
telemt_handshake_timeouts_total 103242
telemt_upstream_connect_attempt_total 27984
telemt_upstream_connect_success_total 27795
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 27984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 6487
telemt_me_reconnect_attempts_total 28941
telemt_me_reconnect_success_total 18826
telemt_me_reader_eof_total 20209
telemt_me_idle_close_by_peer_total 20208
telemt_me_route_drop_no_conn_total 1593812
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3886052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15258
telemt_desync_full_logged_total 4066
telemt_desync_suppressed_total 11192
telemt_desync_frames_bucket_total{bucket="1_2"} 3787
telemt_desync_frames_bucket_total{bucket="3_10"} 5811
telemt_desync_frames_bucket_total{bucket="gt_10"} 5660
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19409
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18813
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 3888221
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 54871760984 (51.10 GB)
telemt_user_octets_to_client{user="hello"} 1219357665253 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 32646.7 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478728
telemt_connections_bad_total 37439
telemt_handshake_timeouts_total 10845
telemt_upstream_connect_attempt_total 9800
telemt_upstream_connect_success_total 9589
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1862
telemt_me_reconnect_attempts_total 9308
telemt_me_reconnect_success_total 5897
telemt_me_reader_eof_total 6234
telemt_me_idle_close_by_peer_total 6233
telemt_me_route_drop_no_conn_total 180025
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416102
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 388
telemt_desync_suppressed_total 1066
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6084
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5889
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 418037
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 4408746333 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 131140697404 (122.13 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 162603.4 (45h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3106119
telemt_connections_bad_total 28942
telemt_handshake_timeouts_total 208167
telemt_upstream_connect_attempt_total 36134
telemt_upstream_connect_success_total 36119
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 9784
telemt_me_reconnect_attempts_total 30265
telemt_me_reconnect_success_total 27702
telemt_me_reader_eof_total 29370
telemt_me_idle_close_by_peer_total 29369
telemt_me_route_drop_no_conn_total 1061292
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2567649
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8632
telemt_desync_full_logged_total 2856
telemt_desync_suppressed_total 5776
telemt_desync_frames_bucket_total{bucket="1_2"} 1407
telemt_desync_frames_bucket_total{bucket="3_10"} 3165
telemt_desync_frames_bucket_total{bucket="gt_10"} 4060
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 28029
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27661
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 2566949
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 42245878068 (39.34 GB)
telemt_user_octets_to_client{user="hello"} 902728270493 (840.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 162603.8 (45h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1997787
telemt_connections_bad_total 20631
telemt_handshake_timeouts_total 182893
telemt_upstream_connect_attempt_total 51349
telemt_upstream_connect_success_total 48916
telemt_upstream_connect_fail_total 2296
telemt_upstream_connect_attempts_per_request{bucket="1"} 51075
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2295
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 19961
telemt_me_reconnect_attempts_total 42798
telemt_me_reconnect_success_total 33793
telemt_me_reader_eof_total 36284
telemt_me_idle_close_by_peer_total 36277
telemt_me_route_drop_no_conn_total 711293
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1649246
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3399
telemt_desync_full_logged_total 1099
telemt_desync_suppressed_total 2300
telemt_desync_frames_bucket_total{bucket="1_2"} 922
telemt_desync_frames_bucket_total{bucket="3_10"} 1390
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 34351
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33769
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 1655119
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 25396133223 (23.65 GB)
telemt_user_octets_to_client{user="hello"} 627691537594 (584.58 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32039.2 (8h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519128
telemt_connections_bad_total 4943
telemt_handshake_timeouts_total 5209
telemt_upstream_connect_attempt_total 6996
telemt_upstream_connect_success_total 6764
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 6996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 24699
telemt_me_reconnect_success_total 5141
telemt_me_reader_eof_total 5842
telemt_me_idle_close_by_peer_total 5841
telemt_me_route_drop_no_conn_total 197171
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486390
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 952
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5794
telemt_me_refill_failed_total 609
telemt_me_writer_restored_same_endpoint_total 5137
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 486348
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 5630232008 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 156154789604 (145.43 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 81
```