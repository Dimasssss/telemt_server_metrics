# Server Metrics 2026-03-13 00:06:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 65280.4 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1978345
telemt_connections_bad_total 26104
telemt_handshake_timeouts_total 21340
telemt_upstream_connect_attempt_total 12970
telemt_upstream_connect_success_total 12895
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1239
telemt_me_reconnect_attempts_total 18477
telemt_me_reconnect_success_total 9617
telemt_me_reader_eof_total 10401
telemt_me_idle_close_by_peer_total 10400
telemt_me_route_drop_no_conn_total 770012
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1839717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8630
telemt_desync_full_logged_total 2252
telemt_desync_suppressed_total 6378
telemt_desync_frames_bucket_total{bucket="1_2"} 2272
telemt_desync_frames_bucket_total{bucket="3_10"} 3109
telemt_desync_frames_bucket_total{bucket="gt_10"} 3249
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10030
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9604
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 1839180
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 27388157800 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 650597795300 (605.92 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94901.0 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816685
telemt_connections_bad_total 11749
telemt_handshake_timeouts_total 31684
telemt_upstream_connect_attempt_total 24130
telemt_upstream_connect_success_total 24101
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 17813
telemt_me_reconnect_success_total 17715
telemt_me_reader_eof_total 18861
telemt_me_idle_close_by_peer_total 18861
telemt_me_route_drop_no_conn_total 263901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738962
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3025
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2079
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17888
telemt_me_writer_restored_same_endpoint_total 17706
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 740842
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 12166754888 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 284054422739 (264.55 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94901.0 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700875
telemt_connections_bad_total 8351
telemt_handshake_timeouts_total 113432
telemt_upstream_connect_attempt_total 22089
telemt_upstream_connect_success_total 22079
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 18240
telemt_me_reconnect_success_total 16981
telemt_me_reader_eof_total 17978
telemt_me_idle_close_by_peer_total 17977
telemt_me_route_drop_no_conn_total 557670
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1332762
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17143
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16940
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 1332365
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 19895857744 (18.53 GB)
telemt_user_octets_to_client{user="hello"} 487519194389 (454.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94901.1 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1058078
telemt_connections_bad_total 13028
telemt_handshake_timeouts_total 71694
telemt_upstream_connect_attempt_total 33327
telemt_upstream_connect_success_total 31066
telemt_upstream_connect_fail_total 2124
telemt_upstream_connect_attempts_per_request{bucket="1"} 33053
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2123
telemt_me_keepalive_timeout_total 11255
telemt_me_reconnect_attempts_total 28301
telemt_me_reconnect_success_total 20463
telemt_me_reader_eof_total 22158
telemt_me_idle_close_by_peer_total 22151
telemt_me_route_drop_no_conn_total 372969
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1892
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20831
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20441
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 916706
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 14352725745 (13.37 GB)
telemt_user_octets_to_client{user="hello"} 363833194550 (338.85 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94901.1 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171174
telemt_connections_bad_total 12560
telemt_handshake_timeouts_total 9290
telemt_upstream_connect_attempt_total 28736
telemt_upstream_connect_success_total 28377
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 28736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1822
telemt_me_reconnect_attempts_total 34674
telemt_me_reconnect_success_total 23632
telemt_me_reader_eof_total 24889
telemt_me_idle_close_by_peer_total 24889
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 437752
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080289
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4058
telemt_desync_full_logged_total 1426
telemt_desync_suppressed_total 2632
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 1352
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 24252
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23587
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1080146
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 13570683468 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 379311643292 (353.26 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 50
```