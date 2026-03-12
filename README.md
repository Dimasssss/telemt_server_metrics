# Server Metrics 2026-03-12 19:20:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 48133.9 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1704363
telemt_connections_bad_total 20538
telemt_handshake_timeouts_total 16690
telemt_upstream_connect_attempt_total 9497
telemt_upstream_connect_success_total 9443
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 572
telemt_me_reconnect_attempts_total 15842
telemt_me_reconnect_success_total 6996
telemt_me_reader_eof_total 7574
telemt_me_idle_close_by_peer_total 7573
telemt_me_route_drop_no_conn_total 667866
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1592805
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8054
telemt_desync_full_logged_total 2058
telemt_desync_suppressed_total 5996
telemt_desync_frames_bucket_total{bucket="1_2"} 2102
telemt_desync_frames_bucket_total{bucket="3_10"} 2906
telemt_desync_frames_bucket_total{bucket="gt_10"} 3046
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7372
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6983
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 1592298
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 24646635864 (22.95 GB)
telemt_user_octets_to_client{user="hello"} 541864925956 (504.65 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77754.3 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726444
telemt_connections_bad_total 9644
telemt_handshake_timeouts_total 29894
telemt_upstream_connect_attempt_total 19787
telemt_upstream_connect_success_total 19758
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3370
telemt_me_reconnect_attempts_total 14291
telemt_me_reconnect_success_total 14205
telemt_me_reader_eof_total 15104
telemt_me_idle_close_by_peer_total 15104
telemt_me_route_drop_no_conn_total 232501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654759
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2847
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1974
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 14355
telemt_me_writer_restored_same_endpoint_total 14196
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 656635
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 11112994124 (10.35 GB)
telemt_user_octets_to_client{user="hello"} 248039303075 (231.00 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77754.3 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1502629
telemt_connections_bad_total 7266
telemt_handshake_timeouts_total 102930
telemt_upstream_connect_attempt_total 18409
telemt_upstream_connect_success_total 18404
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1185
telemt_me_reconnect_attempts_total 15380
telemt_me_reconnect_success_total 14136
telemt_me_reader_eof_total 14909
telemt_me_idle_close_by_peer_total 14908
telemt_me_route_drop_no_conn_total 494756
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1149774
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4748
telemt_desync_full_logged_total 1464
telemt_desync_suppressed_total 3284
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1720
telemt_desync_frames_bucket_total{bucket="gt_10"} 2281
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14263
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14095
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1149637
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 18015635492 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 426589242185 (397.29 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77755.0 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917286
telemt_connections_bad_total 12959
telemt_handshake_timeouts_total 67682
telemt_upstream_connect_attempt_total 20006
telemt_upstream_connect_success_total 19925
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 23748
telemt_me_reconnect_success_total 16023
telemt_me_reader_eof_total 17119
telemt_me_idle_close_by_peer_total 17119
telemt_me_route_drop_no_conn_total 324638
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793969
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 16394
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16002
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 793326
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 12098735256 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 325388630068 (303.04 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77754.6 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1029268
telemt_connections_bad_total 11901
telemt_handshake_timeouts_total 8477
telemt_upstream_connect_attempt_total 24226
telemt_upstream_connect_success_total 23935
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 24226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 1393
telemt_me_reconnect_attempts_total 31051
telemt_me_reconnect_success_total 20016
telemt_me_reader_eof_total 21040
telemt_me_idle_close_by_peer_total 21040
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 384931
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943863
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3543
telemt_desync_full_logged_total 1241
telemt_desync_suppressed_total 2302
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1181
telemt_desync_frames_bucket_total{bucket="gt_10"} 1358
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20586
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19972
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 943734
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 11738697808 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 319645735808 (297.69 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 80
```