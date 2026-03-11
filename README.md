# Server Metrics 2026-03-11 20:53:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109610.3 (30h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2777476
telemt_connections_bad_total 60223
telemt_handshake_timeouts_total 62319
telemt_upstream_connect_attempt_total 23339
telemt_upstream_connect_success_total 23327
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5435
telemt_me_reconnect_attempts_total 35677
telemt_me_reconnect_success_total 17783
telemt_me_reader_eof_total 19176
telemt_me_idle_close_by_peer_total 19176
telemt_me_route_drop_no_conn_total 1043241
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2522837
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12695
telemt_desync_full_logged_total 3529
telemt_desync_suppressed_total 9166
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4683
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18548
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17777
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 2521179
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 38241981660 (35.62 GB)
telemt_user_octets_to_client{user="hello"} 727403612756 (677.45 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109666.9 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016152
telemt_connections_bad_total 17047
telemt_handshake_timeouts_total 90431
telemt_upstream_connect_attempt_total 33446
telemt_upstream_connect_success_total 30471
telemt_upstream_connect_fail_total 2975
telemt_upstream_connect_attempts_per_request{bucket="1"} 33446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2975
telemt_me_keepalive_timeout_total 2907
telemt_me_reconnect_attempts_total 24143
telemt_me_reconnect_success_total 22016
telemt_me_reader_eof_total 23326
telemt_me_idle_close_by_peer_total 23323
telemt_me_route_drop_no_conn_total 384552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849104
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3374
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2276
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 22341
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21993
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 851543
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 10293995338 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 251620638164 (234.34 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109666.8 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1769764
telemt_connections_bad_total 11324
telemt_handshake_timeouts_total 136304
telemt_upstream_connect_attempt_total 27594
telemt_upstream_connect_success_total 27242
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 27594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 2048
telemt_me_reconnect_attempts_total 59754
telemt_me_reconnect_success_total 20625
telemt_me_reader_eof_total 22707
telemt_me_idle_close_by_peer_total 22707
telemt_me_route_drop_no_conn_total 643496
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1556301
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4204
telemt_desync_full_logged_total 1241
telemt_desync_suppressed_total 2963
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1598
telemt_desync_frames_bucket_total{bucket="gt_10"} 1622
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22130
telemt_me_refill_failed_total 1217
telemt_me_writer_restored_same_endpoint_total 20613
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 1555930
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 19912561209 (18.55 GB)
telemt_user_octets_to_client{user="hello"} 476876513857 (444.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109667.3 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265968
telemt_connections_bad_total 78253
telemt_handshake_timeouts_total 111595
telemt_upstream_connect_attempt_total 29462
telemt_upstream_connect_success_total 29462
telemt_upstream_connect_attempts_per_request{bucket="1"} 29462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1542
telemt_me_reconnect_attempts_total 28605
telemt_me_reconnect_success_total 23985
telemt_me_reader_eof_total 25472
telemt_me_idle_close_by_peer_total 25471
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 425685
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040271
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2206
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1376
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24386
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23952
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 1039396
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 12271849512 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 315085372524 (293.45 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14343.1 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203974
telemt_connections_bad_total 5155
telemt_handshake_timeouts_total 2359
telemt_upstream_connect_attempt_total 4075
telemt_upstream_connect_success_total 4074
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 3340
telemt_me_reconnect_success_total 3310
telemt_me_reader_eof_total 3428
telemt_me_idle_close_by_peer_total 3428
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 69087
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 460
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3349
telemt_me_writer_restored_same_endpoint_total 3285
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 180006
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 9622695240 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 63372834240 (59.02 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 57
```