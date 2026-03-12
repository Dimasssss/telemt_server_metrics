# Server Metrics 2026-03-12 08:02:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7413.1 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221232
telemt_connections_bad_total 1206
telemt_handshake_timeouts_total 1762
telemt_upstream_connect_attempt_total 1503
telemt_upstream_connect_success_total 1493
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1100
telemt_me_idle_close_by_peer_total 1100
telemt_me_route_drop_no_conn_total 74322
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213645
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1018
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1075
telemt_me_writer_restored_same_endpoint_total 1060
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 213561
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 3649624148 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 62567984332 (58.27 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37033.5 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189259
telemt_connections_bad_total 2598
telemt_handshake_timeouts_total 7103
telemt_upstream_connect_attempt_total 9651
telemt_upstream_connect_success_total 9645
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 7626
telemt_me_reconnect_success_total 7586
telemt_me_reader_eof_total 8055
telemt_me_idle_close_by_peer_total 8055
telemt_me_route_drop_no_conn_total 54847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164545
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7647
telemt_me_writer_restored_same_endpoint_total 7577
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 164842
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 2499972887 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 65982195094 (61.45 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37033.3 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565533
telemt_connections_bad_total 2603
telemt_handshake_timeouts_total 42204
telemt_upstream_connect_attempt_total 9799
telemt_upstream_connect_success_total 9794
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7630
telemt_me_reconnect_success_total 7561
telemt_me_reader_eof_total 7931
telemt_me_idle_close_by_peer_total 7931
telemt_me_route_drop_no_conn_total 107059
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311734
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1430
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 992
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 496
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7554
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7520
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 312014
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 3484028216 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 110168446649 (102.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37033.8 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263050
telemt_connections_bad_total 1786
telemt_handshake_timeouts_total 17753
telemt_upstream_connect_attempt_total 10383
telemt_upstream_connect_success_total 10342
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 738
telemt_me_reconnect_attempts_total 8496
telemt_me_reconnect_success_total 8467
telemt_me_reader_eof_total 8979
telemt_me_idle_close_by_peer_total 8979
telemt_me_route_drop_no_conn_total 86973
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217371
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8519
telemt_me_writer_restored_same_endpoint_total 8446
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 217206
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2508270456 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 74888518004 (69.75 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37033.5 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287554
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 2283
telemt_upstream_connect_attempt_total 12448
telemt_upstream_connect_success_total 12301
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 12448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 551
telemt_me_reconnect_attempts_total 11929
telemt_me_reconnect_success_total 10416
telemt_me_reader_eof_total 10838
telemt_me_idle_close_by_peer_total 10838
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 90393
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270403
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1099
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 431
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10558
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10395
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 270352
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 2679192940 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 65085591660 (60.62 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 92
```