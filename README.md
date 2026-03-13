# Server Metrics 2026-03-13 01:38:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70785.0 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2039700
telemt_connections_bad_total 26136
telemt_handshake_timeouts_total 21775
telemt_upstream_connect_attempt_total 14038
telemt_upstream_connect_success_total 13958
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 1252
telemt_me_reconnect_attempts_total 19280
telemt_me_reconnect_success_total 10419
telemt_me_reader_eof_total 11264
telemt_me_idle_close_by_peer_total 11263
telemt_me_route_drop_no_conn_total 795130
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1898007
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8695
telemt_desync_full_logged_total 2261
telemt_desync_suppressed_total 6434
telemt_desync_frames_bucket_total{bucket="1_2"} 2291
telemt_desync_frames_bucket_total{bucket="3_10"} 3137
telemt_desync_frames_bucket_total{bucket="gt_10"} 3267
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10845
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10406
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 1897465
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 27730323040 (25.83 GB)
telemt_user_octets_to_client{user="hello"} 661807750492 (616.36 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100405.6 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840912
telemt_connections_bad_total 11786
telemt_handshake_timeouts_total 31986
telemt_upstream_connect_attempt_total 25552
telemt_upstream_connect_success_total 25523
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 25552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3447
telemt_me_reconnect_attempts_total 18977
telemt_me_reconnect_success_total 18872
telemt_me_reader_eof_total 20097
telemt_me_idle_close_by_peer_total 20097
telemt_me_route_drop_no_conn_total 270902
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762183
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19056
telemt_me_writer_restored_same_endpoint_total 18863
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 764086
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 12271000700 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 288567511839 (268.75 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100405.3 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1745455
telemt_connections_bad_total 8974
telemt_handshake_timeouts_total 116175
telemt_upstream_connect_attempt_total 23449
telemt_upstream_connect_success_total 23438
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 19340
telemt_me_reconnect_success_total 18076
telemt_me_reader_eof_total 19142
telemt_me_idle_close_by_peer_total 19141
telemt_me_route_drop_no_conn_total 571860
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1371402
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4997
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 3464
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1807
telemt_desync_frames_bucket_total{bucket="gt_10"} 2392
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18248
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18035
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 1370999
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 20097365740 (18.72 GB)
telemt_user_octets_to_client{user="hello"} 498016497053 (463.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100405.4 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093751
telemt_connections_bad_total 13096
telemt_handshake_timeouts_total 72527
telemt_upstream_connect_attempt_total 34968
telemt_upstream_connect_success_total 32698
telemt_upstream_connect_fail_total 2133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34694
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2132
telemt_me_keepalive_timeout_total 11275
telemt_me_reconnect_attempts_total 29672
telemt_me_reconnect_success_total 21829
telemt_me_reader_eof_total 23604
telemt_me_idle_close_by_peer_total 23597
telemt_me_route_drop_no_conn_total 386490
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937690
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 22214
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 21807
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 942876
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 14473224689 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 369935902082 (344.53 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 100405.6 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205879
telemt_connections_bad_total 12584
telemt_handshake_timeouts_total 9410
telemt_upstream_connect_attempt_total 30842
telemt_upstream_connect_success_total 30458
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 30842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 1855
telemt_me_reconnect_attempts_total 36496
telemt_me_reconnect_success_total 25448
telemt_me_reader_eof_total 26742
telemt_me_idle_close_by_peer_total 26742
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 452124
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1114183
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4165
telemt_desync_full_logged_total 1476
telemt_desync_suppressed_total 2689
telemt_desync_frames_bucket_total{bucket="1_2"} 1249
telemt_desync_frames_bucket_total{bucket="3_10"} 1380
telemt_desync_frames_bucket_total{bucket="gt_10"} 1536
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 26088
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 25401
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 1114039
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 13741116456 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 382850702640 (356.56 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 33
```