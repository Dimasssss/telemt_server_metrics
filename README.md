# Server Metrics 2026-03-11 17:04:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95831.0 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2402538
telemt_connections_bad_total 43701
telemt_handshake_timeouts_total 54280
telemt_upstream_connect_attempt_total 20116
telemt_upstream_connect_success_total 20104
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5090
telemt_me_reconnect_attempts_total 33122
telemt_me_reconnect_success_total 15245
telemt_me_reader_eof_total 16513
telemt_me_idle_close_by_peer_total 16513
telemt_me_route_drop_no_conn_total 892919
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2197364
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11362
telemt_desync_full_logged_total 3106
telemt_desync_suppressed_total 8256
telemt_desync_frames_bucket_total{bucket="1_2"} 2804
telemt_desync_frames_bucket_total{bucket="3_10"} 4384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4174
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15975
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15239
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 2195810
telemt_user_connections_current{user="hello"} 1307
telemt_user_octets_from_client{user="hello"} 29462094908 (27.44 GB)
telemt_user_octets_to_client{user="hello"} 619294442092 (576.76 GB)
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95887.8 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 902685
telemt_connections_bad_total 15723
telemt_handshake_timeouts_total 76320
telemt_upstream_connect_attempt_total 30246
telemt_upstream_connect_success_total 27286
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 30246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2663
telemt_me_reconnect_attempts_total 21615
telemt_me_reconnect_success_total 19513
telemt_me_reader_eof_total 20649
telemt_me_idle_close_by_peer_total 20646
telemt_me_route_drop_no_conn_total 344253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3033
telemt_desync_full_logged_total 966
telemt_desync_suppressed_total 2067
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1023
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19788
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19490
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 757479
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 8698404150 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 214355651816 (199.63 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 95887.8 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1540348
telemt_connections_bad_total 8994
telemt_handshake_timeouts_total 126232
telemt_upstream_connect_attempt_total 24816
telemt_upstream_connect_success_total 24498
telemt_upstream_connect_fail_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 24816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 318
telemt_me_keepalive_timeout_total 1756
telemt_me_reconnect_attempts_total 42337
telemt_me_reconnect_success_total 18576
telemt_me_reader_eof_total 20139
telemt_me_idle_close_by_peer_total 20139
telemt_me_route_drop_no_conn_total 562338
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1347060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3520
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 2484
telemt_desync_frames_bucket_total{bucket="1_2"} 867
telemt_desync_frames_bucket_total{bucket="3_10"} 1327
telemt_desync_frames_bucket_total{bucket="gt_10"} 1326
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19574
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18564
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 998
telemt_user_connections_total{user="hello"} 1346758
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 16549773797 (15.41 GB)
telemt_user_octets_to_client{user="hello"} 409031237621 (380.94 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 95888.2 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106724
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 105687
telemt_upstream_connect_attempt_total 25848
telemt_upstream_connect_success_total 25848
telemt_upstream_connect_attempts_per_request{bucket="1"} 25848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1169
telemt_me_reconnect_attempts_total 23192
telemt_me_reconnect_success_total 21056
telemt_me_reader_eof_total 22337
telemt_me_idle_close_by_peer_total 22336
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 364498
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1849
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 537
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21347
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21025
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 889080
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 10729017496 (9.99 GB)
telemt_user_octets_to_client{user="hello"} 266474473668 (248.17 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 564.2 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10827
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 150
telemt_upstream_connect_success_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 41
telemt_me_idle_close_by_peer_total 41
telemt_me_route_drop_no_conn_total 2865
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10098
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 18
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 63
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 10099
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 82022184 (78.22 MB)
telemt_user_octets_to_client{user="hello"} 2534655524 (2.36 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 112
```