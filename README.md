# Server Metrics 2026-03-13 16:27:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 124111.0 (34h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3917487
telemt_connections_bad_total 37507
telemt_handshake_timeouts_total 92384
telemt_upstream_connect_attempt_total 24026
telemt_upstream_connect_success_total 23889
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 24026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2239
telemt_me_reconnect_attempts_total 27831
telemt_me_reconnect_success_total 17740
telemt_me_reader_eof_total 19064
telemt_me_idle_close_by_peer_total 19063
telemt_me_route_drop_no_conn_total 1454332
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3582319
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14224
telemt_desync_full_logged_total 3754
telemt_desync_suppressed_total 10470
telemt_desync_frames_bucket_total{bucket="1_2"} 3561
telemt_desync_frames_bucket_total{bucket="3_10"} 5386
telemt_desync_frames_bucket_total{bucket="gt_10"} 5277
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18298
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17727
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 3582125
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 49692657400 (46.28 GB)
telemt_user_octets_to_client{user="hello"} 1120104104496 (1.02 TB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 23775.0 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348349
telemt_connections_bad_total 22623
telemt_handshake_timeouts_total 9820
telemt_upstream_connect_attempt_total 5608
telemt_upstream_connect_success_total 5520
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 5608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 6575
telemt_me_reconnect_success_total 4280
telemt_me_reader_eof_total 4526
telemt_me_idle_close_by_peer_total 4525
telemt_me_route_drop_no_conn_total 125965
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307243
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1124
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4407
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 4273
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 307272
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 3062886664 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 87629231588 (81.61 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 153731.7 (42h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2885299
telemt_connections_bad_total 28046
telemt_handshake_timeouts_total 193999
telemt_upstream_connect_attempt_total 34345
telemt_upstream_connect_success_total 34335
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3315
telemt_me_reconnect_attempts_total 28916
telemt_me_reconnect_success_total 26364
telemt_me_reader_eof_total 27958
telemt_me_idle_close_by_peer_total 27957
telemt_me_route_drop_no_conn_total 978162
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2373909
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8345
telemt_desync_full_logged_total 2766
telemt_desync_suppressed_total 5579
telemt_desync_frames_bucket_total{bucket="1_2"} 1341
telemt_desync_frames_bucket_total{bucket="3_10"} 3047
telemt_desync_frames_bucket_total{bucket="gt_10"} 3957
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 26673
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26323
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 2373284
telemt_user_connections_current{user="hello"} 1000
telemt_user_octets_from_client{user="hello"} 38688913140 (36.03 GB)
telemt_user_octets_to_client{user="hello"} 824673563677 (768.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 153732.0 (42h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1849567
telemt_connections_bad_total 18164
telemt_handshake_timeouts_total 160317
telemt_upstream_connect_attempt_total 48217
telemt_upstream_connect_success_total 45881
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 47943
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11897
telemt_me_reconnect_attempts_total 41364
telemt_me_reconnect_success_total 32390
telemt_me_reader_eof_total 34792
telemt_me_idle_close_by_peer_total 34785
telemt_me_route_drop_no_conn_total 659887
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1530241
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3068
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 2075
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 32925
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32366
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 1534941
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 23679123253 (22.05 GB)
telemt_user_octets_to_client{user="hello"} 583644180370 (543.56 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 23167.7 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376450
telemt_connections_bad_total 4162
telemt_handshake_timeouts_total 3400
telemt_upstream_connect_attempt_total 5149
telemt_upstream_connect_success_total 5001
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 5149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 14396
telemt_me_reconnect_success_total 3819
telemt_me_reader_eof_total 4223
telemt_me_idle_close_by_peer_total 4223
telemt_me_route_drop_no_conn_total 147604
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352343
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1174
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4174
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3815
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 352318
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 4050026392 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 113665566708 (105.86 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 100
```