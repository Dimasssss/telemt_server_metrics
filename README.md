# Server Metrics 2026-03-12 08:53:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10469.9 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323315
telemt_connections_bad_total 1322
telemt_handshake_timeouts_total 2247
telemt_upstream_connect_attempt_total 2007
telemt_upstream_connect_success_total 1996
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 107422
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312146
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 1116
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1452
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 312037
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 4837333772 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 86153101912 (80.24 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40090.5 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223948
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 7552
telemt_upstream_connect_attempt_total 10298
telemt_upstream_connect_success_total 10292
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 613
telemt_me_reconnect_attempts_total 8143
telemt_me_reconnect_success_total 8100
telemt_me_reader_eof_total 8605
telemt_me_idle_close_by_peer_total 8605
telemt_me_route_drop_no_conn_total 64403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8162
telemt_me_writer_restored_same_endpoint_total 8091
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 196890
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 2936352031 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 74954639674 (69.81 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 40090.2 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625456
telemt_connections_bad_total 2882
telemt_handshake_timeouts_total 46378
telemt_upstream_connect_attempt_total 10373
telemt_upstream_connect_success_total 10368
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 8075
telemt_me_reconnect_success_total 8005
telemt_me_reader_eof_total 8406
telemt_me_idle_close_by_peer_total 8406
telemt_me_route_drop_no_conn_total 127323
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366416
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1674
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1169
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8000
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7964
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 366685
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 4324995332 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 123918384233 (115.41 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 40090.7 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301177
telemt_connections_bad_total 1807
telemt_handshake_timeouts_total 20252
telemt_upstream_connect_attempt_total 11051
telemt_upstream_connect_success_total 11007
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 11051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 786
telemt_me_reconnect_attempts_total 9029
telemt_me_reconnect_success_total 8997
telemt_me_reader_eof_total 9541
telemt_me_idle_close_by_peer_total 9541
telemt_me_route_drop_no_conn_total 101280
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252057
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9052
telemt_me_writer_restored_same_endpoint_total 8976
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 251881
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 2916825140 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 88749782148 (82.65 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 40090.3 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336308
telemt_connections_bad_total 374
telemt_handshake_timeouts_total 2530
telemt_upstream_connect_attempt_total 13214
telemt_upstream_connect_success_total 13060
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 13214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 12558
telemt_me_reconnect_success_total 11044
telemt_me_reader_eof_total 11508
telemt_me_idle_close_by_peer_total 11508
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 107721
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1315
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11190
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11022
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 317535
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 3451916728 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 76983353880 (71.70 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 93
```