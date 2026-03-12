# Server Metrics 2026-03-12 09:23:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12304.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389461
telemt_connections_bad_total 1333
telemt_handshake_timeouts_total 2436
telemt_upstream_connect_attempt_total 2334
telemt_upstream_connect_success_total 2321
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 1687
telemt_me_reconnect_success_total 1676
telemt_me_reader_eof_total 1740
telemt_me_idle_close_by_peer_total 1740
telemt_me_route_drop_no_conn_total 132571
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376632
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1319
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1690
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 376508
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 5795351056 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 103755929820 (96.63 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41924.7 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247049
telemt_connections_bad_total 2935
telemt_handshake_timeouts_total 7878
telemt_upstream_connect_attempt_total 10678
telemt_upstream_connect_success_total 10672
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 654
telemt_me_reconnect_attempts_total 8437
telemt_me_reconnect_success_total 8394
telemt_me_reader_eof_total 8920
telemt_me_idle_close_by_peer_total 8920
telemt_me_route_drop_no_conn_total 70862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218515
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8459
telemt_me_writer_restored_same_endpoint_total 8385
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 218906
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 3183611187 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 84824010730 (79.00 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41924.7 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666778
telemt_connections_bad_total 3019
telemt_handshake_timeouts_total 49298
telemt_upstream_connect_attempt_total 10701
telemt_upstream_connect_success_total 10696
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 8317
telemt_me_reconnect_success_total 8246
telemt_me_reader_eof_total 8665
telemt_me_idle_close_by_peer_total 8665
telemt_me_route_drop_no_conn_total 140319
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402914
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1829
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1281
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8245
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8205
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 403177
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 5011231796 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 135904835465 (126.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41925.1 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328423
telemt_connections_bad_total 1827
telemt_handshake_timeouts_total 23364
telemt_upstream_connect_attempt_total 11474
telemt_upstream_connect_success_total 11428
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 810
telemt_me_reconnect_attempts_total 9362
telemt_me_reconnect_success_total 9328
telemt_me_reader_eof_total 9898
telemt_me_idle_close_by_peer_total 9898
telemt_me_route_drop_no_conn_total 111448
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275819
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 552
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9388
telemt_me_writer_restored_same_endpoint_total 9307
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 275640
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 3247068312 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 103262416908 (96.17 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41924.7 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367368
telemt_connections_bad_total 384
telemt_handshake_timeouts_total 2699
telemt_upstream_connect_attempt_total 13646
telemt_upstream_connect_success_total 13482
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 13646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 587
telemt_me_reconnect_attempts_total 12894
telemt_me_reconnect_success_total 11377
telemt_me_reader_eof_total 11857
telemt_me_idle_close_by_peer_total 11857
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 117922
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346731
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1456
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 978
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11526
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11355
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 346669
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 3754146420 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 83384994412 (77.66 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 103
```