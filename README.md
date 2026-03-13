# Server Metrics 2026-03-13 14:39:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 117667.2 (32h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3617825
telemt_connections_bad_total 37400
telemt_handshake_timeouts_total 69011
telemt_upstream_connect_attempt_total 22974
telemt_upstream_connect_success_total 22846
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2164
telemt_me_reconnect_attempts_total 27089
telemt_me_reconnect_success_total 17003
telemt_me_reader_eof_total 18279
telemt_me_idle_close_by_peer_total 18278
telemt_me_route_drop_no_conn_total 1340662
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3315201
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13584
telemt_desync_full_logged_total 3568
telemt_desync_suppressed_total 10016
telemt_desync_frames_bucket_total{bucket="1_2"} 3447
telemt_desync_frames_bucket_total{bucket="3_10"} 5146
telemt_desync_frames_bucket_total{bucket="gt_10"} 4991
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17555
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16990
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 3314918
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 45427587396 (42.31 GB)
telemt_user_octets_to_client{user="hello"} 1049153254296 (977.10 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17331.0 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244425
telemt_connections_bad_total 13928
telemt_handshake_timeouts_total 5953
telemt_upstream_connect_attempt_total 4256
telemt_upstream_connect_success_total 4176
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5538
telemt_me_reconnect_success_total 3248
telemt_me_reader_eof_total 3445
telemt_me_idle_close_by_peer_total 3445
telemt_me_route_drop_no_conn_total 88632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218156
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 866
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 655
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3354
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3241
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 218181
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 2262232016 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 62240936904 (57.97 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 147287.9 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2693712
telemt_connections_bad_total 27315
telemt_handshake_timeouts_total 178981
telemt_upstream_connect_attempt_total 33177
telemt_upstream_connect_success_total 33167
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3243
telemt_me_reconnect_attempts_total 28051
telemt_me_reconnect_success_total 25504
telemt_me_reader_eof_total 27042
telemt_me_idle_close_by_peer_total 27041
telemt_me_route_drop_no_conn_total 907305
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2203885
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7927
telemt_desync_full_logged_total 2583
telemt_desync_suppressed_total 5344
telemt_desync_frames_bucket_total{bucket="1_2"} 1253
telemt_desync_frames_bucket_total{bucket="3_10"} 2891
telemt_desync_frames_bucket_total{bucket="gt_10"} 3783
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 25801
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25463
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2203271
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 36620010436 (34.11 GB)
telemt_user_octets_to_client{user="hello"} 780913577805 (727.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 147288.0 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1715461
telemt_connections_bad_total 18075
telemt_handshake_timeouts_total 124517
telemt_upstream_connect_attempt_total 46619
telemt_upstream_connect_success_total 44292
telemt_upstream_connect_fail_total 2190
telemt_upstream_connect_attempts_per_request{bucket="1"} 46345
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11846
telemt_me_reconnect_attempts_total 40081
telemt_me_reconnect_success_total 31112
telemt_me_reader_eof_total 33448
telemt_me_idle_close_by_peer_total 33441
telemt_me_route_drop_no_conn_total 613381
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2888
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 1956
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 1204
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 31626
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31088
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 1440075
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 22511007489 (20.97 GB)
telemt_user_octets_to_client{user="hello"} 553897207142 (515.86 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16724.0 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264272
telemt_connections_bad_total 3908
telemt_handshake_timeouts_total 2560
telemt_upstream_connect_attempt_total 3549
telemt_upstream_connect_success_total 3437
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 3549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 10641
telemt_me_reconnect_success_total 2564
telemt_me_reader_eof_total 2846
telemt_me_idle_close_by_peer_total 2846
telemt_me_route_drop_no_conn_total 103724
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246642
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 800
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2823
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2560
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 246624
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 2730893676 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 80938507104 (75.38 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 93
```