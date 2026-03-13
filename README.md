# Server Metrics 2026-03-13 01:02:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68644.3 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2017111
telemt_connections_bad_total 26123
telemt_handshake_timeouts_total 21518
telemt_upstream_connect_attempt_total 13650
telemt_upstream_connect_success_total 13571
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 1247
telemt_me_reconnect_attempts_total 18979
telemt_me_reconnect_success_total 10120
telemt_me_reader_eof_total 10949
telemt_me_idle_close_by_peer_total 10948
telemt_me_route_drop_no_conn_total 787694
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1876757
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8674
telemt_desync_full_logged_total 2259
telemt_desync_suppressed_total 6415
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3126
telemt_desync_frames_bucket_total{bucket="gt_10"} 3260
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10539
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10107
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 1876214
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 27589020968 (25.69 GB)
telemt_user_octets_to_client{user="hello"} 658151877684 (612.95 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98264.9 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830936
telemt_connections_bad_total 11757
telemt_handshake_timeouts_total 31946
telemt_upstream_connect_attempt_total 25049
telemt_upstream_connect_success_total 25020
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3441
telemt_me_reconnect_attempts_total 18560
telemt_me_reconnect_success_total 18457
telemt_me_reader_eof_total 19657
telemt_me_idle_close_by_peer_total 19657
telemt_me_route_drop_no_conn_total 268568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 752497
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3056
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2098
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 18637
telemt_me_writer_restored_same_endpoint_total 18448
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 754400
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 12216482880 (11.38 GB)
telemt_user_octets_to_client{user="hello"} 285770742767 (266.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98264.7 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1729074
telemt_connections_bad_total 8956
telemt_handshake_timeouts_total 114012
telemt_upstream_connect_attempt_total 22846
telemt_upstream_connect_success_total 22836
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1580
telemt_me_reconnect_attempts_total 18824
telemt_me_reconnect_success_total 17562
telemt_me_reader_eof_total 18598
telemt_me_idle_close_by_peer_total 18597
telemt_me_route_drop_no_conn_total 567211
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1357401
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17732
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17521
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 1357001
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 20002126736 (18.63 GB)
telemt_user_octets_to_client{user="hello"} 493842671909 (459.93 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98265.0 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084220
telemt_connections_bad_total 13090
telemt_handshake_timeouts_total 72347
telemt_upstream_connect_attempt_total 34246
telemt_upstream_connect_success_total 31981
telemt_upstream_connect_fail_total 2128
telemt_upstream_connect_attempts_per_request{bucket="1"} 33972
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2127
telemt_me_keepalive_timeout_total 11268
telemt_me_reconnect_attempts_total 29044
telemt_me_reconnect_success_total 21203
telemt_me_reader_eof_total 22945
telemt_me_idle_close_by_peer_total 22938
telemt_me_route_drop_no_conn_total 382950
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928723
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21581
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21181
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 933914
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 14431342397 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 368240391498 (342.95 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 98265.0 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193488
telemt_connections_bad_total 12582
telemt_handshake_timeouts_total 9360
telemt_upstream_connect_attempt_total 29741
telemt_upstream_connect_success_total 29366
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 29741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 1837
telemt_me_reconnect_attempts_total 35491
telemt_me_reconnect_success_total 24444
telemt_me_reader_eof_total 25729
telemt_me_idle_close_by_peer_total 25729
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 447250
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102132
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4125
telemt_desync_full_logged_total 1457
telemt_desync_suppressed_total 2668
telemt_desync_frames_bucket_total{bucket="1_2"} 1221
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1530
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 25074
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24398
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 1101988
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 13683077788 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 381714263420 (355.50 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 38
```