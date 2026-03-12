# Server Metrics 2026-03-12 23:05:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61610.9 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1940078
telemt_connections_bad_total 26067
telemt_handshake_timeouts_total 21147
telemt_upstream_connect_attempt_total 12212
telemt_upstream_connect_success_total 12143
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 610
telemt_me_reconnect_attempts_total 17896
telemt_me_reconnect_success_total 9040
telemt_me_reader_eof_total 9763
telemt_me_idle_close_by_peer_total 9762
telemt_me_route_drop_no_conn_total 756804
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1804422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8530
telemt_desync_full_logged_total 2225
telemt_desync_suppressed_total 6305
telemt_desync_frames_bucket_total{bucket="1_2"} 2248
telemt_desync_frames_bucket_total{bucket="3_10"} 3068
telemt_desync_frames_bucket_total{bucket="gt_10"} 3214
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9444
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9027
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 1803893
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 27185417536 (25.32 GB)
telemt_user_octets_to_client{user="hello"} 641390336412 (597.34 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91231.4 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802674
telemt_connections_bad_total 11708
telemt_handshake_timeouts_total 31430
telemt_upstream_connect_attempt_total 23099
telemt_upstream_connect_success_total 23070
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3417
telemt_me_reconnect_attempts_total 16955
telemt_me_reconnect_success_total 16860
telemt_me_reader_eof_total 17947
telemt_me_idle_close_by_peer_total 17947
telemt_me_route_drop_no_conn_total 259467
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3008
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 2072
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17030
telemt_me_writer_restored_same_endpoint_total 16851
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 727379
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 12097980636 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 281854341027 (262.50 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91231.2 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1671706
telemt_connections_bad_total 8052
telemt_handshake_timeouts_total 113315
telemt_upstream_connect_attempt_total 21213
telemt_upstream_connect_success_total 21207
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1225
telemt_me_reconnect_attempts_total 17538
telemt_me_reconnect_success_total 16287
telemt_me_reader_eof_total 17223
telemt_me_idle_close_by_peer_total 17222
telemt_me_route_drop_no_conn_total 548544
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1304739
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
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16445
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16246
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 1304345
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 19775578716 (18.42 GB)
telemt_user_octets_to_client{user="hello"} 483637455289 (450.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91231.4 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032308
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 71503
telemt_upstream_connect_attempt_total 27485
telemt_upstream_connect_success_total 25228
telemt_upstream_connect_fail_total 2120
telemt_upstream_connect_attempts_per_request{bucket="1"} 27211
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2119
telemt_me_keepalive_timeout_total 11220
telemt_me_reconnect_attempts_total 26827
telemt_me_reconnect_success_total 18991
telemt_me_reader_eof_total 20544
telemt_me_idle_close_by_peer_total 20537
telemt_me_route_drop_no_conn_total 368278
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19332
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 18969
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 898317
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 14250577172 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 359049489638 (334.39 GB)
telemt_user_msgs_from_client{user="hello"} 7565
telemt_user_msgs_to_client{user="hello"} 19790
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91231.4 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1151678
telemt_connections_bad_total 12541
telemt_handshake_timeouts_total 9249
telemt_upstream_connect_attempt_total 27847
telemt_upstream_connect_success_total 27499
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 27847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 1450
telemt_me_reconnect_attempts_total 33969
telemt_me_reconnect_success_total 22929
telemt_me_reader_eof_total 24116
telemt_me_idle_close_by_peer_total 24116
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 429872
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1061095
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4004
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 2610
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 1329
telemt_desync_frames_bucket_total{bucket="gt_10"} 1509
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 23540
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22884
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 1060953
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 13502108528 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 375006304084 (349.25 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 33
```