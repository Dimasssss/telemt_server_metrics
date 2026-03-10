# Server Metrics 2026-03-10 21:58:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27089.5 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716557
telemt_connections_bad_total 8312
telemt_handshake_timeouts_total 8233
telemt_upstream_connect_attempt_total 5833
telemt_upstream_connect_success_total 5824
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 16043
telemt_me_reconnect_success_total 4384
telemt_me_reader_eof_total 4843
telemt_me_idle_close_by_peer_total 4843
telemt_me_route_drop_no_conn_total 298421
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677455
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3371
telemt_desync_full_logged_total 948
telemt_desync_suppressed_total 2423
telemt_desync_frames_bucket_total{bucket="1_2"} 964
telemt_desync_frames_bucket_total{bucket="3_10"} 1269
telemt_desync_frames_bucket_total{bucket="gt_10"} 1138
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4783
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4378
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 677260
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 9887291232 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 204813720320 (190.75 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 27146.2 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312432
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 17497
telemt_upstream_connect_attempt_total 12319
telemt_upstream_connect_success_total 9456
telemt_upstream_connect_fail_total 2863
telemt_upstream_connect_attempts_per_request{bucket="1"} 12319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2863
telemt_me_keepalive_timeout_total 1371
telemt_me_reconnect_attempts_total 5892
telemt_me_reconnect_success_total 5086
telemt_me_reader_eof_total 5334
telemt_me_idle_close_by_peer_total 5332
telemt_me_route_drop_no_conn_total 164550
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1546
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 1114
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5171
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5065
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 265018
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 2630051830 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62114449448 (57.85 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 27146.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513388
telemt_connections_bad_total 2964
telemt_handshake_timeouts_total 33598
telemt_upstream_connect_attempt_total 7599
telemt_upstream_connect_success_total 7483
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 7599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 16040
telemt_me_reconnect_success_total 4989
telemt_me_reader_eof_total 5499
telemt_me_idle_close_by_peer_total 5499
telemt_me_route_drop_no_conn_total 178276
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448622
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1440
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 1038
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5413
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 4978
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 449555
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 6546444445 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 145430873165 (135.44 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 27146.5 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356383
telemt_connections_bad_total 26256
telemt_handshake_timeouts_total 31196
telemt_upstream_connect_attempt_total 7547
telemt_upstream_connect_success_total 7547
telemt_upstream_connect_attempts_per_request{bucket="1"} 7547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 7148
telemt_me_reconnect_success_total 6126
telemt_me_reader_eof_total 6418
telemt_me_idle_close_by_peer_total 6418
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 115502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286145
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6224
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6112
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 285823
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 4007792668 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 85558143556 (79.68 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 27146.4 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375448
telemt_connections_bad_total 1190
telemt_handshake_timeouts_total 2406
telemt_upstream_connect_attempt_total 8346
telemt_upstream_connect_success_total 8312
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 10615
telemt_me_reconnect_success_total 6861
telemt_me_reader_eof_total 7183
telemt_me_idle_close_by_peer_total 7183
telemt_me_route_drop_no_conn_total 132653
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351517
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2097
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7079
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 6861
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 351369
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 6373663780 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 130644849240 (121.67 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 52
```