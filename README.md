# Server Metrics 2026-03-13 13:02:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111857.8 (31h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3355417
telemt_connections_bad_total 37362
telemt_handshake_timeouts_total 58108
telemt_upstream_connect_attempt_total 22026
telemt_upstream_connect_success_total 21903
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 26404
telemt_me_reconnect_success_total 16321
telemt_me_reader_eof_total 17547
telemt_me_idle_close_by_peer_total 17546
telemt_me_route_drop_no_conn_total 1244151
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3077599
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12896
telemt_desync_full_logged_total 3357
telemt_desync_suppressed_total 9539
telemt_desync_frames_bucket_total{bucket="1_2"} 3277
telemt_desync_frames_bucket_total{bucket="3_10"} 4876
telemt_desync_frames_bucket_total{bucket="gt_10"} 4743
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16864
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16308
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 3077500
telemt_user_connections_current{user="hello"} 1964
telemt_user_octets_from_client{user="hello"} 42667037760 (39.74 GB)
telemt_user_octets_to_client{user="hello"} 991069099276 (923.01 GB)
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11521.6 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157521
telemt_connections_bad_total 9028
telemt_handshake_timeouts_total 3708
telemt_upstream_connect_attempt_total 2795
telemt_upstream_connect_success_total 2721
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 2795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 2104
telemt_me_reader_eof_total 2210
telemt_me_idle_close_by_peer_total 2210
telemt_me_route_drop_no_conn_total 56523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140966
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 484
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2159
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2097
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 140991
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 1408952212 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 38007044908 (35.40 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 141478.3 (39h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2533152
telemt_connections_bad_total 26591
telemt_handshake_timeouts_total 166091
telemt_upstream_connect_attempt_total 32158
telemt_upstream_connect_success_total 32148
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3183
telemt_me_reconnect_attempts_total 27290
telemt_me_reconnect_success_total 24744
telemt_me_reader_eof_total 26235
telemt_me_idle_close_by_peer_total 26234
telemt_me_route_drop_no_conn_total 848685
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061504
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7005
telemt_desync_full_logged_total 2280
telemt_desync_suppressed_total 4725
telemt_desync_frames_bucket_total{bucket="1_2"} 1109
telemt_desync_frames_bucket_total{bucket="3_10"} 2560
telemt_desync_frames_bucket_total{bucket="gt_10"} 3336
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 25030
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24703
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 2060913
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 34645599008 (32.27 GB)
telemt_user_octets_to_client{user="hello"} 742686150521 (691.68 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 141478.7 (39h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1616217
telemt_connections_bad_total 17877
telemt_handshake_timeouts_total 113663
telemt_upstream_connect_attempt_total 45505
telemt_upstream_connect_success_total 43185
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45231
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11829
telemt_me_reconnect_attempts_total 39234
telemt_me_reconnect_success_total 30268
telemt_me_reader_eof_total 32550
telemt_me_idle_close_by_peer_total 32543
telemt_me_route_drop_no_conn_total 575232
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1349204
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2672
telemt_desync_full_logged_total 872
telemt_desync_suppressed_total 1800
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1093
telemt_desync_frames_bucket_total{bucket="gt_10"} 865
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 30772
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30244
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 1353925
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 20530796005 (19.12 GB)
telemt_user_octets_to_client{user="hello"} 528403075638 (492.11 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10914.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167463
telemt_connections_bad_total 3663
telemt_handshake_timeouts_total 1514
telemt_upstream_connect_attempt_total 2225
telemt_upstream_connect_success_total 2149
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 2225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 9614
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_route_drop_no_conn_total 64493
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156299
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1787
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1537
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 156282
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 1742932996 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 49718416560 (46.30 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 160
```