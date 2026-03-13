# Server Metrics 2026-03-13 02:24:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73536.9 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2080991
telemt_connections_bad_total 27786
telemt_handshake_timeouts_total 22144
telemt_upstream_connect_attempt_total 14552
telemt_upstream_connect_success_total 14469
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1263
telemt_me_reconnect_attempts_total 19661
telemt_me_reconnect_success_total 10800
telemt_me_reader_eof_total 11671
telemt_me_idle_close_by_peer_total 11670
telemt_me_route_drop_no_conn_total 805177
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1924271
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8703
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2294
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11230
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10787
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1923730
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 28072682520 (26.14 GB)
telemt_user_octets_to_client{user="hello"} 670039045304 (624.02 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103157.3 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852262
telemt_connections_bad_total 11810
telemt_handshake_timeouts_total 32366
telemt_upstream_connect_attempt_total 26269
telemt_upstream_connect_success_total 26240
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3452
telemt_me_reconnect_attempts_total 19565
telemt_me_reconnect_success_total 19458
telemt_me_reader_eof_total 20726
telemt_me_idle_close_by_peer_total 20726
telemt_me_route_drop_no_conn_total 274195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772896
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 19647
telemt_me_writer_restored_same_endpoint_total 19449
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 774799
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 12361341180 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 292225829707 (272.16 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103157.1 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1767826
telemt_connections_bad_total 9177
telemt_handshake_timeouts_total 118487
telemt_upstream_connect_attempt_total 24052
telemt_upstream_connect_success_total 24042
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1603
telemt_me_reconnect_attempts_total 19813
telemt_me_reconnect_success_total 18550
telemt_me_reader_eof_total 19643
telemt_me_idle_close_by_peer_total 19642
telemt_me_route_drop_no_conn_total 576998
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1390948
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5017
telemt_desync_full_logged_total 1537
telemt_desync_suppressed_total 3480
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1815
telemt_desync_frames_bucket_total{bucket="gt_10"} 2399
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 18724
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18509
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1390543
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 20184537908 (18.80 GB)
telemt_user_octets_to_client{user="hello"} 501853776441 (467.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103157.3 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104844
telemt_connections_bad_total 13134
telemt_handshake_timeouts_total 73193
telemt_upstream_connect_attempt_total 36120
telemt_upstream_connect_success_total 33847
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 35846
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11285
telemt_me_reconnect_attempts_total 31765
telemt_me_reconnect_success_total 22843
telemt_me_reader_eof_total 24684
telemt_me_idle_close_by_peer_total 24677
telemt_me_route_drop_no_conn_total 391660
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 947332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23272
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22820
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 952514
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 14525482177 (13.53 GB)
telemt_user_octets_to_client{user="hello"} 373783517062 (348.11 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 103157.5 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1220662
telemt_connections_bad_total 12625
telemt_handshake_timeouts_total 9546
telemt_upstream_connect_attempt_total 32616
telemt_upstream_connect_success_total 32215
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 32616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 1888
telemt_me_reconnect_attempts_total 40804
telemt_me_reconnect_success_total 27075
telemt_me_reader_eof_total 28465
telemt_me_idle_close_by_peer_total 28465
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 456457
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1128505
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4198
telemt_desync_full_logged_total 1490
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1258
telemt_desync_frames_bucket_total{bucket="3_10"} 1387
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27812
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27026
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 1128360
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 13812512024 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 389796322580 (363.03 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 35
```