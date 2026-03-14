# Server Metrics 2026-03-14 16:28:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 11474.8 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455248
telemt_connections_bad_total 20417
telemt_handshake_timeouts_total 5685
telemt_upstream_connect_attempt_total 2462
telemt_upstream_connect_success_total 2450
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 2617
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1898
telemt_me_idle_close_by_peer_total 1898
telemt_me_route_drop_no_conn_total 177655
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408947
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1405
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1876
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1812
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 408942
telemt_user_connections_current{user="hello"} 1858
telemt_user_octets_from_client{user="hello"} 7433665752 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 124117580868 (115.59 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 11480.2 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186632
telemt_connections_bad_total 18490
telemt_handshake_timeouts_total 6005
telemt_upstream_connect_attempt_total 2502
telemt_upstream_connect_success_total 2473
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 2627
telemt_me_reconnect_success_total 1847
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 57442
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149258
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1917
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1832
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 149199
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 2261457292 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 61040237904 (56.85 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 11343.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377538
telemt_connections_bad_total 1448
telemt_handshake_timeouts_total 83599
telemt_upstream_connect_attempt_total 2358
telemt_upstream_connect_success_total 2350
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 5635
telemt_me_reconnect_success_total 1738
telemt_me_reader_eof_total 1881
telemt_me_idle_close_by_peer_total 1881
telemt_me_route_drop_no_conn_total 96703
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258436
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 553
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1863
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1705
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 258315
telemt_user_connections_current{user="hello"} 1000
telemt_user_octets_from_client{user="hello"} 3858055444 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 96870279748 (90.22 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 11197.6 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202274
telemt_connections_bad_total 41825
telemt_handshake_timeouts_total 33841
telemt_upstream_connect_attempt_total 2867
telemt_upstream_connect_success_total 2866
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2273
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2311
telemt_me_idle_close_by_peer_total 2311
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 45398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 245
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2277
telemt_me_writer_restored_same_endpoint_total 2251
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 123946
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 2065799756 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 40710051680 (37.91 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 11492.8 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179570
telemt_connections_bad_total 361
telemt_handshake_timeouts_total 2488
telemt_upstream_connect_attempt_total 2567
telemt_upstream_connect_success_total 2511
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 2566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2567
telemt_me_reconnect_success_total 1901
telemt_me_reader_eof_total 1994
telemt_me_idle_close_by_peer_total 1994
telemt_me_route_drop_no_conn_total 60095
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165495
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 479
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1965
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 165510
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 2537641996 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 65709622848 (61.20 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 90
```