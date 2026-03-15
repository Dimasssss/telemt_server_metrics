# Server Metrics 2026-03-15 03:57:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 20592.1 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253049
telemt_connections_bad_total 3502
telemt_handshake_timeouts_total 1265
telemt_upstream_connect_attempt_total 4380
telemt_upstream_connect_success_total 4363
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 3352
telemt_me_reconnect_success_total 3336
telemt_me_reader_eof_total 3516
telemt_me_idle_close_by_peer_total 3516
telemt_me_route_drop_no_conn_total 78364
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223863
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 586
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3374
telemt_me_writer_restored_same_endpoint_total 3325
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 223837
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 2392715504 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 79622872260 (74.15 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 20592.6 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101465
telemt_connections_bad_total 17149
telemt_handshake_timeouts_total 3876
telemt_upstream_connect_attempt_total 6135
telemt_upstream_connect_success_total 6110
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4794
telemt_me_reconnect_success_total 4771
telemt_me_reader_eof_total 5031
telemt_me_idle_close_by_peer_total 5031
telemt_me_route_drop_no_conn_total 20128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77926
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4765
telemt_me_writer_restored_same_endpoint_total 4763
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 78222
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 1696310323 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 23331729644 (21.73 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 20592.7 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176409
telemt_connections_bad_total 3603
telemt_handshake_timeouts_total 17984
telemt_upstream_connect_attempt_total 4772
telemt_upstream_connect_success_total 4753
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3736
telemt_me_reconnect_success_total 3718
telemt_me_reader_eof_total 3925
telemt_me_idle_close_by_peer_total 3925
telemt_me_route_drop_no_conn_total 38028
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151705
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3757
telemt_me_writer_restored_same_endpoint_total 3699
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 151589
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 1282749756 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 46527547332 (43.33 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 20592.6 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139695
telemt_connections_bad_total 31845
telemt_handshake_timeouts_total 6101
telemt_upstream_connect_attempt_total 7160
telemt_upstream_connect_success_total 7018
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 7160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9538
telemt_me_reconnect_success_total 5985
telemt_me_reader_eof_total 6291
telemt_me_idle_close_by_peer_total 6291
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 27995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99775
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6148
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5965
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 99780
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 789149568 (752.59 MB)
telemt_user_octets_to_client{user="hello"} 28488722044 (26.53 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 20593.3 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85652
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1037
telemt_upstream_connect_attempt_total 4755
telemt_upstream_connect_success_total 4734
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3718
telemt_me_reconnect_success_total 3703
telemt_me_reader_eof_total 3944
telemt_me_idle_close_by_peer_total 3944
telemt_me_route_drop_no_conn_total 22397
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81918
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3738
telemt_me_writer_restored_same_endpoint_total 3695
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 81916
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 697845084 (665.52 MB)
telemt_user_octets_to_client{user="hello"} 26101896188 (24.31 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 54
```