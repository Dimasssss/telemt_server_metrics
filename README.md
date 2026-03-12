# Server Metrics 2026-03-12 09:28:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12610.0 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400444
telemt_connections_bad_total 1335
telemt_handshake_timeouts_total 2467
telemt_upstream_connect_attempt_total 2366
telemt_upstream_connect_success_total 2353
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 271
telemt_me_reconnect_attempts_total 1719
telemt_me_reconnect_success_total 1707
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1773
telemt_me_route_drop_no_conn_total 136545
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387365
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1814
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1361
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 691
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1723
telemt_me_writer_restored_same_endpoint_total 1694
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 387242
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 5900224396 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 105695480744 (98.44 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42230.4 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250592
telemt_connections_bad_total 2974
telemt_handshake_timeouts_total 7978
telemt_upstream_connect_attempt_total 10711
telemt_upstream_connect_success_total 10705
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 655
telemt_me_reconnect_attempts_total 8470
telemt_me_reconnect_success_total 8427
telemt_me_reader_eof_total 8953
telemt_me_idle_close_by_peer_total 8953
telemt_me_route_drop_no_conn_total 71823
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8492
telemt_me_writer_restored_same_endpoint_total 8418
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 222231
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 3210585203 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 85791128602 (79.90 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42230.2 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673004
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 49748
telemt_upstream_connect_attempt_total 10728
telemt_upstream_connect_success_total 10723
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 8344
telemt_me_reconnect_success_total 8273
telemt_me_reader_eof_total 8693
telemt_me_idle_close_by_peer_total 8693
telemt_me_route_drop_no_conn_total 142170
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408541
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1852
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1293
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8273
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8232
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 408807
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 5075614196 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 137217927069 (127.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42230.7 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332712
telemt_connections_bad_total 1827
telemt_handshake_timeouts_total 23709
telemt_upstream_connect_attempt_total 11512
telemt_upstream_connect_success_total 11466
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 810
telemt_me_reconnect_attempts_total 9400
telemt_me_reconnect_success_total 9365
telemt_me_reader_eof_total 9935
telemt_me_idle_close_by_peer_total 9935
telemt_me_route_drop_no_conn_total 112911
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 554
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9425
telemt_me_writer_restored_same_endpoint_total 9344
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 279477
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 3313280416 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 106560624080 (99.24 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42230.5 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372604
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 2742
telemt_upstream_connect_attempt_total 13678
telemt_upstream_connect_success_total 13514
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 13678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 588
telemt_me_reconnect_attempts_total 12926
telemt_me_reconnect_success_total 11409
telemt_me_reader_eof_total 11890
telemt_me_idle_close_by_peer_total 11890
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 119568
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351765
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1485
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1002
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11559
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11387
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 351702
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 3805246220 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 84614388020 (78.80 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 94
```