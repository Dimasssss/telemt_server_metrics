# Server Metrics 2026-03-14 16:49:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 12702.3 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508356
telemt_connections_bad_total 25701
telemt_handshake_timeouts_total 6965
telemt_upstream_connect_attempt_total 2665
telemt_upstream_connect_success_total 2652
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 2736
telemt_me_reconnect_success_total 1940
telemt_me_reader_eof_total 2020
telemt_me_idle_close_by_peer_total 2020
telemt_me_route_drop_no_conn_total 196662
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453052
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1124
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 645
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1995
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 1931
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 452973
telemt_user_connections_current{user="hello"} 1790
telemt_user_octets_from_client{user="hello"} 8205238544 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 139121037368 (129.57 GB)
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 12707.2 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206831
telemt_connections_bad_total 20880
telemt_handshake_timeouts_total 6317
telemt_upstream_connect_attempt_total 2752
telemt_upstream_connect_success_total 2720
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2787
telemt_me_reconnect_success_total 2006
telemt_me_reader_eof_total 2084
telemt_me_idle_close_by_peer_total 2084
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 63614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166207
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2081
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 1991
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 166157
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 2422098216 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 66747305172 (62.16 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 12570.0 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418778
telemt_connections_bad_total 1482
telemt_handshake_timeouts_total 88872
telemt_upstream_connect_attempt_total 2612
telemt_upstream_connect_success_total 2604
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 5844
telemt_me_reconnect_success_total 1946
telemt_me_reader_eof_total 2092
telemt_me_idle_close_by_peer_total 2092
telemt_me_route_drop_no_conn_total 106778
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287421
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 710
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2075
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1913
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 287305
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 4191917576 (3.90 GB)
telemt_user_octets_to_client{user="hello"} 105598623188 (98.35 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 12424.5 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223855
telemt_connections_bad_total 47998
telemt_handshake_timeouts_total 35650
telemt_upstream_connect_attempt_total 3148
telemt_upstream_connect_success_total 3147
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3406
telemt_me_reconnect_success_total 2494
telemt_me_reader_eof_total 2578
telemt_me_idle_close_by_peer_total 2578
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 49884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137211
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 283
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2546
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2487
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 137174
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 2262292764 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 45890389048 (42.74 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 12719.9 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199262
telemt_connections_bad_total 718
telemt_handshake_timeouts_total 2709
telemt_upstream_connect_attempt_total 2890
telemt_upstream_connect_success_total 2831
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 2890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 2798
telemt_me_reconnect_success_total 2133
telemt_me_reader_eof_total 2227
telemt_me_idle_close_by_peer_total 2227
telemt_me_route_drop_no_conn_total 65594
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183113
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2198
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 183129
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 2878797972 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 72607755692 (67.62 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 106
```