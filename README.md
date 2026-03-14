# Server Metrics 2026-03-14 15:52:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 9288.3 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362657
telemt_connections_bad_total 13061
telemt_handshake_timeouts_total 4440
telemt_upstream_connect_attempt_total 1989
telemt_upstream_connect_success_total 1981
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 2236
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1504
telemt_me_idle_close_by_peer_total 1504
telemt_me_route_drop_no_conn_total 143243
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330624
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1004
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 701
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1494
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 330623
telemt_user_connections_current{user="hello"} 1795
telemt_user_octets_from_client{user="hello"} 5467991196 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 100055213836 (93.18 GB)
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 9293.7 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149397
telemt_connections_bad_total 13988
telemt_handshake_timeouts_total 5059
telemt_upstream_connect_attempt_total 2028
telemt_upstream_connect_success_total 2003
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 2028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 2244
telemt_me_reconnect_success_total 1469
telemt_me_reader_eof_total 1524
telemt_me_idle_close_by_peer_total 1524
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 46591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120247
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 511
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1533
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1455
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 120188
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 1596576588 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 50514892092 (47.05 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 9156.7 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306341
telemt_connections_bad_total 1041
telemt_handshake_timeouts_total 75693
telemt_upstream_connect_attempt_total 2005
telemt_upstream_connect_success_total 1997
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 5369
telemt_me_reconnect_success_total 1473
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1601
telemt_me_route_drop_no_conn_total 77344
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209614
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 366
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1595
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1440
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 209516
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 2907347636 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 79365831376 (73.92 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 9011.1 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155795
telemt_connections_bad_total 33022
telemt_handshake_timeouts_total 24140
telemt_upstream_connect_attempt_total 2259
telemt_upstream_connect_success_total 2258
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1798
telemt_me_reconnect_success_total 1786
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1825
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 35123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96352
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1794
telemt_me_writer_restored_same_endpoint_total 1784
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 96325
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 1725350400 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 31680763956 (29.51 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 9306.5 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143714
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 2006
telemt_upstream_connect_attempt_total 2208
telemt_upstream_connect_success_total 2158
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 2208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 1636
telemt_me_reader_eof_total 1715
telemt_me_idle_close_by_peer_total 1715
telemt_me_route_drop_no_conn_total 48647
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133052
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1696
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1618
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 133057
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 1972616804 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 49151324176 (45.78 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 84
```