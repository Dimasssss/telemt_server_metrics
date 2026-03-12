# Server Metrics 2026-03-12 05:24:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27542.8 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293140
telemt_connections_bad_total 1397
telemt_handshake_timeouts_total 5080
telemt_upstream_connect_attempt_total 6170
telemt_upstream_connect_success_total 6170
telemt_upstream_connect_attempts_per_request{bucket="1"} 6170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4806
telemt_me_reconnect_success_total 4788
telemt_me_reader_eof_total 5066
telemt_me_idle_close_by_peer_total 5066
telemt_me_route_drop_no_conn_total 104776
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278999
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4838
telemt_me_writer_restored_same_endpoint_total 4772
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 278719
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 2677966284 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 86436773264 (80.50 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27543.4 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95912
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 1848
telemt_upstream_connect_attempt_total 7495
telemt_upstream_connect_success_total 7490
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 5946
telemt_me_reconnect_success_total 5911
telemt_me_reader_eof_total 6285
telemt_me_idle_close_by_peer_total 6285
telemt_me_route_drop_no_conn_total 28609
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5960
telemt_me_writer_restored_same_endpoint_total 5902
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 87085
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1406676755 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 35542710722 (33.10 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27543.3 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396937
telemt_connections_bad_total 2069
telemt_handshake_timeouts_total 26395
telemt_upstream_connect_attempt_total 7787
telemt_upstream_connect_success_total 7785
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 6095
telemt_me_reconnect_success_total 6033
telemt_me_reader_eof_total 6312
telemt_me_idle_close_by_peer_total 6312
telemt_me_route_drop_no_conn_total 53631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162782
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 637
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6008
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5992
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 163098
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 1591030036 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 49926110473 (46.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27543.6 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138989
telemt_connections_bad_total 1689
telemt_handshake_timeouts_total 9337
telemt_upstream_connect_attempt_total 8062
telemt_upstream_connect_success_total 8027
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 8062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 6658
telemt_me_reconnect_success_total 6635
telemt_me_reader_eof_total 7043
telemt_me_idle_close_by_peer_total 7043
telemt_me_route_drop_no_conn_total 46853
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125846
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6676
telemt_me_writer_restored_same_endpoint_total 6614
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 125823
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1112408908 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 36020584672 (33.55 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27543.4 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160453
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 10026
telemt_upstream_connect_success_total 9914
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 10026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 10017
telemt_me_reconnect_success_total 8511
telemt_me_reader_eof_total 8856
telemt_me_idle_close_by_peer_total 8856
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 45907
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 572
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 8629
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8492
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 153308
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 1224305752 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 34227569492 (31.88 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 68
```