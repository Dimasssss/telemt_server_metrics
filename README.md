# Server Metrics 2026-03-14 21:35:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 29886.4 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1085041
telemt_connections_bad_total 42743
telemt_handshake_timeouts_total 14838
telemt_upstream_connect_attempt_total 5456
telemt_upstream_connect_success_total 5433
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4692
telemt_me_reconnect_success_total 3883
telemt_me_reader_eof_total 4099
telemt_me_idle_close_by_peer_total 4099
telemt_me_route_drop_no_conn_total 413896
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966976
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3216
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 2278
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1210
telemt_desync_frames_bucket_total{bucket="gt_10"} 1247
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3971
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3874
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 966945
telemt_user_connections_current{user="hello"} 1194
telemt_user_octets_from_client{user="hello"} 17339553972 (16.15 GB)
telemt_user_octets_to_client{user="hello"} 326505361632 (304.08 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 29891.7 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428104
telemt_connections_bad_total 32891
telemt_handshake_timeouts_total 13178
telemt_upstream_connect_attempt_total 6407
telemt_upstream_connect_success_total 6345
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 484
telemt_me_reconnect_attempts_total 5595
telemt_me_reconnect_success_total 4796
telemt_me_reader_eof_total 5023
telemt_me_idle_close_by_peer_total 5023
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 125152
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358223
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1782
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1314
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4918
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4773
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 358167
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 5651046460 (5.26 GB)
telemt_user_octets_to_client{user="hello"} 124991841500 (116.41 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 29754.6 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932005
telemt_connections_bad_total 3920
telemt_handshake_timeouts_total 234942
telemt_upstream_connect_attempt_total 5740
telemt_upstream_connect_success_total 5723
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 8130
telemt_me_reconnect_success_total 4216
telemt_me_reader_eof_total 4517
telemt_me_idle_close_by_peer_total 4517
telemt_me_route_drop_no_conn_total 207217
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594691
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2223
telemt_desync_full_logged_total 848
telemt_desync_suppressed_total 1375
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 775
telemt_desync_frames_bucket_total{bucket="gt_10"} 1108
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4387
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4183
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 594513
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 9140798092 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 221231043208 (206.04 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 29609.0 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492959
telemt_connections_bad_total 101604
telemt_handshake_timeouts_total 55559
telemt_upstream_connect_attempt_total 6778
telemt_upstream_connect_success_total 6777
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 6214
telemt_me_reconnect_success_total 5290
telemt_me_reader_eof_total 5555
telemt_me_idle_close_by_peer_total 5555
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 114588
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5380
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5278
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 327471
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 4571497444 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 100350640120 (93.46 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 29904.4 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413198
telemt_connections_bad_total 1406
telemt_handshake_timeouts_total 4074
telemt_upstream_connect_attempt_total 6346
telemt_upstream_connect_success_total 6221
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 5369
telemt_me_reconnect_success_total 4690
telemt_me_reader_eof_total 4961
telemt_me_idle_close_by_peer_total 4961
telemt_me_route_drop_no_conn_total 129543
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383732
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1115
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 721
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4795
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4672
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 383697
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 6037761592 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 157101695344 (146.31 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 55
```