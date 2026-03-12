# Server Metrics 2026-03-12 10:35:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16584.5 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545146
telemt_connections_bad_total 1468
telemt_handshake_timeouts_total 3089
telemt_upstream_connect_attempt_total 3250
telemt_upstream_connect_success_total 3229
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 6245
telemt_me_reconnect_success_total 2359
telemt_me_reader_eof_total 2560
telemt_me_idle_close_by_peer_total 2560
telemt_me_route_drop_no_conn_total 188398
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527508
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2550
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1914
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2502
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2346
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 527372
telemt_user_connections_current{user="hello"} 1381
telemt_user_octets_from_client{user="hello"} 8230449316 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 143616645696 (133.75 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46205.2 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303361
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 8703
telemt_upstream_connect_attempt_total 11649
telemt_upstream_connect_success_total 11643
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 675
telemt_me_reconnect_attempts_total 9186
telemt_me_reconnect_success_total 9135
telemt_me_reader_eof_total 9712
telemt_me_idle_close_by_peer_total 9712
telemt_me_route_drop_no_conn_total 87820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272174
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9213
telemt_me_writer_restored_same_endpoint_total 9126
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 272607
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 3755298771 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 98972612210 (92.18 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46205.0 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758654
telemt_connections_bad_total 3717
telemt_handshake_timeouts_total 55362
telemt_upstream_connect_attempt_total 11627
telemt_upstream_connect_success_total 11622
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 588
telemt_me_reconnect_attempts_total 9026
telemt_me_reconnect_success_total 8949
telemt_me_reader_eof_total 9407
telemt_me_idle_close_by_peer_total 9407
telemt_me_route_drop_no_conn_total 170866
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2194
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1546
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 1155
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8962
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8908
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 486326
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 5768092632 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 156666927777 (145.91 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46205.3 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391103
telemt_connections_bad_total 2476
telemt_handshake_timeouts_total 29569
telemt_upstream_connect_attempt_total 12479
telemt_upstream_connect_success_total 12429
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 844
telemt_me_reconnect_attempts_total 10145
telemt_me_reconnect_success_total 10106
telemt_me_reader_eof_total 10724
telemt_me_idle_close_by_peer_total 10724
telemt_me_route_drop_no_conn_total 131866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10173
telemt_me_writer_restored_same_endpoint_total 10085
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 330189
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 3951661796 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 128047306404 (119.25 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46205.1 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441530
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 3305
telemt_upstream_connect_attempt_total 14936
telemt_upstream_connect_success_total 14757
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 14936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 632
telemt_me_reconnect_attempts_total 13950
telemt_me_reconnect_success_total 12426
telemt_me_reader_eof_total 12942
telemt_me_idle_close_by_peer_total 12942
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 143053
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416024
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1762
telemt_desync_full_logged_total 583
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12597
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12402
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 415949
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 4644136036 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 100580523700 (93.67 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 104
```