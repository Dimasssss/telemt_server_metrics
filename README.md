# Server Metrics 2026-03-13 09:48:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100173.6 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2869752
telemt_connections_bad_total 36439
telemt_handshake_timeouts_total 43631
telemt_upstream_connect_attempt_total 19756
telemt_upstream_connect_success_total 19647
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 19756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1415
telemt_me_reconnect_attempts_total 24721
telemt_me_reconnect_success_total 14655
telemt_me_reader_eof_total 15785
telemt_me_idle_close_by_peer_total 15784
telemt_me_route_drop_no_conn_total 1063883
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2622220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11445
telemt_desync_full_logged_total 2964
telemt_desync_suppressed_total 8481
telemt_desync_frames_bucket_total{bucket="1_2"} 2935
telemt_desync_frames_bucket_total{bucket="3_10"} 4283
telemt_desync_frames_bucket_total{bucket="gt_10"} 4227
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15172
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14642
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 2622017
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 36424836132 (33.92 GB)
telemt_user_octets_to_client{user="hello"} 854127326684 (795.47 GB)
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 129794.0 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167141
telemt_connections_bad_total 14622
telemt_handshake_timeouts_total 106762
telemt_upstream_connect_attempt_total 32179
telemt_upstream_connect_success_total 32148
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3734
telemt_me_reconnect_attempts_total 24172
telemt_me_reconnect_success_total 24046
telemt_me_reader_eof_total 25634
telemt_me_idle_close_by_peer_total 25634
telemt_me_route_drop_no_conn_total 359888
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003954
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4411
telemt_desync_full_logged_total 1336
telemt_desync_suppressed_total 3075
telemt_desync_frames_bucket_total{bucket="1_2"} 1605
telemt_desync_frames_bucket_total{bucket="3_10"} 1457
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 24282
telemt_me_writer_restored_same_endpoint_total 24037
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 1005889
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 15338741060 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 367696999495 (342.44 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 129793.9 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243224
telemt_connections_bad_total 24685
telemt_handshake_timeouts_total 151775
telemt_upstream_connect_attempt_total 29765
telemt_upstream_connect_success_total 29755
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14042
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1834
telemt_me_reconnect_attempts_total 24219
telemt_me_reconnect_success_total 22931
telemt_me_reader_eof_total 24293
telemt_me_idle_close_by_peer_total 24292
telemt_me_route_drop_no_conn_total 731985
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1795664
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5942
telemt_desync_full_logged_total 1893
telemt_desync_suppressed_total 4049
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 2175
telemt_desync_frames_bucket_total{bucket="gt_10"} 2799
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 23159
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22890
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 1795127
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 31258713060 (29.11 GB)
telemt_user_octets_to_client{user="hello"} 645902866017 (601.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 129794.3 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1421244
telemt_connections_bad_total 14234
telemt_handshake_timeouts_total 88263
telemt_upstream_connect_attempt_total 42676
telemt_upstream_connect_success_total 40369
telemt_upstream_connect_fail_total 2170
telemt_upstream_connect_attempts_per_request{bucket="1"} 42402
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2169
telemt_me_keepalive_timeout_total 11472
telemt_me_reconnect_attempts_total 36986
telemt_me_reconnect_success_total 28041
telemt_me_reader_eof_total 30198
telemt_me_idle_close_by_peer_total 30191
telemt_me_route_drop_no_conn_total 501094
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1186065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2228
telemt_desync_full_logged_total 735
telemt_desync_suppressed_total 1493
telemt_desync_frames_bucket_total{bucket="1_2"} 615
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 28523
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28017
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 1190827
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 18080527393 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 473216413450 (440.72 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 129794.2 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1585861
telemt_connections_bad_total 36063
telemt_handshake_timeouts_total 12891
telemt_upstream_connect_attempt_total 41635
telemt_upstream_connect_success_total 41140
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 41635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_timeout_total 2248
telemt_me_reconnect_attempts_total 52512
telemt_me_reconnect_success_total 34664
telemt_me_reader_eof_total 36415
telemt_me_idle_close_by_peer_total 36415
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 580712
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1445568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5026
telemt_desync_full_logged_total 1791
telemt_desync_suppressed_total 3235
telemt_desync_frames_bucket_total{bucket="1_2"} 1535
telemt_desync_frames_bucket_total{bucket="3_10"} 1621
telemt_desync_frames_bucket_total{bucket="gt_10"} 1870
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35599
telemt_me_refill_failed_total 553
telemt_me_writer_restored_same_endpoint_total 34603
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 1445368
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 18512549976 (17.24 GB)
telemt_user_octets_to_client{user="hello"} 499117162508 (464.84 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 109
```