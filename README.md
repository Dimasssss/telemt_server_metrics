# Server Metrics 2026-03-14 18:26:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 18530.0 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749381
telemt_connections_bad_total 39343
telemt_handshake_timeouts_total 10186
telemt_upstream_connect_attempt_total 3605
telemt_upstream_connect_success_total 3590
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3410
telemt_me_reconnect_success_total 2608
telemt_me_reader_eof_total 2736
telemt_me_idle_close_by_peer_total 2736
telemt_me_route_drop_no_conn_total 288145
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665639
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2313
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1649
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2673
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2599
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 665572
telemt_user_connections_current{user="hello"} 1802
telemt_user_octets_from_client{user="hello"} 11616364456 (10.82 GB)
telemt_user_octets_to_client{user="hello"} 218013002936 (203.04 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 18535.5 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292630
telemt_connections_bad_total 22782
telemt_handshake_timeouts_total 8888
telemt_upstream_connect_attempt_total 3836
telemt_upstream_connect_success_total 3788
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 3598
telemt_me_reconnect_success_total 2807
telemt_me_reader_eof_total 2942
telemt_me_idle_close_by_peer_total 2942
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 91433
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242670
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 961
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 660
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2894
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2792
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 242611
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 3389222744 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 88988146536 (82.88 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 18398.4 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621833
telemt_connections_bad_total 2171
telemt_handshake_timeouts_total 129849
telemt_upstream_connect_attempt_total 3674
telemt_upstream_connect_success_total 3661
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6600
telemt_me_reconnect_success_total 2695
telemt_me_reader_eof_total 2899
telemt_me_idle_close_by_peer_total 2899
telemt_me_route_drop_no_conn_total 150346
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417393
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1373
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 712
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2842
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2662
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 417300
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 6027283668 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 148937418052 (138.71 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 18252.7 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337485
telemt_connections_bad_total 79813
telemt_handshake_timeouts_total 42073
telemt_upstream_connect_attempt_total 4406
telemt_upstream_connect_success_total 4405
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4362
telemt_me_reconnect_success_total 3447
telemt_me_reader_eof_total 3593
telemt_me_idle_close_by_peer_total 3593
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 74644
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210389
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3508
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3437
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 210340
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 3132379180 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 66430053040 (61.87 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 18548.1 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285391
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 3352
telemt_upstream_connect_attempt_total 3860
telemt_upstream_connect_success_total 3783
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 3860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3491
telemt_me_reconnect_success_total 2823
telemt_me_reader_eof_total 2977
telemt_me_idle_close_by_peer_total 2977
telemt_me_route_drop_no_conn_total 90403
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263815
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2902
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2805
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 263801
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 4084398200 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 113766668904 (105.95 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 105
```