# Server Metrics 2026-03-13 09:12:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98030.0 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2781434
telemt_connections_bad_total 36388
telemt_handshake_timeouts_total 38377
telemt_upstream_connect_attempt_total 19244
telemt_upstream_connect_success_total 19139
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 19244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1393
telemt_me_reconnect_attempts_total 24346
telemt_me_reconnect_success_total 14285
telemt_me_reader_eof_total 15392
telemt_me_idle_close_by_peer_total 15391
telemt_me_route_drop_no_conn_total 1032954
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2542399
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11246
telemt_desync_full_logged_total 2908
telemt_desync_suppressed_total 8338
telemt_desync_frames_bucket_total{bucket="1_2"} 2888
telemt_desync_frames_bucket_total{bucket="3_10"} 4210
telemt_desync_frames_bucket_total{bucket="gt_10"} 4148
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14796
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14272
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 2541969
telemt_user_connections_current{user="hello"} 1729
telemt_user_octets_from_client{user="hello"} 35570370816 (33.13 GB)
telemt_user_octets_to_client{user="hello"} 834102667320 (776.82 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 127650.5 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140426
telemt_connections_bad_total 14236
telemt_handshake_timeouts_total 105399
telemt_upstream_connect_attempt_total 31699
telemt_upstream_connect_success_total 31668
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23822
telemt_me_reconnect_success_total 23697
telemt_me_reader_eof_total 25258
telemt_me_idle_close_by_peer_total 25258
telemt_me_route_drop_no_conn_total 349317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 979449
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4340
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 3023
telemt_desync_frames_bucket_total{bucket="1_2"} 1584
telemt_desync_frames_bucket_total{bucket="3_10"} 1429
telemt_desync_frames_bucket_total{bucket="gt_10"} 1327
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 23929
telemt_me_writer_restored_same_endpoint_total 23688
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 981376
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 14950904440 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 360646311935 (335.88 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 127650.5 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2191966
telemt_connections_bad_total 24636
telemt_handshake_timeouts_total 146251
telemt_upstream_connect_attempt_total 29264
telemt_upstream_connect_success_total 29254
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1806
telemt_me_reconnect_attempts_total 23850
telemt_me_reconnect_success_total 22565
telemt_me_reader_eof_total 23903
telemt_me_idle_close_by_peer_total 23902
telemt_me_route_drop_no_conn_total 712609
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1750822
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5837
telemt_desync_full_logged_total 1858
telemt_desync_suppressed_total 3979
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 2130
telemt_desync_frames_bucket_total{bucket="gt_10"} 2753
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22788
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22524
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 1750257
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 30609785912 (28.51 GB)
telemt_user_octets_to_client{user="hello"} 633346583789 (589.85 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 127650.8 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391044
telemt_connections_bad_total 14228
telemt_handshake_timeouts_total 85431
telemt_upstream_connect_attempt_total 42237
telemt_upstream_connect_success_total 39933
telemt_upstream_connect_fail_total 2167
telemt_upstream_connect_attempts_per_request{bucket="1"} 41963
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2166
telemt_me_keepalive_timeout_total 11462
telemt_me_reconnect_attempts_total 36680
telemt_me_reconnect_success_total 27739
telemt_me_reader_eof_total 29869
telemt_me_idle_close_by_peer_total 29862
telemt_me_route_drop_no_conn_total 489061
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159382
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2200
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28215
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27715
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 1164145
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 17519842225 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 462448740350 (430.69 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 127650.6 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1545118
telemt_connections_bad_total 34021
telemt_handshake_timeouts_total 12681
telemt_upstream_connect_attempt_total 40757
telemt_upstream_connect_success_total 40269
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 40757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 2201
telemt_me_reconnect_attempts_total 48001
telemt_me_reconnect_success_total 33931
telemt_me_reader_eof_total 35560
telemt_me_idle_close_by_peer_total 35560
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 565135
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1411968
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4932
telemt_desync_full_logged_total 1761
telemt_desync_suppressed_total 3171
telemt_desync_frames_bucket_total{bucket="1_2"} 1510
telemt_desync_frames_bucket_total{bucket="3_10"} 1594
telemt_desync_frames_bucket_total{bucket="gt_10"} 1828
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34744
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 33870
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 813
telemt_user_connections_total{user="hello"} 1411770
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 18204332848 (16.95 GB)
telemt_user_octets_to_client{user="hello"} 490203520320 (456.54 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 119
```