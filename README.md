# Server Metrics 2026-03-11 06:16:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56965.3 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121682
telemt_connections_bad_total 13234
telemt_handshake_timeouts_total 38218
telemt_upstream_connect_attempt_total 12073
telemt_upstream_connect_success_total 12064
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 689
telemt_me_reconnect_attempts_total 20839
telemt_me_reconnect_success_total 9157
telemt_me_reader_eof_total 9961
telemt_me_idle_close_by_peer_total 9961
telemt_me_route_drop_no_conn_total 413086
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4699
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 3379
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 1764
telemt_desync_frames_bucket_total{bucket="gt_10"} 1639
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9607
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9151
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1007012
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 13446298180 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 295876470656 (275.56 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57022.0 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430910
telemt_connections_bad_total 4282
telemt_handshake_timeouts_total 20960
telemt_upstream_connect_attempt_total 20740
telemt_upstream_connect_success_total 17832
telemt_upstream_connect_fail_total 2908
telemt_upstream_connect_attempts_per_request{bucket="1"} 20740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2908
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 12835
telemt_me_reconnect_success_total 12011
telemt_me_reader_eof_total 12697
telemt_me_idle_close_by_peer_total 12695
telemt_me_route_drop_no_conn_total 197874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1914
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12150
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11989
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 371727
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 3744399102 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 91334055772 (85.06 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57021.9 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736140
telemt_connections_bad_total 6251
telemt_handshake_timeouts_total 40592
telemt_upstream_connect_attempt_total 15395
telemt_upstream_connect_success_total 15194
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 22324
telemt_me_reconnect_success_total 11251
telemt_me_reader_eof_total 12136
telemt_me_idle_close_by_peer_total 12136
telemt_me_route_drop_no_conn_total 248651
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657704
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1328
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 11743
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11240
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 658558
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 7843700965 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 194737344633 (181.36 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57022.2 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559827
telemt_connections_bad_total 53501
telemt_handshake_timeouts_total 57875
telemt_upstream_connect_attempt_total 16284
telemt_upstream_connect_success_total 16284
telemt_upstream_connect_attempts_per_request{bucket="1"} 16284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 642
telemt_me_reconnect_attempts_total 14460
telemt_me_reconnect_success_total 13415
telemt_me_reader_eof_total 14244
telemt_me_idle_close_by_peer_total 14244
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 167266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433451
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13570
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13393
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 433017
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 5245793864 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 119154564120 (110.97 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57021.9 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586410
telemt_connections_bad_total 5960
telemt_handshake_timeouts_total 4026
telemt_upstream_connect_attempt_total 16280
telemt_upstream_connect_success_total 16212
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 16280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 673
telemt_me_reconnect_attempts_total 17010
telemt_me_reconnect_success_total 13226
telemt_me_reader_eof_total 13973
telemt_me_idle_close_by_peer_total 13973
telemt_me_route_drop_no_conn_total 191783
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533860
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2548
telemt_desync_full_logged_total 986
telemt_desync_suppressed_total 1562
telemt_desync_frames_bucket_total{bucket="1_2"} 916
telemt_desync_frames_bucket_total{bucket="3_10"} 1088
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 13514
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13226
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 533597
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 9420077479 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 186836493038 (174.01 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 72
```