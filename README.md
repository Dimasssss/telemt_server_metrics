# Server Metrics 2026-03-12 03:47:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21725.3 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191650
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 3400
telemt_upstream_connect_attempt_total 4980
telemt_upstream_connect_success_total 4980
telemt_upstream_connect_attempts_per_request{bucket="1"} 4980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 3874
telemt_me_reconnect_success_total 3857
telemt_me_reader_eof_total 4070
telemt_me_idle_close_by_peer_total 4070
telemt_me_route_drop_no_conn_total 68689
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3898
telemt_me_writer_restored_same_endpoint_total 3841
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 181381
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 1651558804 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 56531414468 (52.65 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21725.9 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63557
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1160
telemt_upstream_connect_attempt_total 6156
telemt_upstream_connect_success_total 6153
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4865
telemt_me_reconnect_success_total 4834
telemt_me_reader_eof_total 5130
telemt_me_idle_close_by_peer_total 5130
telemt_me_route_drop_no_conn_total 18030
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59406
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4871
telemt_me_writer_restored_same_endpoint_total 4825
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 59586
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 1007308307 (960.64 MB)
telemt_user_octets_to_client{user="hello"} 20555845790 (19.14 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21725.6 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330635
telemt_connections_bad_total 1577
telemt_handshake_timeouts_total 19660
telemt_upstream_connect_attempt_total 6491
telemt_upstream_connect_success_total 6489
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 5060
telemt_me_reconnect_success_total 5004
telemt_me_reader_eof_total 5208
telemt_me_idle_close_by_peer_total 5208
telemt_me_route_drop_no_conn_total 34702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110421
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4968
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4963
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 110741
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1009734592 (962.96 MB)
telemt_user_octets_to_client{user="hello"} 34086473413 (31.75 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21725.9 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98580
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 5209
telemt_upstream_connect_attempt_total 6486
telemt_upstream_connect_success_total 6458
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 5350
telemt_me_reconnect_success_total 5331
telemt_me_reader_eof_total 5651
telemt_me_idle_close_by_peer_total 5651
telemt_me_route_drop_no_conn_total 33460
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91836
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5364
telemt_me_writer_restored_same_endpoint_total 5310
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 91825
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 692332364 (660.26 MB)
telemt_user_octets_to_client{user="hello"} 23436494172 (21.83 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21725.8 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117823
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 7967
telemt_upstream_connect_success_total 7883
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 7967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 8244
telemt_me_reconnect_success_total 6744
telemt_me_reader_eof_total 7002
telemt_me_idle_close_by_peer_total 7002
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 31004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112574
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 421
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6839
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 112549
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 698898292 (666.52 MB)
telemt_user_octets_to_client{user="hello"} 24593133612 (22.90 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```