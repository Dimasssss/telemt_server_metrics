# Server Metrics 2026-03-12 07:57:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7106.6 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210712
telemt_connections_bad_total 1206
telemt_handshake_timeouts_total 1736
telemt_upstream_connect_attempt_total 1410
telemt_upstream_connect_success_total 1401
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 617
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1030
telemt_me_reconnect_success_total 1025
telemt_me_reader_eof_total 1044
telemt_me_idle_close_by_peer_total 1044
telemt_me_route_drop_no_conn_total 70537
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203426
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 977
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1026
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 203344
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 3156103440 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 59549686540 (55.46 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36727.0 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185969
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 7039
telemt_upstream_connect_attempt_total 9533
telemt_upstream_connect_success_total 9527
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 589
telemt_me_reconnect_attempts_total 7551
telemt_me_reconnect_success_total 7511
telemt_me_reader_eof_total 7967
telemt_me_idle_close_by_peer_total 7967
telemt_me_route_drop_no_conn_total 53757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161414
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7570
telemt_me_writer_restored_same_endpoint_total 7502
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 161707
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 2441956763 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 64707740662 (60.26 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 36726.8 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558154
telemt_connections_bad_total 2583
telemt_handshake_timeouts_total 41688
telemt_upstream_connect_attempt_total 9706
telemt_upstream_connect_success_total 9701
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 505
telemt_me_reconnect_attempts_total 7580
telemt_me_reconnect_success_total 7511
telemt_me_reader_eof_total 7876
telemt_me_idle_close_by_peer_total 7876
telemt_me_route_drop_no_conn_total 104695
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305062
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1386
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 482
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7504
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7470
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 305343
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 3262013376 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 108782623657 (101.31 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 36727.3 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258486
telemt_connections_bad_total 1786
telemt_handshake_timeouts_total 16783
telemt_upstream_connect_attempt_total 10264
telemt_upstream_connect_success_total 10224
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 738
telemt_me_reconnect_attempts_total 8422
telemt_me_reconnect_success_total 8392
telemt_me_reader_eof_total 8901
telemt_me_idle_close_by_peer_total 8901
telemt_me_route_drop_no_conn_total 85385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213725
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 362
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8445
telemt_me_writer_restored_same_endpoint_total 8371
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 213581
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 2470064596 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 72445481464 (67.47 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36727.0 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283120
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 2263
telemt_upstream_connect_attempt_total 12321
telemt_upstream_connect_success_total 12175
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 12321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 549
telemt_me_reconnect_attempts_total 11846
telemt_me_reconnect_success_total 10333
telemt_me_reader_eof_total 10743
telemt_me_idle_close_by_peer_total 10743
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 88496
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266084
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1080
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10475
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10312
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 266034
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 2629727684 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 63800205624 (59.42 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 84
```