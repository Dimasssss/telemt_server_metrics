# Server Metrics 2026-03-14 14:30:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 4384.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177770
telemt_connections_bad_total 3935
telemt_handshake_timeouts_total 2513
telemt_upstream_connect_attempt_total 853
telemt_upstream_connect_success_total 848
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 68003
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163466
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 623
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 163461
telemt_user_connections_current{user="hello"} 1931
telemt_user_octets_from_client{user="hello"} 2627681144 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 45609203528 (42.48 GB)
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 4389.7 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69662
telemt_connections_bad_total 4544
telemt_handshake_timeouts_total 2641
telemt_upstream_connect_attempt_total 930
telemt_upstream_connect_success_total 925
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 671
telemt_me_reader_eof_total 665
telemt_me_idle_close_by_peer_total 665
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 22290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56773
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 56732
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 794423544 (757.62 MB)
telemt_user_octets_to_client{user="hello"} 28069189508 (26.14 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 4252.7 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120346
telemt_connections_bad_total 367
telemt_handshake_timeouts_total 15592
telemt_upstream_connect_attempt_total 876
telemt_upstream_connect_success_total 872
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 627
telemt_me_reconnect_success_total 619
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 35485
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98127
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 610
telemt_me_writer_restored_same_endpoint_total 586
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 98094
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 1334198880 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 27653997196 (25.75 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 4107.1 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65946
telemt_connections_bad_total 18559
telemt_handshake_timeouts_total 9752
telemt_upstream_connect_attempt_total 1188
telemt_upstream_connect_success_total 1188
telemt_upstream_connect_attempts_per_request{bucket="1"} 1188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 944
telemt_me_reconnect_success_total 938
telemt_me_reader_eof_total 941
telemt_me_idle_close_by_peer_total 941
telemt_me_route_drop_no_conn_total 14351
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_restored_same_endpoint_total 937
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 36555
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 852763440 (813.26 MB)
telemt_user_octets_to_client{user="hello"} 9790900948 (9.12 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 4402.4 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70147
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 996
telemt_upstream_connect_success_total 978
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1376
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 754
telemt_me_idle_close_by_peer_total 754
telemt_me_route_drop_no_conn_total 24497
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64511
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 764
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 64512
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 984600728 (938.99 MB)
telemt_user_octets_to_client{user="hello"} 22324971804 (20.79 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 108
```