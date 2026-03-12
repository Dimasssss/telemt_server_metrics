# Server Metrics 2026-03-12 22:50:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60693.1 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1931245
telemt_connections_bad_total 26064
telemt_handshake_timeouts_total 21108
telemt_upstream_connect_attempt_total 11996
telemt_upstream_connect_success_total 11928
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 607
telemt_me_reconnect_attempts_total 17724
telemt_me_reconnect_success_total 8868
telemt_me_reader_eof_total 9578
telemt_me_idle_close_by_peer_total 9577
telemt_me_route_drop_no_conn_total 754322
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1796540
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8521
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 6299
telemt_desync_frames_bucket_total{bucket="1_2"} 2243
telemt_desync_frames_bucket_total{bucket="3_10"} 3065
telemt_desync_frames_bucket_total{bucket="gt_10"} 3213
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9269
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 8855
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1796012
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 27056436468 (25.20 GB)
telemt_user_octets_to_client{user="hello"} 640110237540 (596.15 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90313.6 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799499
telemt_connections_bad_total 11706
telemt_handshake_timeouts_total 31374
telemt_upstream_connect_attempt_total 22864
telemt_upstream_connect_success_total 22835
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 22864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3414
telemt_me_reconnect_attempts_total 16763
telemt_me_reconnect_success_total 16668
telemt_me_reader_eof_total 17743
telemt_me_idle_close_by_peer_total 17743
telemt_me_route_drop_no_conn_total 258682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3001
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 2068
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16837
telemt_me_writer_restored_same_endpoint_total 16659
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 724316
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 12082945588 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 279540160563 (260.34 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90313.5 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664672
telemt_connections_bad_total 8034
telemt_handshake_timeouts_total 113303
telemt_upstream_connect_attempt_total 21023
telemt_upstream_connect_success_total 21017
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1222
telemt_me_reconnect_attempts_total 17391
telemt_me_reconnect_success_total 16140
telemt_me_reader_eof_total 17066
telemt_me_idle_close_by_peer_total 17065
telemt_me_route_drop_no_conn_total 546595
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297891
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4969
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3444
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 1796
telemt_desync_frames_bucket_total{bucket="gt_10"} 2382
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16296
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16099
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 1297497
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 19754648948 (18.40 GB)
telemt_user_octets_to_client{user="hello"} 480730091305 (447.71 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90313.7 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024788
telemt_connections_bad_total 13005
telemt_handshake_timeouts_total 71469
telemt_upstream_connect_attempt_total 23152
telemt_upstream_connect_success_total 23058
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 23152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 26275
telemt_me_reconnect_success_total 18543
telemt_me_reader_eof_total 19812
telemt_me_idle_close_by_peer_total 19812
telemt_me_route_drop_no_conn_total 366806
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 893518
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 615
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18930
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 18522
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 892864
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 14235906520 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 357492526848 (332.94 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90313.6 (25h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1146650
telemt_connections_bad_total 12537
telemt_handshake_timeouts_total 9214
telemt_upstream_connect_attempt_total 27626
telemt_upstream_connect_success_total 27281
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 27626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 1448
telemt_me_reconnect_attempts_total 33794
telemt_me_reconnect_success_total 22754
telemt_me_reader_eof_total 23930
telemt_me_idle_close_by_peer_total 23930
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 428351
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1056160
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3986
telemt_desync_full_logged_total 1385
telemt_desync_suppressed_total 2601
telemt_desync_frames_bucket_total{bucket="1_2"} 1161
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1506
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 23362
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22710
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 1056019
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 13468321900 (12.54 GB)
telemt_user_octets_to_client{user="hello"} 374115469284 (348.42 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 46
```