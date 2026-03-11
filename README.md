# Server Metrics 2026-03-11 04:24:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50256.6 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970589
telemt_connections_bad_total 10073
telemt_handshake_timeouts_total 28246
telemt_upstream_connect_attempt_total 10816
telemt_upstream_connect_success_total 10807
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 532
telemt_me_reconnect_attempts_total 19928
telemt_me_reconnect_success_total 8254
telemt_me_reader_eof_total 8997
telemt_me_idle_close_by_peer_total 8997
telemt_me_route_drop_no_conn_total 366821
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 878821
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4007
telemt_desync_full_logged_total 1122
telemt_desync_suppressed_total 2885
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1368
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8694
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8248
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 878543
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 11520438072 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 259394655844 (241.58 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50313.4 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387098
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 18864
telemt_upstream_connect_attempt_total 19061
telemt_upstream_connect_success_total 16164
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 19061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1777
telemt_me_reconnect_attempts_total 11514
telemt_me_reconnect_success_total 10696
telemt_me_reader_eof_total 11289
telemt_me_idle_close_by_peer_total 11287
telemt_me_route_drop_no_conn_total 185144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332170
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1845
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10821
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10675
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 334441
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 3202007862 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 78640616408 (73.24 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50313.1 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650909
telemt_connections_bad_total 5547
telemt_handshake_timeouts_total 36019
telemt_upstream_connect_attempt_total 13580
telemt_upstream_connect_success_total 13405
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 558
telemt_me_reconnect_attempts_total 20880
telemt_me_reconnect_success_total 9810
telemt_me_reader_eof_total 10624
telemt_me_idle_close_by_peer_total 10624
telemt_me_route_drop_no_conn_total 219840
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579812
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10285
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9799
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 580700
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 7272072449 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 176241978573 (164.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50313.8 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495704
telemt_connections_bad_total 47387
telemt_handshake_timeouts_total 51997
telemt_upstream_connect_attempt_total 14568
telemt_upstream_connect_success_total 14568
telemt_upstream_connect_attempts_per_request{bucket="1"} 14568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 13092
telemt_me_reconnect_success_total 12052
telemt_me_reader_eof_total 12798
telemt_me_idle_close_by_peer_total 12798
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 147579
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382246
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 819
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 12193
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12032
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 381916
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 4606284536 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 103788264056 (96.66 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50313.3 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520802
telemt_connections_bad_total 5825
telemt_handshake_timeouts_total 3264
telemt_upstream_connect_attempt_total 14616
telemt_upstream_connect_success_total 14555
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 552
telemt_me_reconnect_attempts_total 15776
telemt_me_reconnect_success_total 11995
telemt_me_reader_eof_total 12655
telemt_me_idle_close_by_peer_total 12655
telemt_me_route_drop_no_conn_total 168438
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474179
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2391
telemt_desync_full_logged_total 934
telemt_desync_suppressed_total 1457
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1013
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 12267
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11995
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 473800
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 8766900004 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 167661229980 (156.15 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 62
```