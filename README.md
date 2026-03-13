# Server Metrics 2026-03-13 00:42:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67421.3 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2005395
telemt_connections_bad_total 26110
telemt_handshake_timeouts_total 21444
telemt_upstream_connect_attempt_total 13371
telemt_upstream_connect_success_total 13295
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1246
telemt_me_reconnect_attempts_total 18789
telemt_me_reconnect_success_total 9930
telemt_me_reader_eof_total 10739
telemt_me_idle_close_by_peer_total 10738
telemt_me_route_drop_no_conn_total 783143
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1865439
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8668
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 3256
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10346
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9917
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 1864897
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 27521255584 (25.63 GB)
telemt_user_octets_to_client{user="hello"} 655385166520 (610.38 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97041.8 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826379
telemt_connections_bad_total 11755
telemt_handshake_timeouts_total 31840
telemt_upstream_connect_attempt_total 24675
telemt_upstream_connect_success_total 24646
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3437
telemt_me_reconnect_attempts_total 18272
telemt_me_reconnect_success_total 18171
telemt_me_reader_eof_total 19344
telemt_me_idle_close_by_peer_total 19344
telemt_me_route_drop_no_conn_total 267633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748326
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3054
telemt_desync_full_logged_total 957
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 1235
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18348
telemt_me_writer_restored_same_endpoint_total 18162
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 750229
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 12203320652 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 285436423007 (265.83 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97041.7 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1719220
telemt_connections_bad_total 8778
telemt_handshake_timeouts_total 113685
telemt_upstream_connect_attempt_total 22532
telemt_upstream_connect_success_total 22522
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1576
telemt_me_reconnect_attempts_total 18597
telemt_me_reconnect_success_total 17335
telemt_me_reader_eof_total 18357
telemt_me_idle_close_by_peer_total 18356
telemt_me_route_drop_no_conn_total 565199
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1350015
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4979
telemt_desync_full_logged_total 1528
telemt_desync_suppressed_total 3451
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1801
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17502
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17294
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 1349617
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 19964159088 (18.59 GB)
telemt_user_octets_to_client{user="hello"} 490836018877 (457.13 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97041.7 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077938
telemt_connections_bad_total 13050
telemt_handshake_timeouts_total 72135
telemt_upstream_connect_attempt_total 33872
telemt_upstream_connect_success_total 31609
telemt_upstream_connect_fail_total 2126
telemt_upstream_connect_attempts_per_request{bucket="1"} 33598
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2125
telemt_me_keepalive_timeout_total 11266
telemt_me_reconnect_attempts_total 28758
telemt_me_reconnect_success_total 20918
telemt_me_reader_eof_total 22639
telemt_me_idle_close_by_peer_total 22632
telemt_me_route_drop_no_conn_total 380597
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923391
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
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21291
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20896
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 928582
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 14407056049 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 367343372918 (342.12 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97042.0 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1186659
telemt_connections_bad_total 12579
telemt_handshake_timeouts_total 9328
telemt_upstream_connect_attempt_total 29319
telemt_upstream_connect_success_total 28954
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 29319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 1831
telemt_me_reconnect_attempts_total 35165
telemt_me_reconnect_success_total 24121
telemt_me_reader_eof_total 25399
telemt_me_idle_close_by_peer_total 25399
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 445102
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4109
telemt_desync_full_logged_total 1449
telemt_desync_suppressed_total 2660
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 1371
telemt_desync_frames_bucket_total{bucket="gt_10"} 1524
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 24744
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 24075
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 1095284
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 13658100436 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 381128666384 (354.95 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 40
```