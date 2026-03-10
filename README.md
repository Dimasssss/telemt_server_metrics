# Server Metrics 2026-03-10 17:18:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10260.5 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345992
telemt_connections_bad_total 1485
telemt_handshake_timeouts_total 1637
telemt_upstream_connect_attempt_total 1907
telemt_upstream_connect_success_total 1899
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 9463
telemt_me_reconnect_success_total 1324
telemt_me_reader_eof_total 1542
telemt_me_idle_close_by_peer_total 1542
telemt_me_route_drop_no_conn_total 150634
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332502
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1541
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1573
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1318
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 332434
telemt_user_connections_current{user="hello"} 1246
telemt_user_octets_from_client{user="hello"} 4346198400 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 97715973148 (91.01 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 10317.3 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138623
telemt_connections_bad_total 1684
telemt_handshake_timeouts_total 9418
telemt_upstream_connect_attempt_total 2385
telemt_upstream_connect_success_total 2374
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1824
telemt_me_reconnect_success_total 1813
telemt_me_reader_eof_total 1876
telemt_me_idle_close_by_peer_total 1876
telemt_me_route_drop_no_conn_total 39340
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120295
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 574
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1822
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 120276
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 1559706324 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 31926623416 (29.73 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 10317.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266119
telemt_connections_bad_total 794
telemt_handshake_timeouts_total 30357
telemt_upstream_connect_attempt_total 3546
telemt_upstream_connect_success_total 3487
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 1915
telemt_me_reconnect_success_total 1874
telemt_me_reader_eof_total 1936
telemt_me_idle_close_by_peer_total 1936
telemt_me_route_drop_no_conn_total 84312
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212628
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 634
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1904
telemt_me_writer_restored_same_endpoint_total 1863
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 213604
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 3064494845 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 62380494053 (58.10 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 10317.6 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165882
telemt_connections_bad_total 10164
telemt_handshake_timeouts_total 16107
telemt_upstream_connect_attempt_total 2582
telemt_upstream_connect_success_total 2582
telemt_upstream_connect_attempts_per_request{bucket="1"} 2582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1191
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 2031
telemt_me_reconnect_success_total 2018
telemt_me_reader_eof_total 2097
telemt_me_idle_close_by_peer_total 2097
telemt_me_route_drop_no_conn_total 54056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 426
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2033
telemt_me_writer_restored_same_endpoint_total 2007
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 132181
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 2240633296 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 36150917560 (33.67 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10317.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179312
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 1411
telemt_upstream_connect_attempt_total 3214
telemt_upstream_connect_success_total 3204
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 2641
telemt_me_reconnect_success_total 2624
telemt_me_reader_eof_total 2682
telemt_me_idle_close_by_peer_total 2682
telemt_me_route_drop_no_conn_total 66514
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168013
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 864
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2645
telemt_me_writer_restored_same_endpoint_total 2624
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 167950
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 3957996128 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 50764224980 (47.28 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 82
```