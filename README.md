# Server Metrics 2026-03-12 23:10:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61916.7 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1943223
telemt_connections_bad_total 26075
telemt_handshake_timeouts_total 21157
telemt_upstream_connect_attempt_total 12252
telemt_upstream_connect_success_total 12183
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 615
telemt_me_reconnect_attempts_total 17936
telemt_me_reconnect_success_total 9080
telemt_me_reader_eof_total 9803
telemt_me_idle_close_by_peer_total 9802
telemt_me_route_drop_no_conn_total 757590
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1807209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8537
telemt_desync_full_logged_total 2227
telemt_desync_suppressed_total 6310
telemt_desync_frames_bucket_total{bucket="1_2"} 2252
telemt_desync_frames_bucket_total{bucket="3_10"} 3070
telemt_desync_frames_bucket_total{bucket="gt_10"} 3215
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9484
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9067
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 1806680
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 27205632372 (25.34 GB)
telemt_user_octets_to_client{user="hello"} 642230121856 (598.12 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91537.2 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803835
telemt_connections_bad_total 11723
telemt_handshake_timeouts_total 31447
telemt_upstream_connect_attempt_total 23156
telemt_upstream_connect_success_total 23127
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3418
telemt_me_reconnect_attempts_total 17012
telemt_me_reconnect_success_total 16916
telemt_me_reader_eof_total 18004
telemt_me_idle_close_by_peer_total 18004
telemt_me_route_drop_no_conn_total 259830
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3010
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2073
telemt_desync_frames_bucket_total{bucket="1_2"} 1195
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17087
telemt_me_writer_restored_same_endpoint_total 16907
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 728484
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 12101991348 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 282155983999 (262.78 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91537.0 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1674174
telemt_connections_bad_total 8071
telemt_handshake_timeouts_total 113315
telemt_upstream_connect_attempt_total 21266
telemt_upstream_connect_success_total 21260
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1226
telemt_me_reconnect_attempts_total 17591
telemt_me_reconnect_success_total 16340
telemt_me_reader_eof_total 17276
telemt_me_idle_close_by_peer_total 17275
telemt_me_route_drop_no_conn_total 549059
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307126
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
telemt_me_writer_removed_unexpected_total 16498
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16299
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 1306732
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 19780086300 (18.42 GB)
telemt_user_octets_to_client{user="hello"} 483892579573 (450.66 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91537.3 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034060
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 71512
telemt_upstream_connect_attempt_total 29631
telemt_upstream_connect_success_total 27374
telemt_upstream_connect_fail_total 2120
telemt_upstream_connect_attempts_per_request{bucket="1"} 29357
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2119
telemt_me_keepalive_timeout_total 11232
telemt_me_reconnect_attempts_total 27247
telemt_me_reconnect_success_total 19411
telemt_me_reader_eof_total 20970
telemt_me_idle_close_by_peer_total 20963
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
telemt_me_writer_removed_unexpected_total 19758
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 19389
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 900043
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 14256021489 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 359395134135 (334.71 GB)
telemt_user_msgs_from_client{user="hello"} 21097
telemt_user_msgs_to_client{user="hello"} 51567
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91537.4 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1153087
telemt_connections_bad_total 12542
telemt_handshake_timeouts_total 9254
telemt_upstream_connect_attempt_total 27899
telemt_upstream_connect_success_total 27551
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 27899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 34021
telemt_me_reconnect_success_total 22981
telemt_me_reader_eof_total 24168
telemt_me_idle_close_by_peer_total 24168
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 430330
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062479
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4005
telemt_desync_full_logged_total 1395
telemt_desync_suppressed_total 2610
telemt_desync_frames_bucket_total{bucket="1_2"} 1167
telemt_desync_frames_bucket_total{bucket="3_10"} 1329
telemt_desync_frames_bucket_total{bucket="gt_10"} 1509
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 23592
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22936
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 1062337
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 13505305484 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 375149418240 (349.39 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 37
```