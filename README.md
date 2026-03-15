# Server Metrics 2026-03-15 07:46:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 34343.4 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634100
telemt_connections_bad_total 23015
telemt_handshake_timeouts_total 4378
telemt_upstream_connect_attempt_total 7172
telemt_upstream_connect_success_total 7145
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5437
telemt_me_reconnect_success_total 5409
telemt_me_reader_eof_total 5725
telemt_me_idle_close_by_peer_total 5725
telemt_me_route_drop_no_conn_total 198298
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534568
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1485
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1016
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5480
telemt_me_writer_restored_same_endpoint_total 5398
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 534564
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 6757224508 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 194318555976 (180.97 GB)
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 34344.3 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234668
telemt_connections_bad_total 18359
telemt_handshake_timeouts_total 9343
telemt_upstream_connect_attempt_total 9437
telemt_upstream_connect_success_total 9390
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 7329
telemt_me_reader_eof_total 7759
telemt_me_idle_close_by_peer_total 7759
telemt_me_route_drop_no_conn_total 61437
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194437
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 733
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7368
telemt_me_writer_restored_same_endpoint_total 7321
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 194718
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 3019670983 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 71670052412 (66.75 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 34344.4 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430053
telemt_connections_bad_total 12408
telemt_handshake_timeouts_total 40611
telemt_upstream_connect_attempt_total 7734
telemt_upstream_connect_success_total 7700
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 7734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 5989
telemt_me_reconnect_success_total 5955
telemt_me_reader_eof_total 6310
telemt_me_idle_close_by_peer_total 6310
telemt_me_route_drop_no_conn_total 112093
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 673
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6024
telemt_me_writer_restored_same_endpoint_total 5936
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 348498
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 5298687292 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 144473142600 (134.55 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 34344.1 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277887
telemt_connections_bad_total 45892
telemt_handshake_timeouts_total 19269
telemt_upstream_connect_attempt_total 11053
telemt_upstream_connect_success_total 10793
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 11053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21692
telemt_me_reconnect_success_total 9056
telemt_me_reader_eof_total 9731
telemt_me_idle_close_by_peer_total 9731
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 69961
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206510
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 382
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9524
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9030
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 206511
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 1774727916 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 68603825956 (63.89 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 34345.3 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216239
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 2118
telemt_upstream_connect_attempt_total 7575
telemt_upstream_connect_success_total 7543
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5835
telemt_me_reconnect_success_total 5807
telemt_me_reader_eof_total 6200
telemt_me_idle_close_by_peer_total 6200
telemt_me_route_drop_no_conn_total 65951
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 586
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5866
telemt_me_writer_restored_same_endpoint_total 5799
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 202472
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 2086351704 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 83146765716 (77.44 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 109
```