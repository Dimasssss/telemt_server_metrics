# Server Metrics 2026-03-13 12:42:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110635.2 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3302556
telemt_connections_bad_total 37018
telemt_handshake_timeouts_total 57494
telemt_upstream_connect_attempt_total 21799
telemt_upstream_connect_success_total 21679
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 2104
telemt_me_reconnect_attempts_total 26266
telemt_me_reconnect_success_total 16184
telemt_me_reader_eof_total 17398
telemt_me_idle_close_by_peer_total 17397
telemt_me_route_drop_no_conn_total 1224070
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3027205
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12756
telemt_desync_full_logged_total 3313
telemt_desync_suppressed_total 9443
telemt_desync_frames_bucket_total{bucket="1_2"} 3252
telemt_desync_frames_bucket_total{bucket="3_10"} 4810
telemt_desync_frames_bucket_total{bucket="gt_10"} 4694
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16723
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16171
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 3027106
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 42071408996 (39.18 GB)
telemt_user_octets_to_client{user="hello"} 977138872128 (910.03 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10299.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140299
telemt_connections_bad_total 8254
telemt_handshake_timeouts_total 3322
telemt_upstream_connect_attempt_total 2571
telemt_upstream_connect_success_total 2497
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3151
telemt_me_reconnect_success_total 1925
telemt_me_reader_eof_total 2020
telemt_me_idle_close_by_peer_total 2020
telemt_me_route_drop_no_conn_total 49836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125216
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 320
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1975
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 125241
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 1228929560 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 33874144580 (31.55 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 140255.8 (38h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2502009
telemt_connections_bad_total 26318
telemt_handshake_timeouts_total 164691
telemt_upstream_connect_attempt_total 31910
telemt_upstream_connect_success_total 31900
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3179
telemt_me_reconnect_attempts_total 27128
telemt_me_reconnect_success_total 24582
telemt_me_reader_eof_total 26057
telemt_me_idle_close_by_peer_total 26056
telemt_me_route_drop_no_conn_total 836253
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2032693
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6846
telemt_desync_full_logged_total 2212
telemt_desync_suppressed_total 4634
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 2509
telemt_desync_frames_bucket_total{bucket="gt_10"} 3261
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 24864
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24541
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 2032106
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 34348834296 (31.99 GB)
telemt_user_octets_to_client{user="hello"} 731727075705 (681.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 140256.3 (38h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596048
telemt_connections_bad_total 17870
telemt_handshake_timeouts_total 112485
telemt_upstream_connect_attempt_total 45234
telemt_upstream_connect_success_total 42914
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 44960
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11826
telemt_me_reconnect_attempts_total 39049
telemt_me_reconnect_success_total 30085
telemt_me_reader_eof_total 32352
telemt_me_idle_close_by_peer_total 32345
telemt_me_route_drop_no_conn_total 566450
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330560
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2603
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1751
telemt_desync_frames_bucket_total{bucket="1_2"} 701
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 30587
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30061
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 1335283
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 19865854925 (18.50 GB)
telemt_user_octets_to_client{user="hello"} 520811643646 (485.04 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9691.7 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143208
telemt_connections_bad_total 1520
telemt_handshake_timeouts_total 1225
telemt_upstream_connect_attempt_total 1962
telemt_upstream_connect_success_total 1890
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 1962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 9441
telemt_me_reconnect_success_total 1370
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 56178
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135312
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 513
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1616
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1366
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 135306
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 1523010260 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 44324350452 (41.28 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 101
```