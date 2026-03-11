# Server Metrics 2026-03-11 07:42:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 62152.2 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256185
telemt_connections_bad_total 13655
telemt_handshake_timeouts_total 39367
telemt_upstream_connect_attempt_total 12925
telemt_upstream_connect_success_total 12916
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 21465
telemt_me_reconnect_success_total 9781
telemt_me_reader_eof_total 10624
telemt_me_idle_close_by_peer_total 10624
telemt_me_route_drop_no_conn_total 462712
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135346
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5557
telemt_desync_full_logged_total 1553
telemt_desync_suppressed_total 4004
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 2099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1988
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10243
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9775
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1135003
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 14990130824 (13.96 GB)
telemt_user_octets_to_client{user="hello"} 333278818116 (310.39 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 62208.9 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487590
telemt_connections_bad_total 7332
telemt_handshake_timeouts_total 25768
telemt_upstream_connect_attempt_total 21843
telemt_upstream_connect_success_total 18924
telemt_upstream_connect_fail_total 2919
telemt_upstream_connect_attempts_per_request{bucket="1"} 21843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2919
telemt_me_keepalive_timeout_total 2044
telemt_me_reconnect_attempts_total 13668
telemt_me_reconnect_success_total 12842
telemt_me_reader_eof_total 13584
telemt_me_idle_close_by_peer_total 13582
telemt_me_route_drop_no_conn_total 212271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414547
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2066
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1429
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12988
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12820
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 416815
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 4055433298 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 109922819036 (102.37 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 62208.8 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820291
telemt_connections_bad_total 6905
telemt_handshake_timeouts_total 44372
telemt_upstream_connect_attempt_total 16801
telemt_upstream_connect_success_total 16592
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 16801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 736
telemt_me_reconnect_attempts_total 24737
telemt_me_reconnect_success_total 12382
telemt_me_reader_eof_total 13343
telemt_me_idle_close_by_peer_total 13343
telemt_me_route_drop_no_conn_total 278611
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734114
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2119
telemt_desync_full_logged_total 623
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 772
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 12924
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12371
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 734905
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 8604280417 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 217123197565 (202.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 62209.2 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626776
telemt_connections_bad_total 58256
telemt_handshake_timeouts_total 61964
telemt_upstream_connect_attempt_total 17452
telemt_upstream_connect_success_total 17452
telemt_upstream_connect_attempts_per_request{bucket="1"} 17452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 663
telemt_me_reconnect_attempts_total 15369
telemt_me_reconnect_success_total 14319
telemt_me_reader_eof_total 15206
telemt_me_idle_close_by_peer_total 15205
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 192231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486001
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 684
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14487
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14297
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 485400
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 5749492688 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 133074209404 (123.94 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 62208.9 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655084
telemt_connections_bad_total 5972
telemt_handshake_timeouts_total 4743
telemt_upstream_connect_attempt_total 17314
telemt_upstream_connect_success_total 17242
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 17782
telemt_me_reconnect_success_total 13996
telemt_me_reader_eof_total 14786
telemt_me_idle_close_by_peer_total 14786
telemt_me_route_drop_no_conn_total 218784
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597157
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2748
telemt_desync_full_logged_total 1039
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1148
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14291
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13996
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 596868
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 10067097371 (9.38 GB)
telemt_user_octets_to_client{user="hello"} 218207650526 (203.22 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 135
```