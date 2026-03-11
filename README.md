# Server Metrics 2026-03-11 11:32:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75916.2 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1709390
telemt_connections_bad_total 25369
telemt_handshake_timeouts_total 44419
telemt_upstream_connect_attempt_total 15910
telemt_upstream_connect_success_total 15901
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 812
telemt_me_reconnect_attempts_total 24873
telemt_me_reconnect_success_total 12053
telemt_me_reader_eof_total 13043
telemt_me_idle_close_by_peer_total 13043
telemt_me_route_drop_no_conn_total 629134
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1555019
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8235
telemt_desync_full_logged_total 2215
telemt_desync_suppressed_total 6020
telemt_desync_frames_bucket_total{bucket="1_2"} 2080
telemt_desync_frames_bucket_total{bucket="3_10"} 3140
telemt_desync_frames_bucket_total{bucket="gt_10"} 3015
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12576
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12047
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 1553586
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 20129569324 (18.75 GB)
telemt_user_octets_to_client{user="hello"} 441748960040 (411.41 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75972.9 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647780
telemt_connections_bad_total 11239
telemt_handshake_timeouts_total 40236
telemt_upstream_connect_attempt_total 24883
telemt_upstream_connect_success_total 21945
telemt_upstream_connect_fail_total 2938
telemt_upstream_connect_attempts_per_request{bucket="1"} 24883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2938
telemt_me_keepalive_timeout_total 2185
telemt_me_reconnect_attempts_total 16035
telemt_me_reconnect_success_total 15185
telemt_me_reader_eof_total 16079
telemt_me_idle_close_by_peer_total 16077
telemt_me_route_drop_no_conn_total 262882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549432
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2527
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1733
telemt_desync_frames_bucket_total{bucket="1_2"} 819
telemt_desync_frames_bucket_total{bucket="3_10"} 912
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15375
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15163
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 551652
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 5667553894 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 155338405884 (144.67 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75972.8 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127789
telemt_connections_bad_total 7838
telemt_handshake_timeouts_total 107286
telemt_upstream_connect_attempt_total 20583
telemt_upstream_connect_success_total 20333
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 826
telemt_me_reconnect_attempts_total 29062
telemt_me_reconnect_success_total 15435
telemt_me_reader_eof_total 16571
telemt_me_idle_close_by_peer_total 16571
telemt_me_route_drop_no_conn_total 378165
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 970959
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2658
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1868
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 997
telemt_desync_frames_bucket_total{bucket="gt_10"} 1033
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 16062
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15424
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 971711
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 11288781909 (10.51 GB)
telemt_user_octets_to_client{user="hello"} 295019935249 (274.76 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75973.1 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816557
telemt_connections_bad_total 71360
telemt_handshake_timeouts_total 75755
telemt_upstream_connect_attempt_total 20601
telemt_upstream_connect_success_total 20601
telemt_upstream_connect_attempts_per_request{bucket="1"} 20601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 815
telemt_me_reconnect_attempts_total 17861
telemt_me_reconnect_success_total 16800
telemt_me_reader_eof_total 17839
telemt_me_idle_close_by_peer_total 17838
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 259498
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646118
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1413
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 515
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17004
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16774
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 645486
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 7427610328 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 183535950388 (170.93 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75972.8 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878988
telemt_connections_bad_total 6222
telemt_handshake_timeouts_total 8442
telemt_upstream_connect_attempt_total 20802
telemt_upstream_connect_success_total 20710
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 20802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 883
telemt_me_reconnect_attempts_total 20848
telemt_me_reconnect_success_total 16790
telemt_me_reader_eof_total 17708
telemt_me_idle_close_by_peer_total 17708
telemt_me_route_drop_no_conn_total 307908
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797224
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3295
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1125
telemt_desync_frames_bucket_total{bucket="3_10"} 1301
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17131
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 16790
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 796984
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 11926886187 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 289513502962 (269.63 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 100
```