# Server Metrics 2026-03-11 15:27:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90010.4 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2209421
telemt_connections_bad_total 37518
telemt_handshake_timeouts_total 52654
telemt_upstream_connect_attempt_total 18867
telemt_upstream_connect_success_total 18855
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4892
telemt_me_reconnect_attempts_total 32183
telemt_me_reconnect_success_total 14317
telemt_me_reader_eof_total 15541
telemt_me_idle_close_by_peer_total 15541
telemt_me_route_drop_no_conn_total 817787
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2021248
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10552
telemt_desync_full_logged_total 2864
telemt_desync_suppressed_total 7688
telemt_desync_frames_bucket_total{bucket="1_2"} 2624
telemt_desync_frames_bucket_total{bucket="3_10"} 4067
telemt_desync_frames_bucket_total{bucket="gt_10"} 3861
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15034
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14311
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2019710
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 27089863192 (25.23 GB)
telemt_user_octets_to_client{user="hello"} 573855176440 (534.44 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90067.3 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820569
telemt_connections_bad_total 13261
telemt_handshake_timeouts_total 55350
telemt_upstream_connect_attempt_total 28527
telemt_upstream_connect_success_total 25570
telemt_upstream_connect_fail_total 2956
telemt_upstream_connect_attempts_per_request{bucket="1"} 28526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2956
telemt_me_keepalive_timeout_total 2551
telemt_me_reconnect_attempts_total 20194
telemt_me_reconnect_success_total 18101
telemt_me_reader_eof_total 19161
telemt_me_idle_close_by_peer_total 19158
telemt_me_route_drop_no_conn_total 321660
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2885
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 954
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18364
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18078
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 700292
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 8081934998 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 198047954732 (184.45 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90067.1 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1425085
telemt_connections_bad_total 8659
telemt_handshake_timeouts_total 124082
telemt_upstream_connect_attempt_total 23746
telemt_upstream_connect_success_total 23463
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 23746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 36203
telemt_me_reconnect_success_total 17848
telemt_me_reader_eof_total 19225
telemt_me_idle_close_by_peer_total 19225
telemt_me_route_drop_no_conn_total 518115
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1240190
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3272
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2303
telemt_desync_frames_bucket_total{bucket="1_2"} 806
telemt_desync_frames_bucket_total{bucket="3_10"} 1238
telemt_desync_frames_bucket_total{bucket="gt_10"} 1228
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18665
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 17837
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 1239914
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 14924387517 (13.90 GB)
telemt_user_octets_to_client{user="hello"} 373792493605 (348.12 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90067.5 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1022662
telemt_connections_bad_total 77915
telemt_handshake_timeouts_total 99720
telemt_upstream_connect_attempt_total 24079
telemt_upstream_connect_success_total 24079
telemt_upstream_connect_attempts_per_request{bucket="1"} 24079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1010
telemt_me_reconnect_attempts_total 20649
telemt_me_reconnect_success_total 19574
telemt_me_reader_eof_total 20763
telemt_me_idle_close_by_peer_total 20762
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 334027
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816820
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1715
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1055
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19815
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19545
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 816145
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 9737329988 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 241053386024 (224.50 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90067.3 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129983
telemt_connections_bad_total 6937
telemt_handshake_timeouts_total 11377
telemt_upstream_connect_attempt_total 24340
telemt_upstream_connect_success_total 24231
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 24340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1948
telemt_me_reconnect_attempts_total 23682
telemt_me_reconnect_success_total 19594
telemt_me_reader_eof_total 20664
telemt_me_idle_close_by_peer_total 20664
telemt_me_route_drop_no_conn_total 402666
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1027423
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3975
telemt_desync_full_logged_total 1443
telemt_desync_suppressed_total 2532
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 1487
telemt_desync_frames_bucket_total{bucket="gt_10"} 1136
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19975
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19594
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 1027135
telemt_user_connections_current{user="hello"} 772
telemt_user_octets_from_client{user="hello"} 14522235803 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 360400150562 (335.65 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 111
```