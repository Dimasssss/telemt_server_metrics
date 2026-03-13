# Server Metrics 2026-03-13 02:44:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74760.4 (20h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2100400
telemt_connections_bad_total 27845
telemt_handshake_timeouts_total 22363
telemt_upstream_connect_attempt_total 14795
telemt_upstream_connect_success_total 14712
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 19838
telemt_me_reconnect_success_total 10977
telemt_me_reader_eof_total 11854
telemt_me_idle_close_by_peer_total 11853
telemt_me_route_drop_no_conn_total 809020
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1936277
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8717
telemt_desync_full_logged_total 2269
telemt_desync_suppressed_total 6448
telemt_desync_frames_bucket_total{bucket="1_2"} 2298
telemt_desync_frames_bucket_total{bucket="3_10"} 3145
telemt_desync_frames_bucket_total{bucket="gt_10"} 3274
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11407
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10964
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1935734
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 28166764624 (26.23 GB)
telemt_user_octets_to_client{user="hello"} 672724675852 (626.52 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104380.9 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856868
telemt_connections_bad_total 11818
telemt_handshake_timeouts_total 32882
telemt_upstream_connect_attempt_total 26565
telemt_upstream_connect_success_total 26536
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3456
telemt_me_reconnect_attempts_total 19818
telemt_me_reconnect_success_total 19709
telemt_me_reader_eof_total 20997
telemt_me_idle_close_by_peer_total 20997
telemt_me_route_drop_no_conn_total 275565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3100
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2126
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 19903
telemt_me_writer_restored_same_endpoint_total 19700
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 778763
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 12381500832 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 293092836031 (272.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104380.7 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1777794
telemt_connections_bad_total 9226
telemt_handshake_timeouts_total 119035
telemt_upstream_connect_attempt_total 24326
telemt_upstream_connect_success_total 24316
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1606
telemt_me_reconnect_attempts_total 20043
telemt_me_reconnect_success_total 18779
telemt_me_reader_eof_total 19887
telemt_me_idle_close_by_peer_total 19886
telemt_me_route_drop_no_conn_total 579269
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400155
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5022
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3484
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18955
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18738
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1399749
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 20234410056 (18.84 GB)
telemt_user_octets_to_client{user="hello"} 503926505833 (469.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104381.1 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1109576
telemt_connections_bad_total 13138
telemt_handshake_timeouts_total 73354
telemt_upstream_connect_attempt_total 36447
telemt_upstream_connect_success_total 34174
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 36173
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11363
telemt_me_reconnect_attempts_total 32049
telemt_me_reconnect_success_total 23124
telemt_me_reader_eof_total 24968
telemt_me_idle_close_by_peer_total 24961
telemt_me_route_drop_no_conn_total 393528
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951589
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1899
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1269
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23554
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23100
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 956759
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 14607633145 (13.60 GB)
telemt_user_octets_to_client{user="hello"} 375808667710 (350.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 104381.0 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227478
telemt_connections_bad_total 12630
telemt_handshake_timeouts_total 9553
telemt_upstream_connect_attempt_total 32994
telemt_upstream_connect_success_total 32591
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 32994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 1896
telemt_me_reconnect_attempts_total 41137
telemt_me_reconnect_success_total 27407
telemt_me_reader_eof_total 28836
telemt_me_idle_close_by_peer_total 28836
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 458711
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135235
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4225
telemt_desync_full_logged_total 1499
telemt_desync_suppressed_total 2726
telemt_desync_frames_bucket_total{bucket="1_2"} 1272
telemt_desync_frames_bucket_total{bucket="3_10"} 1392
telemt_desync_frames_bucket_total{bucket="gt_10"} 1561
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 28149
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27358
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 1135090
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 14024703512 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 393251746924 (366.24 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 42
```