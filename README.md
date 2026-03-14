# Server Metrics 2026-03-14 03:25:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 163624.4 (45h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4707882
telemt_connections_bad_total 39881
telemt_handshake_timeouts_total 109004
telemt_upstream_connect_attempt_total 34572
telemt_upstream_connect_success_total 34343
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 34572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 6733
telemt_me_reconnect_attempts_total 34012
telemt_me_reconnect_success_total 23870
telemt_me_reader_eof_total 25596
telemt_me_idle_close_by_peer_total 25595
telemt_me_route_drop_no_conn_total 1787738
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4318872
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16777
telemt_desync_full_logged_total 4525
telemt_desync_suppressed_total 12252
telemt_desync_frames_bucket_total{bucket="1_2"} 4193
telemt_desync_frames_bucket_total{bucket="3_10"} 6397
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 24528
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23857
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 4320465
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 63228792732 (58.89 GB)
telemt_user_octets_to_client{user="hello"} 1363885614869 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63287.8 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710619
telemt_connections_bad_total 51587
telemt_handshake_timeouts_total 13231
telemt_upstream_connect_attempt_total 17633
telemt_upstream_connect_success_total 17376
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 17633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 2091
telemt_me_reconnect_attempts_total 15626
telemt_me_reconnect_success_total 12177
telemt_me_reader_eof_total 12931
telemt_me_idle_close_by_peer_total 12930
telemt_me_route_drop_no_conn_total 237953
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569486
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1702
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 12450
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12169
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 571441
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 6096456165 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 187708035160 (174.82 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 193244.4 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3398332
telemt_connections_bad_total 35688
telemt_handshake_timeouts_total 223755
telemt_upstream_connect_attempt_total 43616
telemt_upstream_connect_success_total 43595
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 43616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10429
telemt_me_reconnect_attempts_total 38639
telemt_me_reconnect_success_total 33673
telemt_me_reader_eof_total 35768
telemt_me_idle_close_by_peer_total 35767
telemt_me_route_drop_no_conn_total 1163384
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2830050
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9368
telemt_desync_full_logged_total 3132
telemt_desync_suppressed_total 6236
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 3386
telemt_desync_frames_bucket_total{bucket="gt_10"} 4368
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 34144
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33632
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2829271
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 45318089192 (42.21 GB)
telemt_user_octets_to_client{user="hello"} 1009873856061 (940.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 193247.1 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2275339
telemt_connections_bad_total 22996
telemt_handshake_timeouts_total 250578
telemt_upstream_connect_attempt_total 60583
telemt_upstream_connect_success_total 58116
telemt_upstream_connect_fail_total 2330
telemt_upstream_connect_attempts_per_request{bucket="1"} 60309
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2329
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20442
telemt_me_reconnect_attempts_total 50517
telemt_me_reconnect_success_total 41482
telemt_me_reader_eof_total 44489
telemt_me_idle_close_by_peer_total 44482
telemt_me_route_drop_no_conn_total 775255
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3822
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 2592
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1592
telemt_desync_frames_bucket_total{bucket="gt_10"} 1212
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 42118
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 41458
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 1816135
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 27657267963 (25.76 GB)
telemt_user_octets_to_client{user="hello"} 669643932726 (623.65 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62680.7 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710181
telemt_connections_bad_total 7953
telemt_handshake_timeouts_total 8686
telemt_upstream_connect_attempt_total 16300
telemt_upstream_connect_success_total 15862
telemt_upstream_connect_fail_total 438
telemt_upstream_connect_attempts_per_request{bucket="1"} 16300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 438
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 48733
telemt_me_reconnect_success_total 12729
telemt_me_reader_eof_total 14165
telemt_me_idle_close_by_peer_total 14164
telemt_me_route_drop_no_conn_total 270071
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661951
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 1167
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13963
telemt_me_refill_failed_total 1121
telemt_me_writer_restored_same_endpoint_total 12724
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1234
telemt_user_connections_total{user="hello"} 661829
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 12057192996 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 215116547436 (200.34 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 45
```