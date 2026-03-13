# Server Metrics 2026-03-13 12:57:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111552.0 (30h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3340948
telemt_connections_bad_total 37361
telemt_handshake_timeouts_total 57938
telemt_upstream_connect_attempt_total 21934
telemt_upstream_connect_success_total 21813
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2106
telemt_me_reconnect_attempts_total 26357
telemt_me_reconnect_success_total 16274
telemt_me_reader_eof_total 17496
telemt_me_idle_close_by_peer_total 17495
telemt_me_route_drop_no_conn_total 1238165
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3063645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12865
telemt_desync_full_logged_total 3346
telemt_desync_suppressed_total 9519
telemt_desync_frames_bucket_total{bucket="1_2"} 3269
telemt_desync_frames_bucket_total{bucket="3_10"} 4865
telemt_desync_frames_bucket_total{bucket="gt_10"} 4731
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16817
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16261
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 3063544
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 42516318524 (39.60 GB)
telemt_user_octets_to_client{user="hello"} 987877053388 (920.03 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11216.0 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153243
telemt_connections_bad_total 9026
telemt_handshake_timeouts_total 3625
telemt_upstream_connect_attempt_total 2748
telemt_upstream_connect_success_total 2674
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3285
telemt_me_reconnect_success_total 2057
telemt_me_reader_eof_total 2163
telemt_me_idle_close_by_peer_total 2163
telemt_me_route_drop_no_conn_total 54771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136868
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 329
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2112
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2050
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 136893
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 1371104112 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 36903046020 (34.37 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 141172.7 (39h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2524709
telemt_connections_bad_total 26336
telemt_handshake_timeouts_total 165930
telemt_upstream_connect_attempt_total 32071
telemt_upstream_connect_success_total 32061
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3182
telemt_me_reconnect_attempts_total 27246
telemt_me_reconnect_success_total 24700
telemt_me_reader_eof_total 26185
telemt_me_idle_close_by_peer_total 26184
telemt_me_route_drop_no_conn_total 845130
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2053792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6949
telemt_desync_full_logged_total 2250
telemt_desync_suppressed_total 4699
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 2545
telemt_desync_frames_bucket_total{bucket="gt_10"} 3306
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 24986
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24659
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 2053203
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 34574849100 (32.20 GB)
telemt_user_octets_to_client{user="hello"} 740134836397 (689.30 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 141173.2 (39h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610616
telemt_connections_bad_total 17875
telemt_handshake_timeouts_total 113339
telemt_upstream_connect_attempt_total 45414
telemt_upstream_connect_success_total 43094
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45140
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11829
telemt_me_reconnect_attempts_total 39186
telemt_me_reconnect_success_total 30221
telemt_me_reader_eof_total 32498
telemt_me_idle_close_by_peer_total 32491
telemt_me_route_drop_no_conn_total 572763
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1344107
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2648
telemt_desync_full_logged_total 865
telemt_desync_suppressed_total 1783
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 863
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 30725
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30197
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1348828
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 20492678221 (19.09 GB)
telemt_user_octets_to_client{user="hello"} 526472856770 (490.32 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10608.6 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161185
telemt_connections_bad_total 3396
telemt_handshake_timeouts_total 1467
telemt_upstream_connect_attempt_total 2159
telemt_upstream_connect_success_total 2085
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 9593
telemt_me_reconnect_success_total 1520
telemt_me_reader_eof_total 1764
telemt_me_idle_close_by_peer_total 1764
telemt_me_route_drop_no_conn_total 61778
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 539
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1766
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 150529
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 1690750328 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 47934991164 (44.64 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 113
```