# Server Metrics 2026-03-10 23:40:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33190.4 (9h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765593
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 8524
telemt_upstream_connect_attempt_total 7173
telemt_upstream_connect_success_total 7164
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 17106
telemt_me_reconnect_success_total 5444
telemt_me_reader_eof_total 5983
telemt_me_idle_close_by_peer_total 5983
telemt_me_route_drop_no_conn_total 316810
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724824
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3515
telemt_desync_full_logged_total 981
telemt_desync_suppressed_total 2534
telemt_desync_frames_bucket_total{bucket="1_2"} 1013
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 1189
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 5854
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5438
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 724614
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 10130622772 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 216968834056 (202.07 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33247.1 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331855
telemt_connections_bad_total 2381
telemt_handshake_timeouts_total 17608
telemt_upstream_connect_attempt_total 14003
telemt_upstream_connect_success_total 11129
telemt_upstream_connect_fail_total 2874
telemt_upstream_connect_attempts_per_request{bucket="1"} 14003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2874
telemt_me_keepalive_timeout_total 1677
telemt_me_reconnect_attempts_total 7305
telemt_me_reconnect_success_total 6494
telemt_me_reader_eof_total 6835
telemt_me_idle_close_by_peer_total 6833
telemt_me_route_drop_no_conn_total 170066
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281548
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1709
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6588
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6473
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 283817
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2769448162 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 69021018940 (64.28 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33246.8 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550057
telemt_connections_bad_total 3676
telemt_handshake_timeouts_total 33978
telemt_upstream_connect_attempt_total 8985
telemt_upstream_connect_success_total 8860
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 8985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 475
telemt_me_reconnect_attempts_total 17158
telemt_me_reconnect_success_total 6101
telemt_me_reader_eof_total 6687
telemt_me_idle_close_by_peer_total 6687
telemt_me_route_drop_no_conn_total 190315
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483945
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6539
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6090
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 484870
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 6747585617 (6.28 GB)
telemt_user_octets_to_client{user="hello"} 152058621913 (141.62 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33247.4 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395001
telemt_connections_bad_total 31797
telemt_handshake_timeouts_total 36372
telemt_upstream_connect_attempt_total 9277
telemt_upstream_connect_success_total 9277
telemt_upstream_connect_attempts_per_request{bucket="1"} 9277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 8618
telemt_me_reconnect_success_total 7590
telemt_me_reader_eof_total 7997
telemt_me_idle_close_by_peer_total 7997
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 123960
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313881
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7703
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7575
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 313556
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 4096332616 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 88779422676 (82.68 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33246.9 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418114
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2686
telemt_upstream_connect_attempt_total 10130
telemt_upstream_connect_success_total 10091
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 10130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 462
telemt_me_reconnect_attempts_total 12132
telemt_me_reconnect_success_total 8370
telemt_me_reader_eof_total 8782
telemt_me_idle_close_by_peer_total 8782
telemt_me_route_drop_no_conn_total 142372
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387566
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2225
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 8599
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8370
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 387347
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 6518878996 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 142521488584 (132.73 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```