# Server Metrics 2026-03-13 05:02:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83024.1 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2239210
telemt_connections_bad_total 32112
telemt_handshake_timeouts_total 23517
telemt_upstream_connect_attempt_total 16398
telemt_upstream_connect_success_total 16306
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1306
telemt_me_reconnect_attempts_total 21024
telemt_me_reconnect_success_total 12158
telemt_me_reader_eof_total 13122
telemt_me_idle_close_by_peer_total 13121
telemt_me_route_drop_no_conn_total 853576
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2059089
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9085
telemt_desync_full_logged_total 2351
telemt_desync_suppressed_total 6734
telemt_desync_frames_bucket_total{bucket="1_2"} 2378
telemt_desync_frames_bucket_total{bucket="3_10"} 3295
telemt_desync_frames_bucket_total{bucket="gt_10"} 3412
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12603
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12145
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2058510
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 29915790756 (27.86 GB)
telemt_user_octets_to_client{user="hello"} 710511980732 (661.72 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112644.7 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909434
telemt_connections_bad_total 12352
telemt_handshake_timeouts_total 39798
telemt_upstream_connect_attempt_total 28556
telemt_upstream_connect_success_total 28525
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3532
telemt_me_reconnect_attempts_total 21376
telemt_me_reconnect_success_total 21259
telemt_me_reader_eof_total 22661
telemt_me_idle_close_by_peer_total 22661
telemt_me_route_drop_no_conn_total 289554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820028
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3249
telemt_desync_full_logged_total 1023
telemt_desync_suppressed_total 2226
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 1063
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21468
telemt_me_writer_restored_same_endpoint_total 21250
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 821927
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 13192110052 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 315209072895 (293.56 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112644.5 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1875931
telemt_connections_bad_total 18168
telemt_handshake_timeouts_total 123347
telemt_upstream_connect_attempt_total 26232
telemt_upstream_connect_success_total 26222
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1642
telemt_me_reconnect_attempts_total 21517
telemt_me_reconnect_success_total 20249
telemt_me_reader_eof_total 21448
telemt_me_idle_close_by_peer_total 21447
telemt_me_route_drop_no_conn_total 604903
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5143
telemt_desync_full_logged_total 1574
telemt_desync_suppressed_total 3569
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1857
telemt_desync_frames_bucket_total{bucket="gt_10"} 2458
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 20441
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20208
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 1481080
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 25530244368 (23.78 GB)
telemt_user_octets_to_client{user="hello"} 524628912797 (488.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112645.0 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1157918
telemt_connections_bad_total 13212
telemt_handshake_timeouts_total 75187
telemt_upstream_connect_attempt_total 38647
telemt_upstream_connect_success_total 36362
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38373
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11392
telemt_me_reconnect_attempts_total 33806
telemt_me_reconnect_success_total 24872
telemt_me_reader_eof_total 26841
telemt_me_idle_close_by_peer_total 26834
telemt_me_route_drop_no_conn_total 412048
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 996956
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1971
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1322
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 25320
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24848
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 1002133
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 15296832529 (14.25 GB)
telemt_user_octets_to_client{user="hello"} 394676787586 (367.57 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 112644.7 (31h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290775
telemt_connections_bad_total 12917
telemt_handshake_timeouts_total 10318
telemt_upstream_connect_attempt_total 35534
telemt_upstream_connect_success_total 35104
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 35534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 1944
telemt_me_reconnect_attempts_total 43214
telemt_me_reconnect_success_total 29481
telemt_me_reader_eof_total 30980
telemt_me_idle_close_by_peer_total 30980
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 477383
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194847
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4343
telemt_desync_full_logged_total 1564
telemt_desync_suppressed_total 2779
telemt_desync_frames_bucket_total{bucket="1_2"} 1313
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1613
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 30243
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29430
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 1194705
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 14504471536 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 406532285804 (378.61 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 97
```