# Server Metrics 2026-03-15 10:30:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 44153.4 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1073250
telemt_connections_bad_total 65105
telemt_handshake_timeouts_total 8328
telemt_upstream_connect_attempt_total 8889
telemt_upstream_connect_success_total 8850
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6689
telemt_me_reconnect_success_total 6649
telemt_me_reader_eof_total 7022
telemt_me_idle_close_by_peer_total 7022
telemt_me_route_drop_no_conn_total 354817
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904729
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3324
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2387
telemt_desync_frames_bucket_total{bucket="1_2"} 814
telemt_desync_frames_bucket_total{bucket="3_10"} 1299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1211
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6743
telemt_me_writer_restored_same_endpoint_total 6638
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 904726
telemt_user_connections_current{user="hello"} 2284
telemt_user_octets_from_client{user="hello"} 12990630128 (12.10 GB)
telemt_user_octets_to_client{user="hello"} 355333757656 (330.93 GB)
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 44154.0 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421645
telemt_connections_bad_total 23246
telemt_handshake_timeouts_total 17688
telemt_upstream_connect_attempt_total 11654
telemt_upstream_connect_success_total 11593
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9120
telemt_me_reconnect_success_total 9063
telemt_me_reader_eof_total 9591
telemt_me_idle_close_by_peer_total 9591
telemt_me_route_drop_no_conn_total 107601
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333550
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1186
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9150
telemt_me_writer_restored_same_endpoint_total 9055
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 333836
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 4869688783 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 125178452692 (116.58 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 44153.9 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797454
telemt_connections_bad_total 26642
telemt_handshake_timeouts_total 79186
telemt_upstream_connect_attempt_total 9793
telemt_upstream_connect_success_total 9751
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 9793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 7582
telemt_me_reconnect_success_total 7533
telemt_me_reader_eof_total 7968
telemt_me_idle_close_by_peer_total 7968
telemt_me_route_drop_no_conn_total 222175
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585639
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1301
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 825
telemt_desync_frames_bucket_total{bucket="1_2"} 281
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7632
telemt_me_writer_restored_same_endpoint_total 7514
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 585057
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 8599469228 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 233234280500 (217.22 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 44153.7 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439754
telemt_connections_bad_total 55967
telemt_handshake_timeouts_total 25589
telemt_upstream_connect_attempt_total 13243
telemt_upstream_connect_success_total 12918
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 13243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31071
telemt_me_reconnect_success_total 10710
telemt_me_reader_eof_total 11669
telemt_me_idle_close_by_peer_total 11669
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 122728
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330290
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 778
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11442
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10678
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 330200
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 4002957432 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 106170289420 (98.88 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 44154.9 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443635
telemt_connections_bad_total 6148
telemt_handshake_timeouts_total 7169
telemt_upstream_connect_attempt_total 9761
telemt_upstream_connect_success_total 9716
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7549
telemt_me_reconnect_success_total 7512
telemt_me_reader_eof_total 7990
telemt_me_idle_close_by_peer_total 7990
telemt_me_route_drop_no_conn_total 116304
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366840
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1405
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 959
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7597
telemt_me_writer_restored_same_endpoint_total 7504
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 366843
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 4621354880 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 135964373132 (126.63 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 130
```