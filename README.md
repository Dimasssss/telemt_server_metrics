# Server Metrics 2026-03-14 19:17:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 21598.6 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865163
telemt_connections_bad_total 40367
telemt_handshake_timeouts_total 12686
telemt_upstream_connect_attempt_total 4021
telemt_upstream_connect_success_total 4004
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3693
telemt_me_reconnect_success_total 2890
telemt_me_reader_eof_total 3039
telemt_me_idle_close_by_peer_total 3039
telemt_me_route_drop_no_conn_total 331040
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762762
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2608
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1861
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 1001
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2964
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2881
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 762707
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 13594865012 (12.66 GB)
telemt_user_octets_to_client{user="hello"} 253350585160 (235.95 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 21603.7 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333594
telemt_connections_bad_total 23098
telemt_handshake_timeouts_total 10099
telemt_upstream_connect_attempt_total 4451
telemt_upstream_connect_success_total 4398
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 386
telemt_me_reconnect_attempts_total 4079
telemt_me_reconnect_success_total 3286
telemt_me_reader_eof_total 3445
telemt_me_idle_close_by_peer_total 3445
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 103754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281004
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1190
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 824
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3380
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3270
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 280935
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 3806189936 (3.54 GB)
telemt_user_octets_to_client{user="hello"} 98393152152 (91.64 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 21466.5 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697929
telemt_connections_bad_total 2880
telemt_handshake_timeouts_total 137129
telemt_upstream_connect_attempt_total 4179
telemt_upstream_connect_success_total 4165
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 6973
telemt_me_reconnect_success_total 3065
telemt_me_reader_eof_total 3292
telemt_me_idle_close_by_peer_total 3292
telemt_me_route_drop_no_conn_total 169530
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476657
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1693
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 590
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3216
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3032
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 476485
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 6983675436 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 170081484800 (158.40 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 21321.1 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386376
telemt_connections_bad_total 88198
telemt_handshake_timeouts_total 45769
telemt_upstream_connect_attempt_total 5053
telemt_upstream_connect_success_total 5052
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 181
telemt_me_reconnect_attempts_total 4877
telemt_me_reconnect_success_total 3960
telemt_me_reader_eof_total 4139
telemt_me_idle_close_by_peer_total 4139
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 87185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246064
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 541
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4033
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3950
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 245996
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 3638977200 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 78728556832 (73.32 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 21616.5 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328551
telemt_connections_bad_total 1245
telemt_handshake_timeouts_total 3557
telemt_upstream_connect_attempt_total 4458
telemt_upstream_connect_success_total 4368
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 3945
telemt_me_reconnect_success_total 3274
telemt_me_reader_eof_total 3445
telemt_me_idle_close_by_peer_total 3445
telemt_me_route_drop_no_conn_total 102325
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3358
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3256
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 304711
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 4700467472 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 129614067168 (120.71 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 89
```