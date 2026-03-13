# Server Metrics 2026-03-13 09:32:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99254.8 (27h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2830869
telemt_connections_bad_total 36388
telemt_handshake_timeouts_total 40906
telemt_upstream_connect_attempt_total 19527
telemt_upstream_connect_success_total 19419
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 24538
telemt_me_reconnect_success_total 14475
telemt_me_reader_eof_total 15603
telemt_me_idle_close_by_peer_total 15602
telemt_me_route_drop_no_conn_total 1050179
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2587613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11360
telemt_desync_full_logged_total 2938
telemt_desync_suppressed_total 8422
telemt_desync_frames_bucket_total{bucket="1_2"} 2914
telemt_desync_frames_bucket_total{bucket="3_10"} 4252
telemt_desync_frames_bucket_total{bucket="gt_10"} 4194
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14990
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14462
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 515
telemt_user_connections_total{user="hello"} 2587296
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 36076125172 (33.60 GB)
telemt_user_octets_to_client{user="hello"} 845871849068 (787.78 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 128875.3 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155965
telemt_connections_bad_total 14417
telemt_handshake_timeouts_total 106225
telemt_upstream_connect_attempt_total 31979
telemt_upstream_connect_success_total 31948
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3688
telemt_me_reconnect_attempts_total 24015
telemt_me_reconnect_success_total 23890
telemt_me_reader_eof_total 25467
telemt_me_idle_close_by_peer_total 25467
telemt_me_route_drop_no_conn_total 355068
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993734
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4373
telemt_desync_full_logged_total 1325
telemt_desync_suppressed_total 3048
telemt_desync_frames_bucket_total{bucket="1_2"} 1595
telemt_desync_frames_bucket_total{bucket="3_10"} 1441
telemt_desync_frames_bucket_total{bucket="gt_10"} 1337
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 24124
telemt_me_writer_restored_same_endpoint_total 23881
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 995661
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 15209487580 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 365449587631 (340.35 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 128875.2 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2219898
telemt_connections_bad_total 24648
telemt_handshake_timeouts_total 148109
telemt_upstream_connect_attempt_total 29596
telemt_upstream_connect_success_total 29586
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1809
telemt_me_reconnect_attempts_total 24094
telemt_me_reconnect_success_total 22807
telemt_me_reader_eof_total 24163
telemt_me_idle_close_by_peer_total 24162
telemt_me_route_drop_no_conn_total 723157
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776456
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5891
telemt_desync_full_logged_total 1876
telemt_desync_suppressed_total 4015
telemt_desync_frames_bucket_total{bucket="1_2"} 963
telemt_desync_frames_bucket_total{bucket="3_10"} 2150
telemt_desync_frames_bucket_total{bucket="gt_10"} 2778
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 23035
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22766
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 1775883
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 30943103040 (28.82 GB)
telemt_user_octets_to_client{user="hello"} 640263880589 (596.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 128875.6 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1408047
telemt_connections_bad_total 14229
telemt_handshake_timeouts_total 86428
telemt_upstream_connect_attempt_total 42482
telemt_upstream_connect_success_total 40177
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42208
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11468
telemt_me_reconnect_attempts_total 36838
telemt_me_reconnect_success_total 27896
telemt_me_reader_eof_total 30037
telemt_me_idle_close_by_peer_total 30030
telemt_me_route_drop_no_conn_total 495887
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2214
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28376
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27872
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 1179743
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 17765563681 (16.55 GB)
telemt_user_octets_to_client{user="hello"} 468363931878 (436.20 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 128875.4 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568953
telemt_connections_bad_total 35909
telemt_handshake_timeouts_total 12795
telemt_upstream_connect_attempt_total 41298
telemt_upstream_connect_success_total 40805
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 41298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 2208
telemt_me_reconnect_attempts_total 49949
telemt_me_reconnect_success_total 34375
telemt_me_reader_eof_total 36055
telemt_me_idle_close_by_peer_total 36055
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 573918
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1430518
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4984
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 3207
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1850
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35239
telemt_me_refill_failed_total 482
telemt_me_writer_restored_same_endpoint_total 34314
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 864
telemt_user_connections_total{user="hello"} 1430319
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 18384546076 (17.12 GB)
telemt_user_octets_to_client{user="hello"} 493867804820 (459.95 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 127
```