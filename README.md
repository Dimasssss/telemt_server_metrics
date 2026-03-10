# Server Metrics 2026-03-10 15:51:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5054.1 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184228
telemt_connections_bad_total 867
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 1054
telemt_upstream_connect_success_total 1049
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 4820
telemt_me_reconnect_success_total 748
telemt_me_reader_eof_total 831
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 82556
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175214
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 569
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_me_writer_removed_unexpected_total 864
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 175164
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 2287126108 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 48997033312 (45.63 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 5110.7 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72733
telemt_connections_bad_total 1480
telemt_handshake_timeouts_total 6513
telemt_upstream_connect_attempt_total 1090
telemt_upstream_connect_success_total 1083
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 795
telemt_me_reconnect_success_total 789
telemt_me_reader_eof_total 798
telemt_me_idle_close_by_peer_total 798
telemt_me_route_drop_no_conn_total 18915
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60401
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 333
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_user_connections_total{user="hello"} 60388
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 787839436 (751.34 MB)
telemt_user_octets_to_client{user="hello"} 17372825368 (16.18 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 5110.6 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128135
telemt_connections_bad_total 409
telemt_handshake_timeouts_total 6569
telemt_upstream_connect_attempt_total 2281
telemt_upstream_connect_success_total 2241
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 2281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 935
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 41680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108850
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 240
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_restored_same_endpoint_total 903
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 109850
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 1140363341 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 31738867681 (29.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 5111.1 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85256
telemt_connections_bad_total 5049
telemt_handshake_timeouts_total 8599
telemt_upstream_connect_attempt_total 1111
telemt_upstream_connect_success_total 1111
telemt_upstream_connect_attempts_per_request{bucket="1"} 1111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 479
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 825
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 27731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 817
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 67506
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 967898348 (923.06 MB)
telemt_user_octets_to_client{user="hello"} 16293077940 (15.17 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 5110.8 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94384
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 760
telemt_upstream_connect_attempt_total 1474
telemt_upstream_connect_success_total 1468
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1177
telemt_me_reconnect_success_total 1169
telemt_me_reader_eof_total 1189
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 34893
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87161
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 499
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_restored_same_endpoint_total 1169
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 87118
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 1523399808 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 23885259664 (22.24 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 112
```