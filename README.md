# Server Metrics 2026-03-11 09:14:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67650.1 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430899
telemt_connections_bad_total 17594
telemt_handshake_timeouts_total 40450
telemt_upstream_connect_attempt_total 14125
telemt_upstream_connect_success_total 14116
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 22367
telemt_me_reconnect_success_total 10680
telemt_me_reader_eof_total 11573
telemt_me_idle_close_by_peer_total 11573
telemt_me_route_drop_no_conn_total 525578
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297788
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6354
telemt_desync_full_logged_total 1760
telemt_desync_suppressed_total 4594
telemt_desync_frames_bucket_total{bucket="1_2"} 1673
telemt_desync_frames_bucket_total{bucket="3_10"} 2412
telemt_desync_frames_bucket_total{bucket="gt_10"} 2269
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11147
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10674
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 1297457
telemt_user_connections_current{user="hello"} 1343
telemt_user_octets_from_client{user="hello"} 17128270560 (15.95 GB)
telemt_user_octets_to_client{user="hello"} 371872018796 (346.33 GB)
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67707.0 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550778
telemt_connections_bad_total 9293
telemt_handshake_timeouts_total 30576
telemt_upstream_connect_attempt_total 23058
telemt_upstream_connect_success_total 20131
telemt_upstream_connect_fail_total 2927
telemt_upstream_connect_attempts_per_request{bucket="1"} 23058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2927
telemt_me_keepalive_timeout_total 2078
telemt_me_reconnect_attempts_total 14615
telemt_me_reconnect_success_total 13780
telemt_me_reader_eof_total 14591
telemt_me_idle_close_by_peer_total 14589
telemt_me_route_drop_no_conn_total 231007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467008
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2180
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1511
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 784
telemt_desync_frames_bucket_total{bucket="gt_10"} 668
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13942
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13758
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 469246
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 4579275858 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 125612279252 (116.99 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67706.8 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958145
telemt_connections_bad_total 7443
telemt_handshake_timeouts_total 91200
telemt_upstream_connect_attempt_total 18317
telemt_upstream_connect_success_total 18091
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 764
telemt_me_reconnect_attempts_total 25974
telemt_me_reconnect_success_total 13608
telemt_me_reader_eof_total 14626
telemt_me_idle_close_by_peer_total 14626
telemt_me_route_drop_no_conn_total 314914
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821207
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2353
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1655
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14171
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13597
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 822075
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 9761515149 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 249624699173 (232.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67707.1 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701578
telemt_connections_bad_total 63499
telemt_handshake_timeouts_total 68332
telemt_upstream_connect_attempt_total 18728
telemt_upstream_connect_success_total 18728
telemt_upstream_connect_attempts_per_request{bucket="1"} 18728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 694
telemt_me_reconnect_attempts_total 16383
telemt_me_reconnect_success_total 15329
telemt_me_reader_eof_total 16282
telemt_me_idle_close_by_peer_total 16281
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 219322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548080
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1244
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 15509
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15306
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 547454
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 6428295252 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 154519948340 (143.91 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67706.9 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743219
telemt_connections_bad_total 5983
telemt_handshake_timeouts_total 7018
telemt_upstream_connect_attempt_total 18462
telemt_upstream_connect_success_total 18388
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 18664
telemt_me_reconnect_success_total 14872
telemt_me_reader_eof_total 15728
telemt_me_idle_close_by_peer_total 15728
telemt_me_route_drop_no_conn_total 253203
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672987
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2899
telemt_desync_full_logged_total 1097
telemt_desync_suppressed_total 1802
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 690
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15180
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14872
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 672674
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 10738948167 (10.00 GB)
telemt_user_octets_to_client{user="hello"} 241765938218 (225.16 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 92
```