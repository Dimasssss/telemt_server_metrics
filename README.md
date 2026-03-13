# Server Metrics 2026-03-13 06:39:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 88842.8 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2399595
telemt_connections_bad_total 36044
telemt_handshake_timeouts_total 25648
telemt_upstream_connect_attempt_total 17409
telemt_upstream_connect_success_total 17312
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1326
telemt_me_reconnect_attempts_total 21769
telemt_me_reconnect_success_total 12898
telemt_me_reader_eof_total 13913
telemt_me_idle_close_by_peer_total 13912
telemt_me_route_drop_no_conn_total 909667
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2208366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9950
telemt_desync_full_logged_total 2559
telemt_desync_suppressed_total 7391
telemt_desync_frames_bucket_total{bucket="1_2"} 2546
telemt_desync_frames_bucket_total{bucket="3_10"} 3659
telemt_desync_frames_bucket_total{bucket="gt_10"} 3745
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13356
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12885
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2207826
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 31893495108 (29.70 GB)
telemt_user_octets_to_client{user="hello"} 749001715792 (697.56 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 118463.2 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964957
telemt_connections_bad_total 12525
telemt_handshake_timeouts_total 41431
telemt_upstream_connect_attempt_total 29808
telemt_upstream_connect_success_total 29777
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3577
telemt_me_reconnect_attempts_total 22368
telemt_me_reconnect_success_total 22249
telemt_me_reader_eof_total 23725
telemt_me_idle_close_by_peer_total 23725
telemt_me_route_drop_no_conn_total 307474
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871985
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3631
telemt_desync_full_logged_total 1127
telemt_desync_suppressed_total 2504
telemt_desync_frames_bucket_total{bucket="1_2"} 1395
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 1059
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 22469
telemt_me_writer_restored_same_endpoint_total 22240
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 873900
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 13674276572 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 330789111995 (308.07 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 118463.2 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1991876
telemt_connections_bad_total 22828
telemt_handshake_timeouts_total 133800
telemt_upstream_connect_attempt_total 27410
telemt_upstream_connect_success_total 27400
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1685
telemt_me_reconnect_attempts_total 22433
telemt_me_reconnect_success_total 21159
telemt_me_reader_eof_total 22414
telemt_me_idle_close_by_peer_total 22413
telemt_me_route_drop_no_conn_total 637231
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1570607
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5420
telemt_desync_full_logged_total 1642
telemt_desync_suppressed_total 3778
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1971
telemt_desync_frames_bucket_total{bucket="gt_10"} 2557
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21363
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21118
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 1570102
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 26718064592 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 556279054589 (518.08 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 118463.5 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214808
telemt_connections_bad_total 13998
telemt_handshake_timeouts_total 78587
telemt_upstream_connect_attempt_total 40207
telemt_upstream_connect_success_total 37917
telemt_upstream_connect_fail_total 2153
telemt_upstream_connect_attempts_per_request{bucket="1"} 39933
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2152
telemt_me_keepalive_timeout_total 11422
telemt_me_reconnect_attempts_total 35099
telemt_me_reconnect_success_total 26164
telemt_me_reader_eof_total 28203
telemt_me_idle_close_by_peer_total 28196
telemt_me_route_drop_no_conn_total 435078
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044577
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2076
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 705
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 26624
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26140
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 1049496
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 16090644577 (14.99 GB)
telemt_user_octets_to_client{user="hello"} 418176244830 (389.46 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 118463.2 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371523
telemt_connections_bad_total 19862
telemt_handshake_timeouts_total 11212
telemt_upstream_connect_attempt_total 37482
telemt_upstream_connect_success_total 37026
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 37482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_keepalive_timeout_total 2036
telemt_me_reconnect_attempts_total 44876
telemt_me_reconnect_success_total 31139
telemt_me_reader_eof_total 32691
telemt_me_idle_close_by_peer_total 32691
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 503904
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1264702
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 46
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4529
telemt_desync_full_logged_total 1626
telemt_desync_suppressed_total 2903
telemt_desync_frames_bucket_total{bucket="1_2"} 1372
telemt_desync_frames_bucket_total{bucket="3_10"} 1474
telemt_desync_frames_bucket_total{bucket="gt_10"} 1683
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 31908
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31085
telemt_me_writer_restored_fallback_total 54
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1264543
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 15266202820 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 435777693340 (405.85 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 90
```