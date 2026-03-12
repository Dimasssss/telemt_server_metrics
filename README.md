# Server Metrics 2026-03-12 23:15:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62222.3 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1947332
telemt_connections_bad_total 26075
telemt_handshake_timeouts_total 21174
telemt_upstream_connect_attempt_total 12333
telemt_upstream_connect_success_total 12262
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 616
telemt_me_reconnect_attempts_total 17972
telemt_me_reconnect_success_total 9116
telemt_me_reader_eof_total 9843
telemt_me_idle_close_by_peer_total 9842
telemt_me_route_drop_no_conn_total 758856
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810954
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8551
telemt_desync_full_logged_total 2230
telemt_desync_suppressed_total 6321
telemt_desync_frames_bucket_total{bucket="1_2"} 2258
telemt_desync_frames_bucket_total{bucket="3_10"} 3074
telemt_desync_frames_bucket_total{bucket="gt_10"} 3219
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9522
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9103
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 1810423
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 27223268220 (25.35 GB)
telemt_user_octets_to_client{user="hello"} 642842793264 (598.69 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91842.9 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 805423
telemt_connections_bad_total 11723
telemt_handshake_timeouts_total 31468
telemt_upstream_connect_attempt_total 23212
telemt_upstream_connect_success_total 23183
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3418
telemt_me_reconnect_attempts_total 17053
telemt_me_reconnect_success_total 16957
telemt_me_reader_eof_total 18044
telemt_me_idle_close_by_peer_total 18044
telemt_me_route_drop_no_conn_total 260365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728145
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
telemt_me_writer_removed_unexpected_total 17127
telemt_me_writer_restored_same_endpoint_total 16948
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 730025
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 12105952408 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 282378438935 (262.99 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91842.9 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1677249
telemt_connections_bad_total 8095
telemt_handshake_timeouts_total 113327
telemt_upstream_connect_attempt_total 21313
telemt_upstream_connect_success_total 21307
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1226
telemt_me_reconnect_attempts_total 17624
telemt_me_reconnect_success_total 16373
telemt_me_reader_eof_total 17310
telemt_me_idle_close_by_peer_total 17309
telemt_me_route_drop_no_conn_total 549909
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1310122
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
telemt_me_writer_removed_unexpected_total 16532
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16332
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 1309728
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 19787773876 (18.43 GB)
telemt_user_octets_to_client{user="hello"} 484419757845 (451.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91842.8 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1036227
telemt_connections_bad_total 13010
telemt_handshake_timeouts_total 71526
telemt_upstream_connect_attempt_total 32090
telemt_upstream_connect_success_total 29832
telemt_upstream_connect_fail_total 2121
telemt_upstream_connect_attempts_per_request{bucket="1"} 31816
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2120
telemt_me_keepalive_timeout_total 11240
telemt_me_reconnect_attempts_total 27565
telemt_me_reconnect_success_total 19728
telemt_me_reader_eof_total 21302
telemt_me_idle_close_by_peer_total 21295
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
telemt_me_writer_removed_unexpected_total 20090
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 19706
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 902176
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 14264575629 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 360132483148 (335.40 GB)
telemt_user_msgs_from_client{user="hello"} 42187
telemt_user_msgs_to_client{user="hello"} 108765
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91843.1 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155119
telemt_connections_bad_total 12542
telemt_handshake_timeouts_total 9256
telemt_upstream_connect_attempt_total 27943
telemt_upstream_connect_success_total 27595
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 27943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 1453
telemt_me_reconnect_attempts_total 34058
telemt_me_reconnect_success_total 23018
telemt_me_reader_eof_total 24207
telemt_me_idle_close_by_peer_total 24207
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 431093
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064489
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4015
telemt_desync_full_logged_total 1399
telemt_desync_suppressed_total 2616
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 23631
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 22973
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 1064347
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 13509968152 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 375277944184 (349.50 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 31
```