# Server Metrics 2026-03-13 00:27:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66503.3 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1994295
telemt_connections_bad_total 26107
telemt_handshake_timeouts_total 21403
telemt_upstream_connect_attempt_total 13194
telemt_upstream_connect_success_total 13118
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1242
telemt_me_reconnect_attempts_total 18655
telemt_me_reconnect_success_total 9796
telemt_me_reader_eof_total 10593
telemt_me_idle_close_by_peer_total 10592
telemt_me_route_drop_no_conn_total 778072
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1855174
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8659
telemt_desync_full_logged_total 2257
telemt_desync_suppressed_total 6402
telemt_desync_frames_bucket_total{bucket="1_2"} 2287
telemt_desync_frames_bucket_total{bucket="3_10"} 3119
telemt_desync_frames_bucket_total{bucket="gt_10"} 3253
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10210
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9783
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 414
telemt_user_connections_total{user="hello"} 1854635
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 27461039716 (25.58 GB)
telemt_user_octets_to_client{user="hello"} 653920534828 (609.01 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96124.0 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 822357
telemt_connections_bad_total 11751
telemt_handshake_timeouts_total 31778
telemt_upstream_connect_attempt_total 24431
telemt_upstream_connect_success_total 24402
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3435
telemt_me_reconnect_attempts_total 18071
telemt_me_reconnect_success_total 17972
telemt_me_reader_eof_total 19130
telemt_me_idle_close_by_peer_total 19130
telemt_me_route_drop_no_conn_total 266337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3039
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2088
telemt_desync_frames_bucket_total{bucket="1_2"} 1220
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18146
telemt_me_writer_restored_same_endpoint_total 17963
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 746339
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 12182681680 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 285188225427 (265.60 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96123.8 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1712110
telemt_connections_bad_total 8593
telemt_handshake_timeouts_total 113502
telemt_upstream_connect_attempt_total 22326
telemt_upstream_connect_success_total 22315
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1574
telemt_me_reconnect_attempts_total 18434
telemt_me_reconnect_success_total 17173
telemt_me_reader_eof_total 18184
telemt_me_idle_close_by_peer_total 18183
telemt_me_route_drop_no_conn_total 562016
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1343577
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
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 17338
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 17132
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 1343180
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 19942091896 (18.57 GB)
telemt_user_octets_to_client{user="hello"} 489514691341 (455.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96123.9 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1068336
telemt_connections_bad_total 13046
telemt_handshake_timeouts_total 71765
telemt_upstream_connect_attempt_total 33616
telemt_upstream_connect_success_total 31354
telemt_upstream_connect_fail_total 2125
telemt_upstream_connect_attempts_per_request{bucket="1"} 33342
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2124
telemt_me_keepalive_timeout_total 11261
telemt_me_reconnect_attempts_total 28546
telemt_me_reconnect_success_total 20707
telemt_me_reader_eof_total 22413
telemt_me_idle_close_by_peer_total 22406
telemt_me_route_drop_no_conn_total 377365
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 918165
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
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 21077
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20685
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 923357
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 14381885585 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 366248798378 (341.10 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96124.1 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180340
telemt_connections_bad_total 12575
telemt_handshake_timeouts_total 9307
telemt_upstream_connect_attempt_total 29078
telemt_upstream_connect_success_total 28715
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 29078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_keepalive_timeout_total 1827
telemt_me_reconnect_attempts_total 34969
telemt_me_reconnect_success_total 23926
telemt_me_reader_eof_total 25185
telemt_me_idle_close_by_peer_total 25185
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 441917
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1089296
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4094
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 2652
telemt_desync_frames_bucket_total{bucket="1_2"} 1204
telemt_desync_frames_bucket_total{bucket="3_10"} 1368
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 24549
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23880
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 1089153
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 13623242788 (12.69 GB)
telemt_user_octets_to_client{user="hello"} 380499504092 (354.37 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 39
```