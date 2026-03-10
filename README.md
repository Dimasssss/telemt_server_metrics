# Server Metrics 2026-03-10 22:59:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 30754.1 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749346
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8410
telemt_upstream_connect_attempt_total 6629
telemt_upstream_connect_success_total 6620
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 16649
telemt_me_reconnect_success_total 4988
telemt_me_reader_eof_total 5494
telemt_me_idle_close_by_peer_total 5494
telemt_me_route_drop_no_conn_total 311277
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 708971
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3483
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 2512
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 1175
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5392
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4982
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 708767
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 10074615616 (9.38 GB)
telemt_user_octets_to_client{user="hello"} 213766369760 (199.09 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30810.8 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325081
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17584
telemt_upstream_connect_attempt_total 13362
telemt_upstream_connect_success_total 10492
telemt_upstream_connect_fail_total 2870
telemt_upstream_connect_attempts_per_request{bucket="1"} 13362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2870
telemt_me_keepalive_timeout_total 1384
telemt_me_reconnect_attempts_total 6754
telemt_me_reconnect_success_total 5946
telemt_me_reader_eof_total 6255
telemt_me_idle_close_by_peer_total 6253
telemt_me_route_drop_no_conn_total 168629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274973
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 461
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 590
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6036
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5925
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 277242
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2710250418 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 65268400932 (60.79 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 30810.6 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537045
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 33912
telemt_upstream_connect_attempt_total 8434
telemt_upstream_connect_success_total 8312
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 16697
telemt_me_reconnect_success_total 5641
telemt_me_reader_eof_total 6201
telemt_me_idle_close_by_peer_total 6201
telemt_me_route_drop_no_conn_total 185781
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471300
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1515
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6071
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5630
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 472232
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 6690356193 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 150194905349 (139.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 30810.9 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381475
telemt_connections_bad_total 29577
telemt_handshake_timeouts_total 34522
telemt_upstream_connect_attempt_total 8593
telemt_upstream_connect_success_total 8593
telemt_upstream_connect_attempts_per_request{bucket="1"} 8593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 8021
telemt_me_reconnect_success_total 6996
telemt_me_reader_eof_total 7368
telemt_me_idle_close_by_peer_total 7368
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 121136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304460
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7100
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6982
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 304135
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 4073306916 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 87889913052 (81.85 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30810.6 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402919
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 2636
telemt_upstream_connect_attempt_total 9520
telemt_upstream_connect_success_total 9481
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 202
telemt_me_reconnect_attempts_total 11608
telemt_me_reconnect_success_total 7848
telemt_me_reader_eof_total 8237
telemt_me_idle_close_by_peer_total 8237
telemt_me_route_drop_no_conn_total 139358
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374203
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2166
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 1329
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8074
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7848
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 374015
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 6455806084 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 139816694332 (130.21 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 36
```