# Server Metrics 2026-03-12 08:07:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 7719.4 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231441
telemt_connections_bad_total 1209
telemt_handshake_timeouts_total 1785
telemt_upstream_connect_attempt_total 1541
telemt_upstream_connect_success_total 1531
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 680
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1117
telemt_me_reconnect_success_total 1111
telemt_me_reader_eof_total 1138
telemt_me_idle_close_by_peer_total 1138
telemt_me_route_drop_no_conn_total 77928
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223597
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1085
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 810
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_restored_same_endpoint_total 1098
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 223513
telemt_user_connections_current{user="hello"} 1368
telemt_user_octets_from_client{user="hello"} 3746918808 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 65233980672 (60.75 GB)
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37339.9 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192965
telemt_connections_bad_total 2618
telemt_handshake_timeouts_total 7175
telemt_upstream_connect_attempt_total 9725
telemt_upstream_connect_success_total 9719
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 591
telemt_me_reconnect_attempts_total 7700
telemt_me_reconnect_success_total 7660
telemt_me_reader_eof_total 8134
telemt_me_idle_close_by_peer_total 8134
telemt_me_route_drop_no_conn_total 55792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168044
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 418
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 252
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7721
telemt_me_writer_restored_same_endpoint_total 7651
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 168340
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 2531946099 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 67019265006 (62.42 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37339.9 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572755
telemt_connections_bad_total 2693
telemt_handshake_timeouts_total 42650
telemt_upstream_connect_attempt_total 9861
telemt_upstream_connect_success_total 9856
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7692
telemt_me_reconnect_success_total 7623
telemt_me_reader_eof_total 8000
telemt_me_idle_close_by_peer_total 8000
telemt_me_route_drop_no_conn_total 109469
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318350
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1496
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 778
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7617
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7582
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 318630
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 3518386680 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 112218145517 (104.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37340.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266844
telemt_connections_bad_total 1795
telemt_handshake_timeouts_total 17944
telemt_upstream_connect_attempt_total 10450
telemt_upstream_connect_success_total 10409
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 739
telemt_me_reconnect_attempts_total 8563
telemt_me_reconnect_success_total 8534
telemt_me_reader_eof_total 9063
telemt_me_idle_close_by_peer_total 9063
telemt_me_route_drop_no_conn_total 88435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220761
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8588
telemt_me_writer_restored_same_endpoint_total 8513
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 220596
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 2545876084 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 76373687836 (71.13 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37339.8 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292174
telemt_connections_bad_total 352
telemt_handshake_timeouts_total 2306
telemt_upstream_connect_attempt_total 12518
telemt_upstream_connect_success_total 12371
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 12518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 11999
telemt_me_reconnect_success_total 10486
telemt_me_reader_eof_total 10922
telemt_me_idle_close_by_peer_total 10922
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 92487
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274906
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1115
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 738
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10629
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10465
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 274855
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 2733467684 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 66299677616 (61.75 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 100
```