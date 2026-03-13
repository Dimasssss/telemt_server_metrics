# Server Metrics 2026-03-13 09:58:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100786.2 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2899201
telemt_connections_bad_total 36439
telemt_handshake_timeouts_total 52076
telemt_upstream_connect_attempt_total 19878
telemt_upstream_connect_success_total 19769
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 19878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1421
telemt_me_reconnect_attempts_total 24843
telemt_me_reconnect_success_total 14776
telemt_me_reader_eof_total 15908
telemt_me_idle_close_by_peer_total 15907
telemt_me_route_drop_no_conn_total 1071358
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2642714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11534
telemt_desync_full_logged_total 2981
telemt_desync_suppressed_total 8553
telemt_desync_frames_bucket_total{bucket="1_2"} 2962
telemt_desync_frames_bucket_total{bucket="3_10"} 4314
telemt_desync_frames_bucket_total{bucket="gt_10"} 4258
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15295
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14763
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 2642557
telemt_user_connections_current{user="hello"} 1547
telemt_user_octets_from_client{user="hello"} 36576275924 (34.06 GB)
telemt_user_octets_to_client{user="hello"} 860162270732 (801.09 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 130406.6 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1174250
telemt_connections_bad_total 14707
telemt_handshake_timeouts_total 106869
telemt_upstream_connect_attempt_total 32272
telemt_upstream_connect_success_total 32241
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3734
telemt_me_reconnect_attempts_total 24265
telemt_me_reconnect_success_total 24139
telemt_me_reader_eof_total 25727
telemt_me_idle_close_by_peer_total 25727
telemt_me_route_drop_no_conn_total 361974
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010418
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4450
telemt_desync_full_logged_total 1347
telemt_desync_suppressed_total 3103
telemt_desync_frames_bucket_total{bucket="1_2"} 1615
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1364
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 24375
telemt_me_writer_restored_same_endpoint_total 24130
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 1012353
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 15421825796 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 369286295923 (343.92 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 130406.5 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2257848
telemt_connections_bad_total 24755
telemt_handshake_timeouts_total 153996
telemt_upstream_connect_attempt_total 29827
telemt_upstream_connect_success_total 29817
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1851
telemt_me_reconnect_attempts_total 24281
telemt_me_reconnect_success_total 22993
telemt_me_reader_eof_total 24357
telemt_me_idle_close_by_peer_total 24356
telemt_me_route_drop_no_conn_total 737577
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1807820
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5968
telemt_desync_full_logged_total 1903
telemt_desync_suppressed_total 4065
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 2183
telemt_desync_frames_bucket_total{bucket="gt_10"} 2813
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 23223
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22952
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 1807273
telemt_user_connections_current{user="hello"} 893
telemt_user_octets_from_client{user="hello"} 31395517188 (29.24 GB)
telemt_user_octets_to_client{user="hello"} 650800743129 (606.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 130407.0 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1429424
telemt_connections_bad_total 14235
telemt_handshake_timeouts_total 89103
telemt_upstream_connect_attempt_total 42777
telemt_upstream_connect_success_total 40470
telemt_upstream_connect_fail_total 2170
telemt_upstream_connect_attempts_per_request{bucket="1"} 42503
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2169
telemt_me_keepalive_timeout_total 11473
telemt_me_reconnect_attempts_total 37087
telemt_me_reconnect_success_total 28142
telemt_me_reader_eof_total 30300
telemt_me_idle_close_by_peer_total 30293
telemt_me_route_drop_no_conn_total 504017
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1193302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2231
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1494
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 28625
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28118
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 1198061
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 18213140041 (16.96 GB)
telemt_user_octets_to_client{user="hello"} 476532281978 (443.81 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 130406.9 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1597322
telemt_connections_bad_total 36068
telemt_handshake_timeouts_total 12989
telemt_upstream_connect_attempt_total 41801
telemt_upstream_connect_success_total 41306
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 41801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_timeout_total 2250
telemt_me_reconnect_attempts_total 52806
telemt_me_reconnect_success_total 34830
telemt_me_reader_eof_total 36587
telemt_me_idle_close_by_peer_total 36587
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 585065
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1454873
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5073
telemt_desync_full_logged_total 1808
telemt_desync_suppressed_total 3265
telemt_desync_frames_bucket_total{bucket="1_2"} 1561
telemt_desync_frames_bucket_total{bucket="3_10"} 1638
telemt_desync_frames_bucket_total{bucket="gt_10"} 1874
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35771
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34769
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 1454673
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 18613941976 (17.34 GB)
telemt_user_octets_to_client{user="hello"} 505080061868 (470.39 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 96
```