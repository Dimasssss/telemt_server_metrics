# Server Metrics 2026-03-10 19:41:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 18836.7 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584822
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 4599
telemt_upstream_connect_attempt_total 3717
telemt_upstream_connect_success_total 3708
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 13173
telemt_me_reconnect_success_total 2712
telemt_me_reader_eof_total 3057
telemt_me_idle_close_by_peer_total 3057
telemt_me_route_drop_no_conn_total 243550
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552285
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2974
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 2178
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 1032
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3053
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2706
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 552172
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 8101463524 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 159541927124 (148.58 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 18893.5 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252291
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16570
telemt_upstream_connect_attempt_total 9122
telemt_upstream_connect_success_total 6377
telemt_upstream_connect_fail_total 2745
telemt_upstream_connect_attempts_per_request{bucket="1"} 9122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1883
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2745
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 4205
telemt_me_reconnect_success_total 3418
telemt_me_reader_eof_total 3567
telemt_me_idle_close_by_peer_total 3565
telemt_me_route_drop_no_conn_total 139290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215560
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1065
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3481
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3397
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 216859
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 2292630430 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 53280875562 (49.62 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 18893.4 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419032
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 32227
telemt_upstream_connect_attempt_total 5780
telemt_upstream_connect_success_total 5693
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 5780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 7114
telemt_me_reconnect_success_total 3660
telemt_me_reader_eof_total 3884
telemt_me_idle_close_by_peer_total 3884
telemt_me_route_drop_no_conn_total 143502
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360192
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1143
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 826
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 390
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3836
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3649
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 361142
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 5219945345 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 113865067197 (106.05 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 18894.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279038
telemt_connections_bad_total 18735
telemt_handshake_timeouts_total 24547
telemt_upstream_connect_attempt_total 5092
telemt_upstream_connect_success_total 5092
telemt_upstream_connect_attempts_per_request{bucket="1"} 5092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 5134
telemt_me_reconnect_success_total 4120
telemt_me_reader_eof_total 4307
telemt_me_idle_close_by_peer_total 4307
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 91289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224446
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 4191
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4107
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 224191
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 3540482536 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 65987034264 (61.46 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 18893.6 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293252
telemt_connections_bad_total 868
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 5782
telemt_upstream_connect_success_total 5760
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 5782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 4800
telemt_me_reconnect_success_total 4762
telemt_me_reader_eof_total 4898
telemt_me_idle_close_by_peer_total 4898
telemt_me_route_drop_no_conn_total 108509
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276933
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1548
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 978
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4835
telemt_me_writer_restored_same_endpoint_total 4762
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 276855
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 5501419152 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 89918788840 (83.74 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 82
```