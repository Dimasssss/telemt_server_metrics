# Server Metrics 2026-03-12 13:59:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 28825.3 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015053
telemt_connections_bad_total 10409
telemt_handshake_timeouts_total 10327
telemt_upstream_connect_attempt_total 5702
telemt_upstream_connect_success_total 5668
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 385
telemt_me_reconnect_attempts_total 8109
telemt_me_reconnect_success_total 4209
telemt_me_reader_eof_total 4496
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 359756
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 962829
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5102
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 1846
telemt_desync_frames_bucket_total{bucket="gt_10"} 1981
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4381
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4196
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 962591
telemt_user_connections_current{user="hello"} 1634
telemt_user_octets_from_client{user="hello"} 15886541372 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 284497030620 (264.96 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58445.7 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484175
telemt_connections_bad_total 5332
telemt_handshake_timeouts_total 25319
telemt_upstream_connect_attempt_total 14003
telemt_upstream_connect_success_total 13996
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 10973
telemt_me_reconnect_success_total 10913
telemt_me_reader_eof_total 11607
telemt_me_idle_close_by_peer_total 11607
telemt_me_route_drop_no_conn_total 139834
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429620
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1505
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11014
telemt_me_writer_restored_same_endpoint_total 10904
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 430087
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 6640339595 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 155105401638 (144.45 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 58445.7 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051310
telemt_connections_bad_total 5513
telemt_handshake_timeouts_total 77299
telemt_upstream_connect_attempt_total 13944
telemt_upstream_connect_success_total 13939
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 925
telemt_me_reconnect_attempts_total 10775
telemt_me_reconnect_success_total 10678
telemt_me_reader_eof_total 11252
telemt_me_idle_close_by_peer_total 11252
telemt_me_route_drop_no_conn_total 271749
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3207
telemt_desync_full_logged_total 977
telemt_desync_suppressed_total 2230
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 1162
telemt_desync_frames_bucket_total{bucket="gt_10"} 1577
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10715
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10637
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 749766
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 9976914384 (9.29 GB)
telemt_user_octets_to_client{user="hello"} 241880806453 (225.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 58446.1 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606329
telemt_connections_bad_total 7681
telemt_handshake_timeouts_total 55209
telemt_upstream_connect_attempt_total 15495
telemt_upstream_connect_success_total 15433
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1311
telemt_me_reconnect_attempts_total 13761
telemt_me_reconnect_success_total 12527
telemt_me_reader_eof_total 13286
telemt_me_idle_close_by_peer_total 13286
telemt_me_route_drop_no_conn_total 203671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 671
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12662
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12506
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 511605
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 5660480852 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 207642144976 (193.38 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 58446.1 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684154
telemt_connections_bad_total 2369
telemt_handshake_timeouts_total 5501
telemt_upstream_connect_attempt_total 18382
telemt_upstream_connect_success_total 18160
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 18382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 22480
telemt_me_reconnect_success_total 15253
telemt_me_reader_eof_total 15997
telemt_me_idle_close_by_peer_total 15997
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 234165
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636319
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2626
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1747
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 975
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 15631
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15224
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 636223
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 7314592720 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 174305392648 (162.33 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 105
```