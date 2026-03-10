# Server Metrics 2026-03-10 19:46:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19142.4 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591298
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 4860
telemt_upstream_connect_attempt_total 3825
telemt_upstream_connect_success_total 3816
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 13236
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 3120
telemt_me_idle_close_by_peer_total 3120
telemt_me_route_drop_no_conn_total 247364
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558295
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2990
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 2190
telemt_desync_frames_bucket_total{bucket="1_2"} 809
telemt_desync_frames_bucket_total{bucket="3_10"} 1145
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3116
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2768
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 558118
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 8152949992 (7.59 GB)
telemt_user_octets_to_client{user="hello"} 161558772856 (150.46 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19199.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254790
telemt_connections_bad_total 1816
telemt_handshake_timeouts_total 16580
telemt_upstream_connect_attempt_total 9288
telemt_upstream_connect_success_total 6541
telemt_upstream_connect_fail_total 2747
telemt_upstream_connect_attempts_per_request{bucket="1"} 9288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1884
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2747
telemt_me_keepalive_timeout_total 713
telemt_me_reconnect_attempts_total 4324
telemt_me_reconnect_success_total 3534
telemt_me_reader_eof_total 3687
telemt_me_idle_close_by_peer_total 3685
telemt_me_route_drop_no_conn_total 140161
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217918
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1089
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 790
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3601
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3513
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 219217
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 2312042342 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 53871842786 (50.17 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19199.2 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423357
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 32370
telemt_upstream_connect_attempt_total 5916
telemt_upstream_connect_success_total 5824
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 5916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 8129
telemt_me_reconnect_success_total 3747
telemt_me_reader_eof_total 4001
telemt_me_idle_close_by_peer_total 4001
telemt_me_route_drop_no_conn_total 145516
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364351
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3953
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 3736
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 365300
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 5292548657 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 114965946217 (107.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19199.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282252
telemt_connections_bad_total 19029
telemt_handshake_timeouts_total 24810
telemt_upstream_connect_attempt_total 5216
telemt_upstream_connect_success_total 5215
telemt_upstream_connect_attempts_per_request{bucket="1"} 5215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 5214
telemt_me_reconnect_success_total 4198
telemt_me_reader_eof_total 4399
telemt_me_idle_close_by_peer_total 4399
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 92518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227042
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 605
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4271
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4185
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 226787
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 3566043184 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 67318531016 (62.70 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19199.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297256
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 1963
telemt_upstream_connect_attempt_total 5965
telemt_upstream_connect_success_total 5942
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 4937
telemt_me_reconnect_success_total 4898
telemt_me_reader_eof_total 5037
telemt_me_idle_close_by_peer_total 5037
telemt_me_route_drop_no_conn_total 109647
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280554
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1572
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 994
telemt_desync_frames_bucket_total{bucket="1_2"} 618
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4974
telemt_me_writer_restored_same_endpoint_total 4898
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 280473
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 5545598688 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 92366269868 (86.02 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 80
```