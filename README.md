# Server Metrics 2026-03-10 22:49:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30144.1 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744833
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8388
telemt_upstream_connect_attempt_total 6494
telemt_upstream_connect_success_total 6485
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 363
telemt_me_reconnect_attempts_total 16558
telemt_me_reconnect_success_total 4897
telemt_me_reader_eof_total 5398
telemt_me_idle_close_by_peer_total 5398
telemt_me_route_drop_no_conn_total 310061
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704562
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3472
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5301
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4891
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 704365
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 10047769300 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 212530219828 (197.93 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30201.0 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323046
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17584
telemt_upstream_connect_attempt_total 13188
telemt_upstream_connect_success_total 10319
telemt_upstream_connect_fail_total 2869
telemt_upstream_connect_attempts_per_request{bucket="1"} 13188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2869
telemt_me_keepalive_timeout_total 1381
telemt_me_reconnect_attempts_total 6624
telemt_me_reconnect_success_total 5817
telemt_me_reader_eof_total 6110
telemt_me_idle_close_by_peer_total 6108
telemt_me_route_drop_no_conn_total 167918
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272996
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 561
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5906
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5796
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 275265
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2677849022 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 64535300320 (60.10 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30200.7 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533894
telemt_connections_bad_total 3456
telemt_handshake_timeouts_total 33862
telemt_upstream_connect_attempt_total 8283
telemt_upstream_connect_success_total 8161
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 16589
telemt_me_reconnect_success_total 5534
telemt_me_reader_eof_total 6082
telemt_me_idle_close_by_peer_total 6082
telemt_me_route_drop_no_conn_total 184884
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468206
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1513
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5964
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5523
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 469138
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 6666760409 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 148913203993 (138.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30201.1 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377638
telemt_connections_bad_total 29026
telemt_handshake_timeouts_total 34036
telemt_upstream_connect_attempt_total 8380
telemt_upstream_connect_success_total 8380
telemt_upstream_connect_attempts_per_request{bucket="1"} 8380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 7851
telemt_me_reconnect_success_total 6827
telemt_me_reader_eof_total 7181
telemt_me_idle_close_by_peer_total 7181
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 120292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301672
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 690
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6931
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6813
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 301347
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 4063284356 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 87592175004 (81.58 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30200.7 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398856
telemt_connections_bad_total 3184
telemt_handshake_timeouts_total 2620
telemt_upstream_connect_attempt_total 9340
telemt_upstream_connect_success_total 9302
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 9340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 11472
telemt_me_reconnect_success_total 7712
telemt_me_reader_eof_total 8085
telemt_me_idle_close_by_peer_total 8085
telemt_me_route_drop_no_conn_total 138500
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2157
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 797
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7938
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7712
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 370433
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 6444318372 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 138770900296 (129.24 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 35
```