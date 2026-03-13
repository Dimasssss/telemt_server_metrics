# Server Metrics 2026-03-13 17:23:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 127473.9 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4062510
telemt_connections_bad_total 37522
telemt_handshake_timeouts_total 100796
telemt_upstream_connect_attempt_total 27092
telemt_upstream_connect_success_total 26914
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 27092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 5666
telemt_me_reconnect_attempts_total 28316
telemt_me_reconnect_success_total 18211
telemt_me_reader_eof_total 19562
telemt_me_idle_close_by_peer_total 19561
telemt_me_route_drop_no_conn_total 1509665
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3709746
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14516
telemt_desync_full_logged_total 3852
telemt_desync_suppressed_total 10664
telemt_desync_frames_bucket_total{bucket="1_2"} 3618
telemt_desync_frames_bucket_total{bucket="3_10"} 5502
telemt_desync_frames_bucket_total{bucket="gt_10"} 5396
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18779
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18198
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 3711914
telemt_user_connections_current{user="hello"} 1675
telemt_user_octets_from_client{user="hello"} 52397166952 (48.80 GB)
telemt_user_octets_to_client{user="hello"} 1155842138397 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27137.8 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405757
telemt_connections_bad_total 30071
telemt_handshake_timeouts_total 10353
telemt_upstream_connect_attempt_total 7851
telemt_upstream_connect_success_total 7677
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 1581
telemt_me_reconnect_attempts_total 8247
telemt_me_reconnect_success_total 4852
telemt_me_reader_eof_total 5137
telemt_me_idle_close_by_peer_total 5136
telemt_me_route_drop_no_conn_total 154023
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353799
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1253
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 934
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5017
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4844
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 355137
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 3617298051 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 103041136516 (95.96 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 157094.6 (43h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2972409
telemt_connections_bad_total 28457
telemt_handshake_timeouts_total 199147
telemt_upstream_connect_attempt_total 35098
telemt_upstream_connect_success_total 35088
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3393
telemt_me_reconnect_attempts_total 29492
telemt_me_reconnect_success_total 26938
telemt_me_reader_eof_total 28556
telemt_me_idle_close_by_peer_total 28555
telemt_me_route_drop_no_conn_total 1011605
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2453257
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8493
telemt_desync_full_logged_total 2813
telemt_desync_suppressed_total 5680
telemt_desync_frames_bucket_total{bucket="1_2"} 1364
telemt_desync_frames_bucket_total{bucket="3_10"} 3109
telemt_desync_frames_bucket_total{bucket="gt_10"} 4020
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27253
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26897
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 2452611
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 40336960352 (37.57 GB)
telemt_user_octets_to_client{user="hello"} 856334766825 (797.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 157095.1 (43h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1918832
telemt_connections_bad_total 18256
telemt_handshake_timeouts_total 178321
telemt_upstream_connect_attempt_total 48977
telemt_upstream_connect_success_total 46638
telemt_upstream_connect_fail_total 2201
telemt_upstream_connect_attempts_per_request{bucket="1"} 48702
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11966
telemt_me_reconnect_attempts_total 41945
telemt_me_reconnect_success_total 32961
telemt_me_reader_eof_total 35400
telemt_me_idle_close_by_peer_total 35393
telemt_me_route_drop_no_conn_total 680592
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1580339
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2105
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 33506
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32937
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 1585030
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 24433749881 (22.76 GB)
telemt_user_octets_to_client{user="hello"} 600620806818 (559.37 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26530.5 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433649
telemt_connections_bad_total 4491
telemt_handshake_timeouts_total 4457
telemt_upstream_connect_attempt_total 6089
telemt_upstream_connect_success_total 5894
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 6089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 852
telemt_me_reconnect_attempts_total 16246
telemt_me_reconnect_success_total 4535
telemt_me_reader_eof_total 4996
telemt_me_idle_close_by_peer_total 4996
telemt_me_route_drop_no_conn_total 167923
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405220
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1263
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4937
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4531
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 405195
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 4644961036 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 127840592344 (119.06 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 86
```