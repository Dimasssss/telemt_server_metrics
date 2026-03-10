# Server Metrics 2026-03-10 17:38:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11483.7 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383071
telemt_connections_bad_total 3171
telemt_handshake_timeouts_total 1848
telemt_upstream_connect_attempt_total 2205
telemt_upstream_connect_success_total 2196
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 264
telemt_me_reconnect_attempts_total 10837
telemt_me_reconnect_success_total 1572
telemt_me_reader_eof_total 1820
telemt_me_idle_close_by_peer_total 1820
telemt_me_route_drop_no_conn_total 165336
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366794
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1759
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 1270
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1860
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1566
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 366723
telemt_user_connections_current{user="hello"} 1386
telemt_user_octets_from_client{user="hello"} 4839729880 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 106792963160 (99.46 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11540.5 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150859
telemt_connections_bad_total 1691
telemt_handshake_timeouts_total 9779
telemt_upstream_connect_attempt_total 2601
telemt_upstream_connect_success_total 2588
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 1995
telemt_me_reconnect_success_total 1984
telemt_me_reader_eof_total 2056
telemt_me_idle_close_by_peer_total 2056
telemt_me_route_drop_no_conn_total 43683
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1995
telemt_me_writer_restored_same_endpoint_total 1963
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 131520
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1677251156 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 35231421776 (32.81 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11540.2 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289879
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 30974
telemt_upstream_connect_attempt_total 3906
telemt_upstream_connect_success_total 3840
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 3376
telemt_me_reconnect_success_total 2183
telemt_me_reader_eof_total 2288
telemt_me_idle_close_by_peer_total 2288
telemt_me_route_drop_no_conn_total 93538
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235350
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 714
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2256
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2172
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 236325
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 3257428957 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 68989560037 (64.25 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11540.8 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184397
telemt_connections_bad_total 11277
telemt_handshake_timeouts_total 18279
telemt_upstream_connect_attempt_total 2902
telemt_upstream_connect_success_total 2902
telemt_upstream_connect_attempts_per_request{bucket="1"} 2902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1340
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2305
telemt_me_reconnect_success_total 2291
telemt_me_reader_eof_total 2373
telemt_me_idle_close_by_peer_total 2373
telemt_me_route_drop_no_conn_total 59433
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 467
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2309
telemt_me_writer_restored_same_endpoint_total 2280
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 146829
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 2401253104 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 41808238304 (38.94 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11540.5 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197173
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 1593
telemt_upstream_connect_attempt_total 3482
telemt_upstream_connect_success_total 3472
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 2866
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2926
telemt_me_idle_close_by_peer_total 2926
telemt_me_route_drop_no_conn_total 72409
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185105
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 993
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 647
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2873
telemt_me_writer_restored_same_endpoint_total 2848
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 185042
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 4180617600 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 54914403932 (51.14 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 73
```