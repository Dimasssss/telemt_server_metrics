# Server Metrics 2026-03-12 17:33:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41694.5 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1507287
telemt_connections_bad_total 20278
telemt_handshake_timeouts_total 14118
telemt_upstream_connect_attempt_total 8254
telemt_upstream_connect_success_total 8206
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 8254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 14915
telemt_me_reconnect_success_total 6071
telemt_me_reader_eof_total 6593
telemt_me_idle_close_by_peer_total 6592
telemt_me_route_drop_no_conn_total 585209
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1412772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7146
telemt_desync_full_logged_total 1812
telemt_desync_suppressed_total 5334
telemt_desync_frames_bucket_total{bucket="1_2"} 1861
telemt_desync_frames_bucket_total{bucket="3_10"} 2578
telemt_desync_frames_bucket_total{bucket="gt_10"} 2707
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6430
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6058
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 1412267
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 21579752392 (20.10 GB)
telemt_user_octets_to_client{user="hello"} 440768331920 (410.50 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71314.7 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654166
telemt_connections_bad_total 8604
telemt_handshake_timeouts_total 28984
telemt_upstream_connect_attempt_total 16950
telemt_upstream_connect_success_total 16943
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1353
telemt_me_reconnect_attempts_total 13259
telemt_me_reconnect_success_total 13182
telemt_me_reader_eof_total 14021
telemt_me_idle_close_by_peer_total 14021
telemt_me_route_drop_no_conn_total 203756
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588165
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2451
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1700
telemt_desync_frames_bucket_total{bucket="1_2"} 1028
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13317
telemt_me_writer_restored_same_endpoint_total 13173
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 588707
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 9007406171 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 220365283178 (205.23 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71314.6 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364664
telemt_connections_bad_total 6685
telemt_handshake_timeouts_total 97231
telemt_upstream_connect_attempt_total 16983
telemt_upstream_connect_success_total 16978
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 14264
telemt_me_reconnect_success_total 13026
telemt_me_reader_eof_total 13734
telemt_me_idle_close_by_peer_total 13733
telemt_me_route_drop_no_conn_total 442448
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1031313
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4390
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 3032
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 1600
telemt_desync_frames_bucket_total{bucket="gt_10"} 2117
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13130
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12985
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1031170
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 15483704272 (14.42 GB)
telemt_user_octets_to_client{user="hello"} 356669996049 (332.17 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71315.3 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824337
telemt_connections_bad_total 9438
telemt_handshake_timeouts_total 63394
telemt_upstream_connect_attempt_total 18617
telemt_upstream_connect_success_total 18545
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 18617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1572
telemt_me_reconnect_attempts_total 20208
telemt_me_reconnect_success_total 14954
telemt_me_reader_eof_total 15916
telemt_me_idle_close_by_peer_total 15916
telemt_me_route_drop_no_conn_total 288107
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714043
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1592
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1060
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15235
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14933
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 713459
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 8814984400 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 289169366332 (269.31 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71315.0 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929895
telemt_connections_bad_total 11402
telemt_handshake_timeouts_total 7589
telemt_upstream_connect_attempt_total 22760
telemt_upstream_connect_success_total 22488
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 22760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 28786
telemt_me_reconnect_success_total 18880
telemt_me_reader_eof_total 19803
telemt_me_idle_close_by_peer_total 19803
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 341126
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853796
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3334
telemt_desync_full_logged_total 1141
telemt_desync_suppressed_total 2193
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 1140
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19397
telemt_me_refill_failed_total 307
telemt_me_writer_restored_same_endpoint_total 18836
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 853678
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 10469080428 (9.75 GB)
telemt_user_octets_to_client{user="hello"} 263498057140 (245.40 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 102
```