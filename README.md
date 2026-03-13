# Server Metrics 2026-03-13 16:06:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 122888.0 (34h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3863437
telemt_connections_bad_total 37438
telemt_handshake_timeouts_total 90087
telemt_upstream_connect_attempt_total 23867
telemt_upstream_connect_success_total 23730
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 27715
telemt_me_reconnect_success_total 17625
telemt_me_reader_eof_total 18941
telemt_me_idle_close_by_peer_total 18940
telemt_me_route_drop_no_conn_total 1433391
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3532486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14106
telemt_desync_full_logged_total 3723
telemt_desync_suppressed_total 10383
telemt_desync_frames_bucket_total{bucket="1_2"} 3531
telemt_desync_frames_bucket_total{bucket="3_10"} 5344
telemt_desync_frames_bucket_total{bucket="gt_10"} 5231
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18179
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17612
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3532293
telemt_user_connections_current{user="hello"} 1963
telemt_user_octets_from_client{user="hello"} 47947352828 (44.65 GB)
telemt_user_octets_to_client{user="hello"} 1107617115000 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22551.8 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328109
telemt_connections_bad_total 19361
telemt_handshake_timeouts_total 9005
telemt_upstream_connect_attempt_total 5190
telemt_upstream_connect_success_total 5104
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 5190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6229
telemt_me_reconnect_success_total 3938
telemt_me_reader_eof_total 4184
telemt_me_idle_close_by_peer_total 4184
telemt_me_route_drop_no_conn_total 119468
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291462
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1081
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4062
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3931
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 291491
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 2910228156 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 81996080236 (76.36 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 152508.5 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2851787
telemt_connections_bad_total 27820
telemt_handshake_timeouts_total 192107
telemt_upstream_connect_attempt_total 34156
telemt_upstream_connect_success_total 34146
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3286
telemt_me_reconnect_attempts_total 28770
telemt_me_reconnect_success_total 26219
telemt_me_reader_eof_total 27806
telemt_me_idle_close_by_peer_total 27805
telemt_me_route_drop_no_conn_total 964828
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2343350
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8268
telemt_desync_full_logged_total 2733
telemt_desync_suppressed_total 5535
telemt_desync_frames_bucket_total{bucket="1_2"} 1329
telemt_desync_frames_bucket_total{bucket="3_10"} 3006
telemt_desync_frames_bucket_total{bucket="gt_10"} 3933
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 26527
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26178
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 2342743
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 38405528208 (35.77 GB)
telemt_user_octets_to_client{user="hello"} 816416447405 (760.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 152509.0 (42h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1815204
telemt_connections_bad_total 18156
telemt_handshake_timeouts_total 145947
telemt_upstream_connect_attempt_total 47958
telemt_upstream_connect_success_total 45624
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 47684
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11886
telemt_me_reconnect_attempts_total 41150
telemt_me_reconnect_success_total 32177
telemt_me_reader_eof_total 34563
telemt_me_idle_close_by_peer_total 34556
telemt_me_route_drop_no_conn_total 651589
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1510173
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3015
telemt_desync_full_logged_total 977
telemt_desync_suppressed_total 2038
telemt_desync_frames_bucket_total{bucket="1_2"} 810
telemt_desync_frames_bucket_total{bucket="3_10"} 1243
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 32708
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32153
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 1514881
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 23469205925 (21.86 GB)
telemt_user_octets_to_client{user="hello"} 578102034066 (538.40 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21944.4 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354277
telemt_connections_bad_total 4115
telemt_handshake_timeouts_total 3233
telemt_upstream_connect_attempt_total 4783
telemt_upstream_connect_success_total 4640
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 4783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 14078
telemt_me_reconnect_success_total 3502
telemt_me_reader_eof_total 3903
telemt_me_idle_close_by_peer_total 3903
telemt_me_route_drop_no_conn_total 139942
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331913
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1145
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3854
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3498
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 331888
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 3840375800 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 106673508156 (99.35 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 117
```