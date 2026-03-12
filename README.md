# Server Metrics 2026-03-12 14:09:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29436.7 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1042260
telemt_connections_bad_total 10938
telemt_handshake_timeouts_total 10721
telemt_upstream_connect_attempt_total 5820
telemt_upstream_connect_success_total 5786
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 387
telemt_me_reconnect_attempts_total 8187
telemt_me_reconnect_success_total 4287
telemt_me_reader_eof_total 4587
telemt_me_idle_close_by_peer_total 4586
telemt_me_route_drop_no_conn_total 369198
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987828
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5270
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 3938
telemt_desync_frames_bucket_total{bucket="1_2"} 1314
telemt_desync_frames_bucket_total{bucket="3_10"} 1917
telemt_desync_frames_bucket_total{bucket="gt_10"} 2039
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4461
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4274
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 987589
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 16082379600 (14.98 GB)
telemt_user_octets_to_client{user="hello"} 290052898192 (270.13 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59057.1 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492466
telemt_connections_bad_total 5337
telemt_handshake_timeouts_total 25424
telemt_upstream_connect_attempt_total 14135
telemt_upstream_connect_success_total 14128
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 11062
telemt_me_reconnect_success_total 11001
telemt_me_reader_eof_total 11702
telemt_me_idle_close_by_peer_total 11702
telemt_me_route_drop_no_conn_total 142565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1566
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11103
telemt_me_writer_restored_same_endpoint_total 10992
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 438040
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 6753803479 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 157473498282 (146.66 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59057.0 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1067001
telemt_connections_bad_total 5558
telemt_handshake_timeouts_total 78186
telemt_upstream_connect_attempt_total 14124
telemt_upstream_connect_success_total 14119
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 10911
telemt_me_reconnect_success_total 10812
telemt_me_reader_eof_total 11388
telemt_me_idle_close_by_peer_total 11388
telemt_me_route_drop_no_conn_total 277041
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763383
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3254
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2260
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 1174
telemt_desync_frames_bucket_total{bucket="gt_10"} 1604
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10851
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10771
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 763580
telemt_user_connections_current{user="hello"} 1009
telemt_user_octets_from_client{user="hello"} 10084831588 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 245207056501 (228.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59057.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616995
telemt_connections_bad_total 7683
telemt_handshake_timeouts_total 55396
telemt_upstream_connect_attempt_total 15648
telemt_upstream_connect_success_total 15586
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1314
telemt_me_reconnect_attempts_total 13870
telemt_me_reconnect_success_total 12636
telemt_me_reader_eof_total 13405
telemt_me_idle_close_by_peer_total 13405
telemt_me_route_drop_no_conn_total 207611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1064
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 693
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12771
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12615
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 521837
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 5745180684 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 211190328292 (196.69 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59057.4 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697816
telemt_connections_bad_total 3360
telemt_handshake_timeouts_total 5608
telemt_upstream_connect_attempt_total 18565
telemt_upstream_connect_success_total 18339
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 1037
telemt_me_reconnect_attempts_total 22614
telemt_me_reconnect_success_total 15386
telemt_me_reader_eof_total 16134
telemt_me_idle_close_by_peer_total 16134
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 239752
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 647929
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2646
telemt_desync_full_logged_total 890
telemt_desync_suppressed_total 1756
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 923
telemt_desync_frames_bucket_total{bucket="gt_10"} 984
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15769
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15355
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 647832
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 7536560064 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 176781075736 (164.64 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 127
```