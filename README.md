# Server Metrics 2026-03-12 09:03:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11081.6 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345228
telemt_connections_bad_total 1324
telemt_handshake_timeouts_total 2312
telemt_upstream_connect_attempt_total 2125
telemt_upstream_connect_success_total 2114
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1526
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1577
telemt_me_idle_close_by_peer_total 1577
telemt_me_route_drop_no_conn_total 115529
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1528
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 333311
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 5253995704 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 92345102472 (86.00 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40702.1 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231963
telemt_connections_bad_total 2822
telemt_handshake_timeouts_total 7655
telemt_upstream_connect_attempt_total 10432
telemt_upstream_connect_success_total 10426
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 621
telemt_me_reconnect_attempts_total 8234
telemt_me_reconnect_success_total 8191
telemt_me_reader_eof_total 8706
telemt_me_idle_close_by_peer_total 8706
telemt_me_route_drop_no_conn_total 66490
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204142
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 455
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8254
telemt_me_writer_restored_same_endpoint_total 8182
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 204534
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 3031299163 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 77757664206 (72.42 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40702.0 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639657
telemt_connections_bad_total 2891
telemt_handshake_timeouts_total 47379
telemt_upstream_connect_attempt_total 10491
telemt_upstream_connect_success_total 10486
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 529
telemt_me_reconnect_attempts_total 8150
telemt_me_reconnect_success_total 8079
telemt_me_reader_eof_total 8489
telemt_me_idle_close_by_peer_total 8489
telemt_me_route_drop_no_conn_total 131577
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378371
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1714
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 904
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8077
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8038
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 378638
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 4406868048 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 127481430737 (118.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40702.3 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310930
telemt_connections_bad_total 1814
telemt_handshake_timeouts_total 21914
telemt_upstream_connect_attempt_total 11238
telemt_upstream_connect_success_total 11192
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 794
telemt_me_reconnect_attempts_total 9169
telemt_me_reconnect_success_total 9136
telemt_me_reader_eof_total 9699
telemt_me_idle_close_by_peer_total 9699
telemt_me_route_drop_no_conn_total 105303
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260001
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 508
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 321
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9194
telemt_me_writer_restored_same_endpoint_total 9115
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 259823
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 3065680908 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 93319547200 (86.91 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40702.2 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346670
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 2585
telemt_upstream_connect_attempt_total 13363
telemt_upstream_connect_success_total 13202
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 13363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 573
telemt_me_reconnect_attempts_total 12657
telemt_me_reconnect_success_total 11142
telemt_me_reader_eof_total 11606
telemt_me_idle_close_by_peer_total 11606
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 111461
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1372
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 916
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 480
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11288
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11120
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 327482
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 3540069144 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 79519870936 (74.06 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 119
```