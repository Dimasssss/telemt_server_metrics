# Server Metrics 2026-03-14 19:07:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 20984.3 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842600
telemt_connections_bad_total 40362
telemt_handshake_timeouts_total 12298
telemt_upstream_connect_attempt_total 3987
telemt_upstream_connect_success_total 3970
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3659
telemt_me_reconnect_success_total 2856
telemt_me_reader_eof_total 3003
telemt_me_idle_close_by_peer_total 3003
telemt_me_route_drop_no_conn_total 323143
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744709
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2526
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1797
telemt_desync_frames_bucket_total{bucket="1_2"} 605
telemt_desync_frames_bucket_total{bucket="3_10"} 946
telemt_desync_frames_bucket_total{bucket="gt_10"} 975
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2928
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2847
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 744656
telemt_user_connections_current{user="hello"} 1924
telemt_user_octets_from_client{user="hello"} 13234605620 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 246615970516 (229.68 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 20989.8 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325638
telemt_connections_bad_total 23065
telemt_handshake_timeouts_total 9883
telemt_upstream_connect_attempt_total 4395
telemt_upstream_connect_success_total 4342
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 384
telemt_me_reconnect_attempts_total 4023
telemt_me_reconnect_success_total 3230
telemt_me_reader_eof_total 3387
telemt_me_idle_close_by_peer_total 3387
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 101497
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273464
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1157
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3322
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3214
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 273396
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 3749939456 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 96664004716 (90.03 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 20852.7 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682058
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 135009
telemt_upstream_connect_attempt_total 4114
telemt_upstream_connect_success_total 4100
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 6908
telemt_me_reconnect_success_total 3001
telemt_me_reader_eof_total 3222
telemt_me_idle_close_by_peer_total 3222
telemt_me_route_drop_no_conn_total 165612
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464509
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1637
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 570
telemt_desync_frames_bucket_total{bucket="gt_10"} 845
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3150
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2968
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 464380
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 6753736664 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 165717485316 (154.34 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 20707.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376639
telemt_connections_bad_total 86634
telemt_handshake_timeouts_total 45080
telemt_upstream_connect_attempt_total 4894
telemt_upstream_connect_success_total 4893
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 4761
telemt_me_reconnect_success_total 3845
telemt_me_reader_eof_total 4016
telemt_me_idle_close_by_peer_total 4016
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 84557
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238851
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 516
telemt_desync_full_logged_total 175
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3916
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3835
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 238779
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 3492264132 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 75902429288 (70.69 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 21002.7 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320115
telemt_connections_bad_total 1242
telemt_handshake_timeouts_total 3522
telemt_upstream_connect_attempt_total 4344
telemt_upstream_connect_success_total 4254
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 3831
telemt_me_reconnect_success_total 3161
telemt_me_reader_eof_total 3331
telemt_me_idle_close_by_peer_total 3331
telemt_me_route_drop_no_conn_total 99927
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296783
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 752
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3244
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3143
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 296771
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 4584351640 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 126254198936 (117.58 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 98
```