# Server Metrics 2026-03-12 04:02:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22642.9 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203606
telemt_connections_bad_total 1368
telemt_handshake_timeouts_total 3542
telemt_upstream_connect_attempt_total 5200
telemt_upstream_connect_success_total 5200
telemt_upstream_connect_attempts_per_request{bucket="1"} 5200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 4051
telemt_me_reconnect_success_total 4035
telemt_me_reader_eof_total 4266
telemt_me_idle_close_by_peer_total 4266
telemt_me_route_drop_no_conn_total 72859
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193088
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4077
telemt_me_writer_restored_same_endpoint_total 4019
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 192867
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 1769484092 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 60086579864 (55.96 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22643.7 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67995
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1293
telemt_upstream_connect_attempt_total 6369
telemt_upstream_connect_success_total 6366
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 5035
telemt_me_reconnect_success_total 5003
telemt_me_reader_eof_total 5315
telemt_me_idle_close_by_peer_total 5315
telemt_me_route_drop_no_conn_total 19696
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5041
telemt_me_writer_restored_same_endpoint_total 4994
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 63339
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1053403971 (1004.60 MB)
telemt_user_octets_to_client{user="hello"} 21352736694 (19.89 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22643.5 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338844
telemt_connections_bad_total 1754
telemt_handshake_timeouts_total 20644
telemt_upstream_connect_attempt_total 6710
telemt_upstream_connect_success_total 6708
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 5235
telemt_me_reconnect_success_total 5179
telemt_me_reader_eof_total 5397
telemt_me_idle_close_by_peer_total 5397
telemt_me_route_drop_no_conn_total 36894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117190
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5145
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5138
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 117506
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 1072770412 (1023.07 MB)
telemt_user_octets_to_client{user="hello"} 36037889225 (33.56 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22643.9 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104237
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 5795
telemt_upstream_connect_attempt_total 6746
telemt_upstream_connect_success_total 6715
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 6746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 5563
telemt_me_reconnect_success_total 5543
telemt_me_reader_eof_total 5882
telemt_me_idle_close_by_peer_total 5882
telemt_me_route_drop_no_conn_total 35434
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96845
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5579
telemt_me_writer_restored_same_endpoint_total 5522
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 96835
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 756100000 (721.07 MB)
telemt_user_octets_to_client{user="hello"} 26676982644 (24.84 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22643.6 (6h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123758
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 739
telemt_upstream_connect_attempt_total 8416
telemt_upstream_connect_success_total 8327
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 8416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 8644
telemt_me_reconnect_success_total 7143
telemt_me_reader_eof_total 7409
telemt_me_idle_close_by_peer_total 7409
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 33306
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118277
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 445
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 292
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7246
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 7126
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 118252
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 760450084 (725.22 MB)
telemt_user_octets_to_client{user="hello"} 25683792904 (23.92 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 55
```