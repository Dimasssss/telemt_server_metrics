# Server Metrics 2026-03-13 12:17:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109106.6 (30h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3240498
telemt_connections_bad_total 36552
telemt_handshake_timeouts_total 56298
telemt_upstream_connect_attempt_total 21612
telemt_upstream_connect_success_total 21494
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2082
telemt_me_reconnect_attempts_total 26124
telemt_me_reconnect_success_total 16043
telemt_me_reader_eof_total 17249
telemt_me_idle_close_by_peer_total 17248
telemt_me_route_drop_no_conn_total 1201518
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2968587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12592
telemt_desync_full_logged_total 3265
telemt_desync_suppressed_total 9327
telemt_desync_frames_bucket_total{bucket="1_2"} 3217
telemt_desync_frames_bucket_total{bucket="3_10"} 4733
telemt_desync_frames_bucket_total{bucket="gt_10"} 4642
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16578
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16030
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 2968519
telemt_user_connections_current{user="hello"} 1794
telemt_user_octets_from_client{user="hello"} 41054761600 (38.24 GB)
telemt_user_octets_to_client{user="hello"} 958009979728 (892.22 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 8770.4 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118083
telemt_connections_bad_total 6599
telemt_handshake_timeouts_total 2731
telemt_upstream_connect_attempt_total 2216
telemt_upstream_connect_success_total 2145
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 2216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2885
telemt_me_reconnect_success_total 1659
telemt_me_reader_eof_total 1735
telemt_me_idle_close_by_peer_total 1735
telemt_me_route_drop_no_conn_total 41864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105818
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1708
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1652
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 105842
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 1042954684 (994.64 MB)
telemt_user_octets_to_client{user="hello"} 27760181924 (25.85 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 138727.1 (38h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2465358
telemt_connections_bad_total 25788
telemt_handshake_timeouts_total 163288
telemt_upstream_connect_attempt_total 31635
telemt_upstream_connect_success_total 31625
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 31635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3158
telemt_me_reconnect_attempts_total 26896
telemt_me_reconnect_success_total 24351
telemt_me_reader_eof_total 25812
telemt_me_idle_close_by_peer_total 25811
telemt_me_route_drop_no_conn_total 821226
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1998888
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6683
telemt_desync_full_logged_total 2156
telemt_desync_suppressed_total 4527
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 2444
telemt_desync_frames_bucket_total{bucket="gt_10"} 3185
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 24633
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24310
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 1998300
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 33953778084 (31.62 GB)
telemt_user_octets_to_client{user="hello"} 714541571253 (665.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 138727.6 (38h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1571669
telemt_connections_bad_total 17851
telemt_handshake_timeouts_total 109265
telemt_upstream_connect_attempt_total 44927
telemt_upstream_connect_success_total 42608
telemt_upstream_connect_fail_total 2182
telemt_upstream_connect_attempts_per_request{bucket="1"} 44653
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2181
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11821
telemt_me_reconnect_attempts_total 38786
telemt_me_reconnect_success_total 29822
telemt_me_reader_eof_total 32068
telemt_me_idle_close_by_peer_total 32061
telemt_me_route_drop_no_conn_total 557209
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1309550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2483
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1657
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 958
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 30319
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29798
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 1314272
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 19566642105 (18.22 GB)
telemt_user_octets_to_client{user="hello"} 513303355306 (478.05 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 8163.1 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118183
telemt_connections_bad_total 661
telemt_handshake_timeouts_total 869
telemt_upstream_connect_attempt_total 1619
telemt_upstream_connect_success_total 1555
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 1618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 9171
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 46004
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112796
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_me_writer_removed_unexpected_total 1345
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1097
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 112791
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 1296734196 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 36637731888 (34.12 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 116
```