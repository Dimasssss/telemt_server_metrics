# Server Metrics 2026-03-12 15:56:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35871.7 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293112
telemt_connections_bad_total 20236
telemt_handshake_timeouts_total 12657
telemt_upstream_connect_attempt_total 7128
telemt_upstream_connect_success_total 7089
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 9183
telemt_me_reconnect_success_total 5276
telemt_me_reader_eof_total 5624
telemt_me_idle_close_by_peer_total 5623
telemt_me_route_drop_no_conn_total 461940
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1213590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6321
telemt_desync_full_logged_total 1578
telemt_desync_suppressed_total 4743
telemt_desync_frames_bucket_total{bucket="1_2"} 1628
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 2425
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5464
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5263
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1213273
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 18881833208 (17.59 GB)
telemt_user_octets_to_client{user="hello"} 351017128488 (326.91 GB)
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65492.3 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577245
telemt_connections_bad_total 7534
telemt_handshake_timeouts_total 27580
telemt_upstream_connect_attempt_total 15681
telemt_upstream_connect_success_total 15674
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1212
telemt_me_reconnect_attempts_total 12298
telemt_me_reconnect_success_total 12228
telemt_me_reader_eof_total 12997
telemt_me_idle_close_by_peer_total 12997
telemt_me_route_drop_no_conn_total 170691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515984
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2012
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1382
telemt_desync_frames_bucket_total{bucket="1_2"} 886
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12349
telemt_me_writer_restored_same_endpoint_total 12219
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 516474
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 7981412939 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 183051039598 (170.48 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65492.4 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221364
telemt_connections_bad_total 6258
telemt_handshake_timeouts_total 84917
telemt_upstream_connect_attempt_total 15765
telemt_upstream_connect_success_total 15760
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1018
telemt_me_reconnect_attempts_total 13361
telemt_me_reconnect_success_total 12136
telemt_me_reader_eof_total 12789
telemt_me_idle_close_by_peer_total 12789
telemt_me_route_drop_no_conn_total 331539
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904394
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3803
telemt_desync_full_logged_total 1169
telemt_desync_suppressed_total 2634
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1854
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12222
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12095
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 904572
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 11944245912 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 283238581385 (263.79 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65492.8 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726214
telemt_connections_bad_total 7714
telemt_handshake_timeouts_total 58360
telemt_upstream_connect_attempt_total 17190
telemt_upstream_connect_success_total 17121
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1401
telemt_me_reconnect_attempts_total 19096
telemt_me_reconnect_success_total 13854
telemt_me_reader_eof_total 14775
telemt_me_idle_close_by_peer_total 14775
telemt_me_route_drop_no_conn_total 247548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14123
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13833
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 624962
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 7875624132 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 246386757588 (229.47 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65492.6 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 822054
telemt_connections_bad_total 9020
telemt_handshake_timeouts_total 6602
telemt_upstream_connect_attempt_total 20640
telemt_upstream_connect_success_total 20387
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 20640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 1148
telemt_me_reconnect_attempts_total 24356
telemt_me_reconnect_success_total 17117
telemt_me_reader_eof_total 17932
telemt_me_idle_close_by_peer_total 17932
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 287782
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757324
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2956
telemt_desync_full_logged_total 1002
telemt_desync_suppressed_total 1954
telemt_desync_frames_bucket_total{bucket="1_2"} 836
telemt_desync_frames_bucket_total{bucket="3_10"} 1011
telemt_desync_frames_bucket_total{bucket="gt_10"} 1109
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17521
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17080
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 757223
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 9187379128 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 212867982220 (198.25 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 106
```