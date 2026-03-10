# Server Metrics 2026-03-10 21:53:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26784.4 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712753
telemt_connections_bad_total 8155
telemt_handshake_timeouts_total 8216
telemt_upstream_connect_attempt_total 5774
telemt_upstream_connect_success_total 5765
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 16011
telemt_me_reconnect_success_total 4352
telemt_me_reader_eof_total 4811
telemt_me_idle_close_by_peer_total 4811
telemt_me_route_drop_no_conn_total 297280
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 673926
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3368
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 2421
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 1268
telemt_desync_frames_bucket_total{bucket="gt_10"} 1138
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4751
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4346
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 673731
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 9872399500 (9.19 GB)
telemt_user_octets_to_client{user="hello"} 203907179416 (189.90 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26841.1 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311451
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 17463
telemt_upstream_connect_attempt_total 12211
telemt_upstream_connect_success_total 9349
telemt_upstream_connect_fail_total 2862
telemt_upstream_connect_attempts_per_request{bucket="1"} 12211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2862
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 5829
telemt_me_reconnect_success_total 5024
telemt_me_reader_eof_total 5268
telemt_me_idle_close_by_peer_total 5266
telemt_me_route_drop_no_conn_total 164145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261820
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1110
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5108
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5003
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 264093
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2626757214 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 61870906100 (57.62 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 26840.9 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510992
telemt_connections_bad_total 2944
telemt_handshake_timeouts_total 33589
telemt_upstream_connect_attempt_total 7506
telemt_upstream_connect_success_total 7390
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 15990
telemt_me_reconnect_success_total 4941
telemt_me_reader_eof_total 5443
telemt_me_idle_close_by_peer_total 5443
telemt_me_route_drop_no_conn_total 177564
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1431
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 1032
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 5364
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4930
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 447208
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 6537217085 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 144926588529 (134.97 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 26841.4 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354589
telemt_connections_bad_total 25980
telemt_handshake_timeouts_total 31071
telemt_upstream_connect_attempt_total 7379
telemt_upstream_connect_success_total 7379
telemt_upstream_connect_attempts_per_request{bucket="1"} 7379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 7024
telemt_me_reconnect_success_total 6002
telemt_me_reader_eof_total 6281
telemt_me_idle_close_by_peer_total 6281
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 115107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284856
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6100
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 5988
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 284534
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 3997781044 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 85323733776 (79.46 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 26841.2 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373200
telemt_connections_bad_total 1190
telemt_handshake_timeouts_total 2385
telemt_upstream_connect_attempt_total 8232
telemt_upstream_connect_success_total 8199
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 8232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 10547
telemt_me_reconnect_success_total 6793
telemt_me_reader_eof_total 7113
telemt_me_idle_close_by_peer_total 7113
telemt_me_route_drop_no_conn_total 132146
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349517
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2094
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7009
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6793
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 349373
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 6365049584 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 128405110068 (119.59 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 38
```