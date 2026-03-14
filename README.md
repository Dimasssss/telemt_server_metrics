# Server Metrics 2026-03-14 17:55:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 16688.1 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675155
telemt_connections_bad_total 37630
telemt_handshake_timeouts_total 9092
telemt_upstream_connect_attempt_total 3332
telemt_upstream_connect_success_total 3318
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3225
telemt_me_reconnect_success_total 2425
telemt_me_reader_eof_total 2537
telemt_me_idle_close_by_peer_total 2537
telemt_me_route_drop_no_conn_total 256871
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597987
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2054
telemt_desync_full_logged_total 592
telemt_desync_suppressed_total 1462
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2487
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2416
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 597924
telemt_user_connections_current{user="hello"} 1857
telemt_user_octets_from_client{user="hello"} 10584328852 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 191337307716 (178.20 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 16693.6 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265795
telemt_connections_bad_total 22626
telemt_handshake_timeouts_total 8535
telemt_upstream_connect_attempt_total 3490
telemt_upstream_connect_success_total 3449
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 307
telemt_me_reconnect_attempts_total 3347
telemt_me_reconnect_success_total 2557
telemt_me_reader_eof_total 2675
telemt_me_idle_close_by_peer_total 2675
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 82365
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217408
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2639
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2542
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 217349
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 3105604904 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 82894972056 (77.20 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 16556.5 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560682
telemt_connections_bad_total 1979
telemt_handshake_timeouts_total 112034
telemt_upstream_connect_attempt_total 3336
telemt_upstream_connect_success_total 3327
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 6352
telemt_me_reconnect_success_total 2449
telemt_me_reader_eof_total 2636
telemt_me_idle_close_by_peer_total 2636
telemt_me_route_drop_no_conn_total 136741
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377540
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1144
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2592
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2416
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 377430
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 5638639768 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 135921642476 (126.59 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 16410.9 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300427
telemt_connections_bad_total 67145
telemt_handshake_timeouts_total 40865
telemt_upstream_connect_attempt_total 4001
telemt_upstream_connect_success_total 4000
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 3128
telemt_me_reader_eof_total 3268
telemt_me_idle_close_by_peer_total 3268
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 67225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188079
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3186
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3121
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 188033
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 2850331948 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 59516480584 (55.43 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 16706.6 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259453
telemt_connections_bad_total 1050
telemt_handshake_timeouts_total 3134
telemt_upstream_connect_attempt_total 3544
telemt_upstream_connect_success_total 3474
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 3544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3268
telemt_me_reconnect_success_total 2602
telemt_me_reader_eof_total 2737
telemt_me_idle_close_by_peer_total 2737
telemt_me_route_drop_no_conn_total 82709
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239354
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 592
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2675
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2584
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 239364
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 3762395896 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 96182995544 (89.58 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 97
```