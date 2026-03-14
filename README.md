# Server Metrics 2026-03-14 17:35:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 15463.0 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625534
telemt_connections_bad_total 34739
telemt_handshake_timeouts_total 8452
telemt_upstream_connect_attempt_total 3102
telemt_upstream_connect_success_total 3088
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3038
telemt_me_reconnect_success_total 2238
telemt_me_reader_eof_total 2341
telemt_me_idle_close_by_peer_total 2341
telemt_me_route_drop_no_conn_total 238699
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554064
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1935
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1378
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2299
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2229
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 554002
telemt_user_connections_current{user="hello"} 1659
telemt_user_octets_from_client{user="hello"} 9921890744 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 172904475600 (161.03 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 15468.3 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250055
telemt_connections_bad_total 22578
telemt_handshake_timeouts_total 8108
telemt_upstream_connect_attempt_total 3249
telemt_upstream_connect_success_total 3213
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 3151
telemt_me_reconnect_success_total 2365
telemt_me_reader_eof_total 2471
telemt_me_idle_close_by_peer_total 2471
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 77219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202784
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 755
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 290
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2445
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2350
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 202726
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 2934364876 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 78518959560 (73.13 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 15331.2 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522039
telemt_connections_bad_total 1969
telemt_handshake_timeouts_total 106826
telemt_upstream_connect_attempt_total 3081
telemt_upstream_connect_success_total 3072
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 6178
telemt_me_reconnect_success_total 2277
telemt_me_reader_eof_total 2452
telemt_me_idle_close_by_peer_total 2452
telemt_me_route_drop_no_conn_total 127674
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350188
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 154
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2416
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2244
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 350088
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 5379362332 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 126015573512 (117.36 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 15185.5 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273321
telemt_connections_bad_total 58257
telemt_handshake_timeouts_total 38934
telemt_upstream_connect_attempt_total 3703
telemt_upstream_connect_success_total 3702
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 3832
telemt_me_reconnect_success_total 2918
telemt_me_reader_eof_total 3036
telemt_me_idle_close_by_peer_total 3036
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 61901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2976
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2911
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 172200
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 2574524064 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 55074227272 (51.29 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 15480.9 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241430
telemt_connections_bad_total 933
telemt_handshake_timeouts_total 2981
telemt_upstream_connect_attempt_total 3366
telemt_upstream_connect_success_total 3300
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3137
telemt_me_reconnect_success_total 2472
telemt_me_reader_eof_total 2599
telemt_me_idle_close_by_peer_total 2599
telemt_me_route_drop_no_conn_total 78182
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222414
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2541
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2454
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 222430
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 3440126068 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 86553971124 (80.61 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 100
```