# Server Metrics 2026-03-12 09:59:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 14445.6 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465343
telemt_connections_bad_total 1459
telemt_handshake_timeouts_total 2704
telemt_upstream_connect_attempt_total 2844
telemt_upstream_connect_success_total 2827
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 3373
telemt_me_reconnect_success_total 2081
telemt_me_reader_eof_total 2188
telemt_me_idle_close_by_peer_total 2188
telemt_me_route_drop_no_conn_total 159113
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2097
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 531
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2138
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 2068
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 450353
telemt_user_connections_current{user="hello"} 1453
telemt_user_octets_from_client{user="hello"} 6659571360 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 122534583372 (114.12 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44066.1 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273754
telemt_connections_bad_total 2982
telemt_handshake_timeouts_total 8341
telemt_upstream_connect_attempt_total 11090
telemt_upstream_connect_success_total 11084
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 662
telemt_me_reconnect_attempts_total 8760
telemt_me_reconnect_success_total 8717
telemt_me_reader_eof_total 9265
telemt_me_idle_close_by_peer_total 9265
telemt_me_route_drop_no_conn_total 79452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8786
telemt_me_writer_restored_same_endpoint_total 8708
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 244426
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 3379830451 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 92088357130 (85.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44065.9 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 711292
telemt_connections_bad_total 3402
telemt_handshake_timeouts_total 52243
telemt_upstream_connect_attempt_total 11125
telemt_upstream_connect_success_total 11119
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 8654
telemt_me_reconnect_success_total 8580
telemt_me_reader_eof_total 9017
telemt_me_idle_close_by_peer_total 9017
telemt_me_route_drop_no_conn_total 155322
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443191
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2041
telemt_desync_full_logged_total 611
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8588
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8539
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 443450
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 5391192696 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 146930002797 (136.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44066.3 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355727
telemt_connections_bad_total 1836
telemt_handshake_timeouts_total 25876
telemt_upstream_connect_attempt_total 12018
telemt_upstream_connect_success_total 11970
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 12018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 818
telemt_me_reconnect_attempts_total 9817
telemt_me_reconnect_success_total 9780
telemt_me_reader_eof_total 10373
telemt_me_idle_close_by_peer_total 10373
telemt_me_route_drop_no_conn_total 121431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299966
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 657
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9843
telemt_me_writer_restored_same_endpoint_total 9759
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 299791
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 3697327860 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 118155983016 (110.04 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44066.3 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404035
telemt_connections_bad_total 409
telemt_handshake_timeouts_total 3102
telemt_upstream_connect_attempt_total 14277
telemt_upstream_connect_success_total 14109
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 14277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 620
telemt_me_reconnect_attempts_total 13434
telemt_me_reconnect_success_total 11911
telemt_me_reader_eof_total 12399
telemt_me_idle_close_by_peer_total 12399
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 130637
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381909
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1629
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 12070
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11889
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 381842
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 4241482736 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 91732532632 (85.43 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 109
```