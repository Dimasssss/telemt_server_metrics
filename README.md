# Server Metrics 2026-03-14 03:51:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 165157.7 (45h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4729532
telemt_connections_bad_total 39890
telemt_handshake_timeouts_total 109241
telemt_upstream_connect_attempt_total 34930
telemt_upstream_connect_success_total 34700
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 34930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 6738
telemt_me_reconnect_attempts_total 34282
telemt_me_reconnect_success_total 24140
telemt_me_reader_eof_total 25888
telemt_me_idle_close_by_peer_total 25887
telemt_me_route_drop_no_conn_total 1794693
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4337887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16800
telemt_desync_full_logged_total 4533
telemt_desync_suppressed_total 12267
telemt_desync_frames_bucket_total{bucket="1_2"} 4195
telemt_desync_frames_bucket_total{bucket="3_10"} 6407
telemt_desync_frames_bucket_total{bucket="gt_10"} 6198
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 24801
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24127
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4339463
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 63541408980 (59.18 GB)
telemt_user_octets_to_client{user="hello"} 1368573895353 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64821.4 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717668
telemt_connections_bad_total 52102
telemt_handshake_timeouts_total 13308
telemt_upstream_connect_attempt_total 17953
telemt_upstream_connect_success_total 17696
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2096
telemt_me_reconnect_attempts_total 15899
telemt_me_reconnect_success_total 12450
telemt_me_reader_eof_total 13216
telemt_me_idle_close_by_peer_total 13215
telemt_me_route_drop_no_conn_total 240393
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575356
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 756
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 12727
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12442
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 577311
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 6139091253 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 191963398328 (178.78 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 194778.1 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3409176
telemt_connections_bad_total 35932
telemt_handshake_timeouts_total 223984
telemt_upstream_connect_attempt_total 44037
telemt_upstream_connect_success_total 44016
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10436
telemt_me_reconnect_attempts_total 38974
telemt_me_reconnect_success_total 34007
telemt_me_reader_eof_total 36123
telemt_me_idle_close_by_peer_total 36122
telemt_me_route_drop_no_conn_total 1166715
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2840185
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9396
telemt_desync_full_logged_total 3143
telemt_desync_suppressed_total 6253
telemt_desync_frames_bucket_total{bucket="1_2"} 1620
telemt_desync_frames_bucket_total{bucket="3_10"} 3396
telemt_desync_frames_bucket_total{bucket="gt_10"} 4380
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 34480
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33966
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 2839403
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 45479537984 (42.36 GB)
telemt_user_octets_to_client{user="hello"} 1018309267689 (948.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 194780.7 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2284574
telemt_connections_bad_total 23014
telemt_handshake_timeouts_total 253460
telemt_upstream_connect_attempt_total 61060
telemt_upstream_connect_success_total 58591
telemt_upstream_connect_fail_total 2332
telemt_upstream_connect_attempts_per_request{bucket="1"} 60786
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2331
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20446
telemt_me_reconnect_attempts_total 50905
telemt_me_reconnect_success_total 41870
telemt_me_reader_eof_total 44909
telemt_me_idle_close_by_peer_total 44902
telemt_me_route_drop_no_conn_total 776916
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1815762
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3844
telemt_desync_full_logged_total 1235
telemt_desync_suppressed_total 2609
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1596
telemt_desync_frames_bucket_total{bucket="gt_10"} 1218
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 42509
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41846
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 1821707
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 27687820371 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 671557289006 (625.44 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64214.2 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717378
telemt_connections_bad_total 7961
telemt_handshake_timeouts_total 8707
telemt_upstream_connect_attempt_total 16696
telemt_upstream_connect_success_total 16247
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 16696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_keepalive_timeout_total 1526
telemt_me_reconnect_attempts_total 51784
telemt_me_reconnect_success_total 13028
telemt_me_reader_eof_total 14550
telemt_me_idle_close_by_peer_total 14549
telemt_me_route_drop_no_conn_total 273282
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669021
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14348
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13023
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1320
telemt_user_connections_total{user="hello"} 668893
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 12209015208 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 216595563756 (201.72 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 46
```