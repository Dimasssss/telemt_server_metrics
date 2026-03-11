# Server Metrics 2026-03-11 02:12:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42332.7 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 836838
telemt_connections_bad_total 9877
telemt_handshake_timeouts_total 12687
telemt_upstream_connect_attempt_total 9177
telemt_upstream_connect_success_total 9168
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 18677
telemt_me_reconnect_success_total 7009
telemt_me_reader_eof_total 7659
telemt_me_idle_close_by_peer_total 7659
telemt_me_route_drop_no_conn_total 338065
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789940
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3652
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 2625
telemt_desync_frames_bucket_total{bucket="1_2"} 1067
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7432
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7003
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 789676
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 10745548632 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 237920924908 (221.58 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42389.3 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357395
telemt_connections_bad_total 2412
telemt_handshake_timeouts_total 18049
telemt_upstream_connect_attempt_total 16764
telemt_upstream_connect_success_total 13874
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 16764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1736
telemt_me_reconnect_attempts_total 9580
telemt_me_reconnect_success_total 8763
telemt_me_reader_eof_total 9237
telemt_me_idle_close_by_peer_total 9235
telemt_me_route_drop_no_conn_total 176281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8876
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8742
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 308314
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2897763358 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 72479308408 (67.50 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42389.2 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595453
telemt_connections_bad_total 4904
telemt_handshake_timeouts_total 34397
telemt_upstream_connect_attempt_total 11596
telemt_upstream_connect_success_total 11440
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 19265
telemt_me_reconnect_success_total 8199
telemt_me_reader_eof_total 8911
telemt_me_idle_close_by_peer_total 8911
telemt_me_route_drop_no_conn_total 202496
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527428
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8657
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8188
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 528337
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 6972962225 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 160448603333 (149.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42389.5 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444120
telemt_connections_bad_total 40159
telemt_handshake_timeouts_total 42785
telemt_upstream_connect_attempt_total 12307
telemt_upstream_connect_success_total 12307
telemt_upstream_connect_attempts_per_request{bucket="1"} 12307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 430
telemt_me_reconnect_attempts_total 11175
telemt_me_reconnect_success_total 10139
telemt_me_reader_eof_total 10735
telemt_me_idle_close_by_peer_total 10735
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 133612
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347622
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 745
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 446
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10263
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10120
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 347291
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 4303531792 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 93471799008 (87.05 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42389.2 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468935
telemt_connections_bad_total 5790
telemt_handshake_timeouts_total 2992
telemt_upstream_connect_attempt_total 12529
telemt_upstream_connect_success_total 12477
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5923
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 14051
telemt_me_reconnect_success_total 10278
telemt_me_reader_eof_total 10830
telemt_me_idle_close_by_peer_total 10830
telemt_me_route_drop_no_conn_total 152553
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428255
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2301
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 1407
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 10531
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10278
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 427934
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 8458422244 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 151180710880 (140.80 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```