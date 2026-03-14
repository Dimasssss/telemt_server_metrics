# Server Metrics 2026-03-14 17:04:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 13621.9 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548890
telemt_connections_bad_total 29106
telemt_handshake_timeouts_total 7454
telemt_upstream_connect_attempt_total 2813
telemt_upstream_connect_success_total 2800
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 2838
telemt_me_reconnect_success_total 2040
telemt_me_reader_eof_total 2128
telemt_me_idle_close_by_peer_total 2128
telemt_me_route_drop_no_conn_total 211122
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487760
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1707
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2096
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 487682
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 8717448128 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 150863368660 (140.50 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 13627.4 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221816
telemt_connections_bad_total 21719
telemt_handshake_timeouts_total 6681
telemt_upstream_connect_attempt_total 2915
telemt_upstream_connect_success_total 2882
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 2905
telemt_me_reconnect_success_total 2123
telemt_me_reader_eof_total 2208
telemt_me_idle_close_by_peer_total 2208
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 68549
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 631
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2199
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2108
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 179322
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 2663597012 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 71217324072 (66.33 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 13490.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455879
telemt_connections_bad_total 1639
telemt_handshake_timeouts_total 95374
telemt_upstream_connect_attempt_total 2767
telemt_upstream_connect_success_total 2759
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 5956
telemt_me_reconnect_success_total 2057
telemt_me_reader_eof_total 2216
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 114370
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309254
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 836
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2190
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2024
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 309156
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 4411562164 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 113203830108 (105.43 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 13344.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240136
telemt_connections_bad_total 51076
telemt_handshake_timeouts_total 36696
telemt_upstream_connect_attempt_total 3346
telemt_upstream_connect_success_total 3345
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 3561
telemt_me_reconnect_success_total 2648
telemt_me_reader_eof_total 2746
telemt_me_idle_close_by_peer_total 2746
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 54072
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149095
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 306
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2702
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2641
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 149053
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 2376701736 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 48844600424 (45.49 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 13640.2 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213318
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 2806
telemt_upstream_connect_attempt_total 3070
telemt_upstream_connect_success_total 3007
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 2930
telemt_me_reconnect_success_total 2265
telemt_me_reader_eof_total 2380
telemt_me_idle_close_by_peer_total 2380
telemt_me_route_drop_no_conn_total 70393
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196298
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2331
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2247
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 196314
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 3149477188 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 76725805108 (71.46 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 131
```