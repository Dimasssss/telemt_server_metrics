# Server Metrics 2026-03-12 20:22:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51809.8 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1789654
telemt_connections_bad_total 20721
telemt_handshake_timeouts_total 19480
telemt_upstream_connect_attempt_total 10093
telemt_upstream_connect_success_total 10034
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 581
telemt_me_reconnect_attempts_total 16261
telemt_me_reconnect_success_total 7413
telemt_me_reader_eof_total 8022
telemt_me_idle_close_by_peer_total 8021
telemt_me_route_drop_no_conn_total 705433
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1670500
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8214
telemt_desync_full_logged_total 2117
telemt_desync_suppressed_total 6097
telemt_desync_frames_bucket_total{bucket="1_2"} 2151
telemt_desync_frames_bucket_total{bucket="3_10"} 2960
telemt_desync_frames_bucket_total{bucket="gt_10"} 3103
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7796
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7400
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 1669988
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 25729225168 (23.96 GB)
telemt_user_octets_to_client{user="hello"} 575354561568 (535.84 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81430.4 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755026
telemt_connections_bad_total 10685
telemt_handshake_timeouts_total 30256
telemt_upstream_connect_attempt_total 20640
telemt_upstream_connect_success_total 20611
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 14971
telemt_me_reconnect_success_total 14882
telemt_me_reader_eof_total 15823
telemt_me_idle_close_by_peer_total 15823
telemt_me_route_drop_no_conn_total 242737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681167
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2931
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 2034
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15035
telemt_me_writer_restored_same_endpoint_total 14873
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 683039
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 11611333288 (10.81 GB)
telemt_user_octets_to_client{user="hello"} 258946353979 (241.16 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81430.2 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1559911
telemt_connections_bad_total 7535
telemt_handshake_timeouts_total 106685
telemt_upstream_connect_attempt_total 19152
telemt_upstream_connect_success_total 19146
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 15951
telemt_me_reconnect_success_total 14704
telemt_me_reader_eof_total 15518
telemt_me_idle_close_by_peer_total 15517
telemt_me_route_drop_no_conn_total 515771
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1201975
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4802
telemt_desync_full_logged_total 1479
telemt_desync_suppressed_total 3323
telemt_desync_frames_bucket_total{bucket="1_2"} 763
telemt_desync_frames_bucket_total{bucket="3_10"} 1737
telemt_desync_frames_bucket_total{bucket="gt_10"} 2302
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14841
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14663
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 1201586
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 19001368968 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 447722976253 (416.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81430.9 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958253
telemt_connections_bad_total 12968
telemt_handshake_timeouts_total 70554
telemt_upstream_connect_attempt_total 20819
telemt_upstream_connect_success_total 20737
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 20819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1670
telemt_me_reconnect_attempts_total 24386
telemt_me_reconnect_success_total 16660
telemt_me_reader_eof_total 17800
telemt_me_idle_close_by_peer_total 17800
telemt_me_route_drop_no_conn_total 341252
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1758
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1170
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 17036
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16639
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 830511
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 12994642980 (12.10 GB)
telemt_user_octets_to_client{user="hello"} 340477888616 (317.09 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81430.5 (22h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076243
telemt_connections_bad_total 12367
telemt_handshake_timeouts_total 8907
telemt_upstream_connect_attempt_total 25397
telemt_upstream_connect_success_total 25087
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 25397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 32030
telemt_me_reconnect_success_total 20992
telemt_me_reader_eof_total 22057
telemt_me_idle_close_by_peer_total 22057
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 402727
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987425
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3691
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 1053
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 1415
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 21576
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20948
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 987294
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 12332985020 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 344294930520 (320.65 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 68
```