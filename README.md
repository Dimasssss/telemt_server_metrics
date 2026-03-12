# Server Metrics 2026-03-12 05:18:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27237.4 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286576
telemt_connections_bad_total 1397
telemt_handshake_timeouts_total 4816
telemt_upstream_connect_attempt_total 6132
telemt_upstream_connect_success_total 6132
telemt_upstream_connect_attempts_per_request{bucket="1"} 6132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4768
telemt_me_reconnect_success_total 4750
telemt_me_reader_eof_total 5028
telemt_me_idle_close_by_peer_total 5028
telemt_me_route_drop_no_conn_total 102669
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272858
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4800
telemt_me_writer_restored_same_endpoint_total 4734
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 272583
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 2635244376 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 84576439336 (78.77 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27236.4 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93783
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1768
telemt_upstream_connect_attempt_total 7441
telemt_upstream_connect_success_total 7438
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 7441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 5892
telemt_me_reconnect_success_total 5858
telemt_me_reader_eof_total 6234
telemt_me_idle_close_by_peer_total 6234
telemt_me_route_drop_no_conn_total 28162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85104
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
telemt_me_writer_removed_unexpected_total 5908
telemt_me_writer_restored_same_endpoint_total 5849
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 85291
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 1389850415 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 33449172766 (31.15 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27236.2 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392025
telemt_connections_bad_total 2069
telemt_handshake_timeouts_total 25998
telemt_upstream_connect_attempt_total 7732
telemt_upstream_connect_success_total 7730
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 6040
telemt_me_reconnect_success_total 5978
telemt_me_reader_eof_total 6255
telemt_me_idle_close_by_peer_total 6255
telemt_me_route_drop_no_conn_total 52466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159342
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 602
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5951
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5937
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 159657
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 1552186216 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 48769076217 (45.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27236.7 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136018
telemt_connections_bad_total 1689
telemt_handshake_timeouts_total 9094
telemt_upstream_connect_attempt_total 7978
telemt_upstream_connect_success_total 7943
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 7978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6574
telemt_me_reconnect_success_total 6552
telemt_me_reader_eof_total 6959
telemt_me_idle_close_by_peer_total 6959
telemt_me_route_drop_no_conn_total 45918
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123255
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
telemt_me_writer_removed_unexpected_total 6592
telemt_me_writer_restored_same_endpoint_total 6531
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 123232
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 1037621112 (989.55 MB)
telemt_user_octets_to_client{user="hello"} 35564750792 (33.12 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27236.4 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157841
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 937
telemt_upstream_connect_attempt_total 9959
telemt_upstream_connect_success_total 9847
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 9959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 9950
telemt_me_reconnect_success_total 8445
telemt_me_reader_eof_total 8790
telemt_me_idle_close_by_peer_total 8790
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 45236
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150872
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 561
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 8563
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 8426
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 150876
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1195464372 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 33656834948 (31.35 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 57
```