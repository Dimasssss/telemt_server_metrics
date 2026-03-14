# Server Metrics 2026-03-14 17:09:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 13928.4 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562460
telemt_connections_bad_total 30225
telemt_handshake_timeouts_total 7682
telemt_upstream_connect_attempt_total 2862
telemt_upstream_connect_success_total 2849
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2887
telemt_me_reconnect_success_total 2088
telemt_me_reader_eof_total 2184
telemt_me_idle_close_by_peer_total 2184
telemt_me_route_drop_no_conn_total 215764
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498924
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1742
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1236
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2146
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2079
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 498859
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 8999331940 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 154474019456 (143.87 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 13933.7 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226564
telemt_connections_bad_total 21987
telemt_handshake_timeouts_total 6873
telemt_upstream_connect_attempt_total 2968
telemt_upstream_connect_success_total 2934
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2958
telemt_me_reconnect_success_total 2174
telemt_me_reader_eof_total 2266
telemt_me_idle_close_by_peer_total 2266
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 70220
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183328
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2251
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2159
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 183270
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 2711653120 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 72596612660 (67.61 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 13796.7 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466780
telemt_connections_bad_total 1647
telemt_handshake_timeouts_total 96189
telemt_upstream_connect_attempt_total 2866
telemt_upstream_connect_success_total 2857
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 6011
telemt_me_reconnect_success_total 2111
telemt_me_reader_eof_total 2276
telemt_me_idle_close_by_peer_total 2276
telemt_me_route_drop_no_conn_total 116642
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316211
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 880
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2246
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 316118
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 4593761868 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 115532714428 (107.60 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 13651.0 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245439
telemt_connections_bad_total 52112
telemt_handshake_timeouts_total 36914
telemt_upstream_connect_attempt_total 3429
telemt_upstream_connect_success_total 3428
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 3601
telemt_me_reconnect_success_total 2688
telemt_me_reader_eof_total 2791
telemt_me_idle_close_by_peer_total 2791
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 55511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153067
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 312
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2743
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2681
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 153025
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 2400366420 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 50003433624 (46.57 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 13946.7 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218631
telemt_connections_bad_total 853
telemt_handshake_timeouts_total 2856
telemt_upstream_connect_attempt_total 3113
telemt_upstream_connect_success_total 3050
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 2973
telemt_me_reconnect_success_total 2308
telemt_me_reader_eof_total 2423
telemt_me_idle_close_by_peer_total 2423
telemt_me_route_drop_no_conn_total 72020
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201232
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 536
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2374
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2290
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 201248
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 3218186248 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 78458898276 (73.07 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 107
```