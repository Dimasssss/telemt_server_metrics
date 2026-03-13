# Server Metrics 2026-03-13 07:55:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93436.1 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2586058
telemt_connections_bad_total 36172
telemt_handshake_timeouts_total 27188
telemt_upstream_connect_attempt_total 18182
telemt_upstream_connect_success_total 18081
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1365
telemt_me_reconnect_attempts_total 22323
telemt_me_reconnect_success_total 13450
telemt_me_reader_eof_total 14498
telemt_me_idle_close_by_peer_total 14497
telemt_me_route_drop_no_conn_total 966739
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2365020
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10661
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 7911
telemt_desync_frames_bucket_total{bucket="1_2"} 2715
telemt_desync_frames_bucket_total{bucket="3_10"} 3956
telemt_desync_frames_bucket_total{bucket="gt_10"} 3990
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 13914
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13437
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2364510
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 33650657888 (31.34 GB)
telemt_user_octets_to_client{user="hello"} 793097495004 (738.63 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 123056.8 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046650
telemt_connections_bad_total 13421
telemt_handshake_timeouts_total 70281
telemt_upstream_connect_attempt_total 30806
telemt_upstream_connect_success_total 30775
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3625
telemt_me_reconnect_attempts_total 23149
telemt_me_reconnect_success_total 23029
telemt_me_reader_eof_total 24545
telemt_me_idle_close_by_peer_total 24545
telemt_me_route_drop_no_conn_total 326167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921895
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4062
telemt_desync_full_logged_total 1244
telemt_desync_suppressed_total 2818
telemt_desync_frames_bucket_total{bucket="1_2"} 1525
telemt_desync_frames_bucket_total{bucket="3_10"} 1316
telemt_desync_frames_bucket_total{bucket="gt_10"} 1221
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 23256
telemt_me_writer_restored_same_endpoint_total 23020
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 923821
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 14195226896 (13.22 GB)
telemt_user_octets_to_client{user="hello"} 345065147899 (321.37 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 123056.6 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2083627
telemt_connections_bad_total 23395
telemt_handshake_timeouts_total 139852
telemt_upstream_connect_attempt_total 28258
telemt_upstream_connect_success_total 28248
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1740
telemt_me_reconnect_attempts_total 23065
telemt_me_reconnect_success_total 21786
telemt_me_reader_eof_total 23080
telemt_me_idle_close_by_peer_total 23079
telemt_me_route_drop_no_conn_total 671655
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1654039
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5589
telemt_desync_full_logged_total 1740
telemt_desync_suppressed_total 3849
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 2035
telemt_desync_frames_bucket_total{bucket="gt_10"} 2633
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 21998
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21745
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 1653517
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 27547243180 (25.66 GB)
telemt_user_octets_to_client{user="hello"} 601198158141 (559.91 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 123057.1 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1294979
telemt_connections_bad_total 14148
telemt_handshake_timeouts_total 81967
telemt_upstream_connect_attempt_total 41347
telemt_upstream_connect_success_total 39049
telemt_upstream_connect_fail_total 2161
telemt_upstream_connect_attempts_per_request{bucket="1"} 41073
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2160
telemt_me_keepalive_timeout_total 11440
telemt_me_reconnect_attempts_total 36014
telemt_me_reconnect_success_total 27076
telemt_me_reader_eof_total 29157
telemt_me_idle_close_by_peer_total 29150
telemt_me_route_drop_no_conn_total 463649
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1101338
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2167
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1463
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27544
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27052
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 1106081
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 16768339397 (15.62 GB)
telemt_user_octets_to_client{user="hello"} 438708657318 (408.58 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 123056.6 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453423
telemt_connections_bad_total 26970
telemt_handshake_timeouts_total 12185
telemt_upstream_connect_attempt_total 38802
telemt_upstream_connect_success_total 38331
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2124
telemt_me_reconnect_attempts_total 45965
telemt_me_reconnect_success_total 32226
telemt_me_reader_eof_total 33829
telemt_me_idle_close_by_peer_total 33829
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 533344
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1335905
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4720
telemt_desync_full_logged_total 1683
telemt_desync_suppressed_total 3037
telemt_desync_frames_bucket_total{bucket="1_2"} 1442
telemt_desync_frames_bucket_total{bucket="3_10"} 1516
telemt_desync_frames_bucket_total{bucket="gt_10"} 1762
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33008
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32170
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1335713
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 16930254412 (15.77 GB)
telemt_user_octets_to_client{user="hello"} 458085996696 (426.63 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 95
```